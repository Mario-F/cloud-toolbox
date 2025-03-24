FROM ubuntu:24.04

ARG DEBIAN_FRONTEND=noninteractive
RUN apt-get update && \
  apt-get install -y --no-install-recommends \
  curl bash tar gzip ca-certificates git openssl gnupg wget \
  less vim

RUN mkdir /install
WORKDIR /install

RUN curl -Lo sops.deb https://github.com/mozilla/sops/releases/download/v3.7.1/sops_3.7.1_amd64.deb
RUN apt install ./sops.deb && rm sops.deb

RUN curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
RUN chmod +x ./kubectl
RUN mv ./kubectl /usr/local/bin/kubectl
RUN mkdir /root/.kube

RUN curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/master/scripts/get-helm-3
RUN chmod +x get_helm.sh
RUN ./get_helm.sh
RUN helm plugin install https://github.com/databus23/helm-diff --version v3.10.0
RUN helm plugin install https://github.com/jkroepke/helm-secrets --version v4.6.3
RUN helm plugin install https://github.com/hypnoglow/helm-s3.git --version v0.16.3
RUN helm plugin install https://github.com/aslafy-z/helm-git.git --version v1.3.0

RUN curl -fsSL -o install_kustomize.sh https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/hack/install_kustomize.sh
RUN chmod +x install_kustomize.sh
RUN ./install_kustomize.sh
RUN mv ./kustomize /usr/local/bin/kustomize

RUN curl -Lo helmfile.tar.gz https://github.com/helmfile/helmfile/releases/download/v0.171.0/helmfile_0.171.0_linux_amd64.tar.gz
RUN tar -zxvf helmfile.tar.gz
RUN chmod +x ./helmfile
RUN mv helmfile /usr/local/bin/

RUN sh -c "$(wget -O- https://github.com/deluan/zsh-in-docker/releases/download/v1.2.1/zsh-in-docker.sh)"
RUN chsh -s /usr/bin/zsh root

RUN rm -rf /var/lib/apt/lists/*

ENV HISTFILE /root/docker/.zsh_history_cloud-toolbox
RUN mkdir /root/docker

RUN mkdir /app
WORKDIR /app
CMD ["zsh"]
