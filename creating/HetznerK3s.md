# Create a test environment

## Hetzner-k3s

Setup a test k3s with hetzner-k3s provisioneer from: <https://github.com/vitobotta/hetzner-k3s>

### Config

Copy the template into secure folder and replace the Hetzner API Token with your own:

```bash
cp templates/testcloud.yaml templates/secure.yaml
vim templates/secure.yaml
```

### Usage

```bash
# Start
docker run --rm -it -v ${PWD}/secure:/cluster -v ${HOME}/.ssh:/tmp/.ssh vitobotta/hetzner-k3s:v0.4.3 create-cluster --config-file /cluster/testcloud.yaml

# Kubeconfig
sudo chown $(id -u):$(id -g) ${PWD}/secure/kubeconfig
export KUBECONFIG=${PWD}/secure/kubeconfig

# Delete
docker run --rm -it -v ${PWD}/secure:/cluster -v ${HOME}/.ssh:/tmp/.ssh vitobotta/hetzner-k3s:v0.4.3 delete-cluster --config-file /cluster/testcloud.yaml
```

**Warning!** Keep in mind that created loadbalancer ressources will not deleted and need to cleanup manually!
