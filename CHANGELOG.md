## [1.6.1](https://github.com/Mario-F/cloud-toolbox/compare/v1.6.0...v1.6.1) (2025-03-24)


### Bug Fixes

* **tools:** :bug: helmfile repo was moved ([69112ed](https://github.com/Mario-F/cloud-toolbox/commit/69112edab8a9a7080d27a91f592fd7e988a02871))
* **tools:** add noninteractive install for apt packages ([ecae481](https://github.com/Mario-F/cloud-toolbox/commit/ecae4810dbadae2440af2b262ed6ef437f7c8782))
* **tools:** install more basic tools ([5aef89d](https://github.com/Mario-F/cloud-toolbox/commit/5aef89d6659220942a126d63b39139776e835442))

# [1.6.0](https://github.com/Mario-F/cloud-toolbox/compare/v1.5.1...v1.6.0) (2025-03-24)


### Bug Fixes

* bitnami chart workaround ([293fc66](https://github.com/Mario-F/cloud-toolbox/commit/293fc66625fdcb79c55a3177321b347e6133c498))
* **provisioning:** ingress antiaffinity ([1b4127d](https://github.com/Mario-F/cloud-toolbox/commit/1b4127d66a44dbaefde810939cae6b71298d00e6))
* **provisioning:** made ingress podAntiAffinity make sense ([40acb23](https://github.com/Mario-F/cloud-toolbox/commit/40acb238f64db2d1d8597fc4483520c233f6dda9))
* **provisioning:** multi ingress setup was not operable ([f5da499](https://github.com/Mario-F/cloud-toolbox/commit/f5da499d7cf24e39ac02a75d418d9fc9062b3321))


### Features

* **ansible:** add swapoff notifier ([cd3d7e3](https://github.com/Mario-F/cloud-toolbox/commit/cd3d7e376e611f25775aa60888faeb253bff6cf3))
* **ansible:** added conditions and dns replacement ([3a31c50](https://github.com/Mario-F/cloud-toolbox/commit/3a31c50c3d11ab743e89b38b609b151ba51656a6))
* **ansible:** added docker install ([a5f2b8b](https://github.com/Mario-F/cloud-toolbox/commit/a5f2b8b9fcec0d3143d3649e951069f4a77733ab))
* **ansible:** added first role task swap ([13f096f](https://github.com/Mario-F/cloud-toolbox/commit/13f096f6696ed7052a5ad9a7b444665fcda967e1))
* **ansible:** added swapoff handler ([a2d9556](https://github.com/Mario-F/cloud-toolbox/commit/a2d9556f595b3db1709be4b16d93c741e38fcf2f))
* **ansible:** dont make docker the default install ([0949af5](https://github.com/Mario-F/cloud-toolbox/commit/0949af531e82968c9e05618c7a746e066ebb7d25))
* **ansible:** moved cloudnode -> cloud ([d55edea](https://github.com/Mario-F/cloud-toolbox/commit/d55edeafb584521f53fcd2c9b5ab121e243e620b))
* **creating:** added ansible collection ([9f9225c](https://github.com/Mario-F/cloud-toolbox/commit/9f9225cf21898345c0575100e7fd397a57d9ffc6))
* **creating:** updated galaxy.yml ([978143c](https://github.com/Mario-F/cloud-toolbox/commit/978143c9572a17232a7b07315ed3f0cb0b418d98))
* **tools:** persist zsh history to docker folder ([f694a27](https://github.com/Mario-F/cloud-toolbox/commit/f694a27d20d5d709eb264f3c75d47cb0f12a2467))
* **tools:** updated versions ([636dd19](https://github.com/Mario-F/cloud-toolbox/commit/636dd197b89e83e4136a6e39af069a3e74c9611e))

## [1.5.1](https://github.com/Mario-F/cloud-toolbox/compare/v1.5.0...v1.5.1) (2022-01-15)


### Bug Fixes

* **tools:** build docker image only for amd64 ([e1bc42b](https://github.com/Mario-F/cloud-toolbox/commit/e1bc42b6bf513e1a816c697ecd865e18c8e5b0e8))

# [1.5.0](https://github.com/Mario-F/cloud-toolbox/compare/v1.4.0...v1.5.0) (2022-01-15)


### Bug Fixes

* **provisioning:** global-config should not mandatory ([4af419d](https://github.com/Mario-F/cloud-toolbox/commit/4af419db9836142c20a048882d5aff9ea1af96b5))
* **provisioning:** local values should prefer before global ([fe90e8f](https://github.com/Mario-F/cloud-toolbox/commit/fe90e8f32a7adbef4dace010ecc3bf9b51183c51))
* **provisioning:** prometheus should select all pod,rules,monitors ([d2e24e2](https://github.com/Mario-F/cloud-toolbox/commit/d2e24e2297e20e47255bb5091dacddd0d3c136e0))
* **provisioning:** removed hetzner cloud controller for bare ([c31c0e1](https://github.com/Mario-F/cloud-toolbox/commit/c31c0e18e0e79af0e8fe14b79906a0afa4b42f02))
* **provisioning:** removed metallb from hcloud-bare ([a3db21b](https://github.com/Mario-F/cloud-toolbox/commit/a3db21bbbe7d5f55a83923b569a05b0ac201635c))


### Features

* **provisioning:** add storage configs to prometheus ([b77f6cf](https://github.com/Mario-F/cloud-toolbox/commit/b77f6cfc0ac9ff04c507109c0530434a56b2bf50))
* **provisioning:** added grafana configuration ([eaa7ebe](https://github.com/Mario-F/cloud-toolbox/commit/eaa7ebe007550930fe9a82834625e90158aebcaa))
* **provisioning:** added hcloud csi storage provider ([9531357](https://github.com/Mario-F/cloud-toolbox/commit/9531357f2d0f5c54fadbea37691d105ab12703e7))
* **provisioning:** added hcloud-bare config ([3f2844c](https://github.com/Mario-F/cloud-toolbox/commit/3f2844c553f7e829837708fdf96199a10198de19))
* **provisioning:** added hetzner cloud controller ([86c5468](https://github.com/Mario-F/cloud-toolbox/commit/86c5468f1a7ebcc216a0bc45cb43b86ae0697863))
* **provisioning:** added hostpath-provisioner ([bce3a77](https://github.com/Mario-F/cloud-toolbox/commit/bce3a77a984784bc2a7b61315a44803e83e061f6))
* **provisioning:** added metallb ([524bd32](https://github.com/Mario-F/cloud-toolbox/commit/524bd325189ffdefb1e8b1db7b8cc0ba55c82324))
* **provisioning:** added prom ingress with opt basic auth ([5787994](https://github.com/Mario-F/cloud-toolbox/commit/57879949f4275952b9a93b767d1196dea9dd7932))
* **provisioning:** make ingressShim configurable ([c6a6ce1](https://github.com/Mario-F/cloud-toolbox/commit/c6a6ce177bf1a13a6d4e912c5d5e21fbbb19b6ff))
* **provisioning:** make service versions pinnable ([bc8067a](https://github.com/Mario-F/cloud-toolbox/commit/bc8067a619a798e8b009eb6be23fe52a637187d4))
* **provisioning:** moved metrics-server to monitoring ([72dd7d4](https://github.com/Mario-F/cloud-toolbox/commit/72dd7d4eedf7be0e77247b5e5d503606a74c2554))
* **provisioning:** renamed testcloud to hcloud-k3s ([8d21af0](https://github.com/Mario-F/cloud-toolbox/commit/8d21af0bf178b4eafd4974a4a74577fffaaa1bb8))
* **provisioning:** update default kube-prometheus-stack to latest ([0bce5ef](https://github.com/Mario-F/cloud-toolbox/commit/0bce5ef096d05e0ddb0a9fbff66054ea834a1699))

# [1.4.0](https://github.com/Mario-F/cloud-toolbox/compare/v1.3.0...v1.4.0) (2021-12-24)


### Features

* **provisioning:** added hetzner external dns support ([4567db6](https://github.com/Mario-F/cloud-toolbox/commit/4567db65d7c156f2ab6f3b631410be06edde2a5b))
* **provisioning:** added hetzner webhook for cert-manager ([3f1b66a](https://github.com/Mario-F/cloud-toolbox/commit/3f1b66aa8fb69c6745d5228bd57918ea2721d2ee))

# [1.3.0](https://github.com/Mario-F/cloud-toolbox/compare/v1.2.0...v1.3.0) (2021-12-24)


### Features

* **hetzner-k3s:** update vitobotta/hetzner-k3s version ([20309d0](https://github.com/Mario-F/cloud-toolbox/commit/20309d08402425a51a62a5ff22099959e5bfcd9e))
* **provisioning:** add readme ([07d4122](https://github.com/Mario-F/cloud-toolbox/commit/07d4122ce0416a81b4a4a6d74d7dcfabfde50e15))
* **provisioning:** moved environments directly into helmfile ([e8849c3](https://github.com/Mario-F/cloud-toolbox/commit/e8849c382679813e7e3a89a020883c29be42bb19))
* **provisioning:** moved helm repos to sub helmfiles ([a28ce78](https://github.com/Mario-F/cloud-toolbox/commit/a28ce7889dc948af0fb273d420d5ac4d4f44fd7f))
* **provisioning:** moved subhelmfiles to extra directory ([5e67cfa](https://github.com/Mario-F/cloud-toolbox/commit/5e67cfa15d1d7c56af59ccfe7e8e0360330e5e4e))
* **tools:** update tool versions ([2d0bfef](https://github.com/Mario-F/cloud-toolbox/commit/2d0bfefd30441af32c16ccca3ec582ed4dfbfccf))

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
