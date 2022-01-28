# Provisioning

!! DEPRECATED - MOVED TO -> https://github.com/Mario-F/helmfile-templates !!

The provisioning will help your kubernetes cluster to become an fully automated workhorse with just some konfiguration needed.

This is done with [Helmfile](https://github.com/roboll/helmfile) and extensive use of templating in sub helmfiles.

## Requriements

To get started you need:

* Kubectl installed: <https://kubernetes.io/docs/tasks/tools>
* Helm installed: <https://helm.sh/docs/helm/helm_install>
* Helmfile installed: <https://github.com/roboll/helmfile>
* A working kubernetes cluster

## Usage

Copy the helmfiles folder into your own project (this will become a sep. git repo later on).

Create your own helmfile.yaml, the files in this folder serving as an example how to use the sub helmfiles.
