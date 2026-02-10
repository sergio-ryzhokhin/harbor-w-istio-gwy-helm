# Intro
This is sample helm chart that builds on top of Harbor and exposes it through pre-installed Istio Ingress Gateway.

### Disclaimer
Source code in this repository is distributed under Apache 2.0 license (see LICENSE file for details) and on "AS IS" basis, without warranties or conditions of any kind, either express or implied.

## Installation
Clone this repository or download it as a ZIP and unpack. 
Create proper values file.
Basic installation would take a couple of simple Helm commands:

1. `helm dependency build`

1. `helm upgrade --install --create-namespace -n harbor -f your_values.yaml harbor ./`
