# [1.2.0](https://github.com/Mario-F/cloud-toolbox/compare/v1.1.0...v1.2.0) (2021-12-19)


### Bug Fixes

* **provisioning:** dont fail if release has no default installed value ([536b129](https://github.com/Mario-F/cloud-toolbox/commit/536b1293758619dcb01adfc1c13a6eb318f159d1))
* **provisioning:** fix yaml string ([cbb2a87](https://github.com/Mario-F/cloud-toolbox/commit/cbb2a873a67a492aa484dc0a815fdfb3fb1a556f))
* **provisioning:** updated deprecated ingressclass values ([2ceded7](https://github.com/Mario-F/cloud-toolbox/commit/2ceded776b6a843cb3925693dc9948f73b3361d3))
* **proxmox:** removed token auth because it does not have enough right ([e3e4e32](https://github.com/Mario-F/cloud-toolbox/commit/e3e4e32ec2275390b8a1e2ac16ca906ee52f2015))


### Features

* **provisioning:** added a iteratable ingress config ([1641111](https://github.com/Mario-F/cloud-toolbox/commit/1641111268a854e3d0eab4827f9c829ac94768e8))
* **provisioning:** added default ingress ([f23940f](https://github.com/Mario-F/cloud-toolbox/commit/f23940f9ab7b806ae417d5a09e475d5cbb7a1a05))
* **provisioning:** added helmfile basics for testcloud ([2948236](https://github.com/Mario-F/cloud-toolbox/commit/2948236c8927bf3719b08bff70e78f1b300df8e7))
* **provisioning:** added services helmfile with cert-manager ([5b8250e](https://github.com/Mario-F/cloud-toolbox/commit/5b8250e87b849c5acabff1032eda0abff98ef16f))
* **provisioning:** added soft affinity as default for ingress controllers ([d6c12ac](https://github.com/Mario-F/cloud-toolbox/commit/d6c12ac54a04179f048545ba04b2c4018d6de090))
* **provisioning:** integrated prometheus stack ([8e1896d](https://github.com/Mario-F/cloud-toolbox/commit/8e1896d064980c1ada406fbc69d16b8106d000e4))
* **provisioning:** make multi ingress version configurable ([dff8e66](https://github.com/Mario-F/cloud-toolbox/commit/dff8e668038ce3e7b294e8ec7b79ec6518503c59))
* **proxmox:** added template env file ([e876d11](https://github.com/Mario-F/cloud-toolbox/commit/e876d116477f0f477287444e689cd5f3ac58eb73))
* **proxmox:** starting proxmox create with ansible ([c8d0cb3](https://github.com/Mario-F/cloud-toolbox/commit/c8d0cb395940dac858d719657cdc3abbee139703))
* **proxmox:** testing proxmox prov with ansible ([64aaffb](https://github.com/Mario-F/cloud-toolbox/commit/64aaffb23c69ff4e6b176d44849b2f1256241d12))
* **proxmox:** use env vars for credentials ([9e4ec27](https://github.com/Mario-F/cloud-toolbox/commit/9e4ec27a15d4627aac5357667ad8c1ed419b04b9))

# [1.1.0](https://github.com/Mario-F/cloud-toolbox/compare/v1.0.0...v1.1.0) (2021-10-23)


### Features

* **hetzner-k3s:** added setup ([ad89b8a](https://github.com/Mario-F/cloud-toolbox/commit/ad89b8affc857592df5db588dedf00ebf52e8c70))

# 1.0.0 (2021-10-22)


### Features

* added automatic release process ([d289183](https://github.com/Mario-F/cloud-toolbox/commit/d289183c29b3efcd096b8e71c114a88db32e5657))
* added tools dockerfile ([a92a2ab](https://github.com/Mario-F/cloud-toolbox/commit/a92a2ab61975400105d8b969543c8a7609031308))
