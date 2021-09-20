# grid3_client_ts

> TODO: WHY THIS DOC, WHAT IS PURPOSE

Github repo: [grid3_client_ts](https://github.com/threefoldtech/grid3_client_ts.git)

## Prerequisites

- node
- npm

## Installation

```bash
npm install typescript -g
npm install
```

## How to run

*note*: Before running any of the scripts, the twinid, nodes selection, and the mnemonics of the user should be added in the scripts themsevles (the flow is still being adjusted)

- One virtual machine with ubuntu

```bash
cd scripts
tsc test.ts && node test.js
```

- Two virtual machines with kubernetes master and worker nodes

```bash
cd scripts
tsc test_kubernetes.ts && node test_kubernetes.js
```

>TODO: where are these scripts?

check [deploy_with_typescript](deploy_with_typescript) for more detailed information