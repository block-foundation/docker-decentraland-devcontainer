<div align="right">

[![GitHub License](https://img.shields.io/github/license/block-foundation/blocktxt?style=flat-square&logo=readthedocs&logoColor=FFFFFF&label=&labelColor=%23041B26&color=%23041B26&link=LICENSE)](https://github.com/block-foundation/brand/blob/main/LICENSE)
[![devContainer](https://img.shields.io/badge/Container-Remote?style=flat-square&logo=visualstudiocode&logoColor=%23FFFFFF&label=Remote&labelColor=%23041B26&color=%23041B26)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/block-foundation/brand)
[![Docker Pulls](https://img.shields.io/docker/pulls/blockfoundation/decentraland-devcontainer?style=flat-square&logo=docker&logoColor=%23FFFFFF&label=Pulls:&labelColor=%23041B26&color=%23041B26)](https://hub.docker.com/r/blockfoundation/decentraland-devcontainer)
[![Docker Stars](https://img.shields.io/docker/stars/blockfoundation/decentraland-devcontainer?style=flat-square&logo=docker&logoColor=%23FFFFFF&label=Stars:&labelColor=%23041B26&color=%23041B26)](https://hub.docker.com/r/blockfoundation/decentraland-devcontainer)
[![Docker Image Version (latest semver)](https://img.shields.io/docker/v/blockfoundation/decentraland-devcontainer?sort=semver&style=flat-square&logo=docker&logoColor=%23FFFFFF&label=Version:&labelColor=%23041B26&color=%23041B26)](https://hub.docker.com/r/blockfoundation/decentraland-devcontainer/tags)
[![Docker Size](https://img.shields.io/docker/image-size/blockfoundation/decentraland-devcontainer/latest?style=flat-square&logo=docker&logoColor=%23FFFFFF&label=Size:&labelColor=%23041B26&color=%23041B26)](https://hub.docker.com/r/blockfoundation/decentraland-devcontainer)

</div>

---

<div>
    <img align="right" src="https://raw.githubusercontent.com/block-foundation/brand/master/src/logo/logo_gray.png" width="96" alt="Block Foundation Logo">
    <h1 align="left">Decentraland devContainer</h1>
    <h3 align="left">Block Foundation Docker Containers</h3>
</div>

---

<img align="right" width="75%" src="https://raw.githubusercontent.com/block-foundation/brand/master/src/image/repository_cover/block_foundation-containers.jpg"  alt="Block Foundation Containers">

### Contents

- [Introduction](#introduction)
- [Colophon](#colophon)

<br clear="both"/>

---

<div align="right">

[![Report a Bug](https://img.shields.io/badge/Report%20a%20Bug-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23E1E4E5)](https://github.com/block-foundation/docker-decentraland-devcontainer/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=bug_report.yml)
[![Request a Feature](https://img.shields.io/badge/Request%20a%20Feature-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23E1E4E5)](https://github.com/block-foundation/docker-decentraland-devcontainer/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=feature_request.yml)
[![Ask a Question](https://img.shields.io/badge/Ask%20a%20Question-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23E1E4E5)](https://github.com/block-foundation/docker-decentraland-devcontainer/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=question.yml)
[![Make a Suggestion](https://img.shields.io/badge/Make%20a%20Suggestion-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23E1E4E5)](https://github.com/block-foundation/docker-decentraland-devcontainer/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=suggestion.yml)
[![Start a Discussion](https://img.shields.io/badge/Start%20a%20Discussion-GitHub?style=flat-square&&logoColor=%23FFFFFF&color=%23E1E4E5)](https://github.com/block-foundation/docker-decentraland-devcontainer/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected&projects=&template=discussion.yml)

</div>

## Introduction

This development container is built specifically for Decentraland development. It provides a pre-configured environment with Node.js, the Decentraland SDK, and essential Ethereum development tools, making it easier to get started with creating experiences in Decentraland.

## Features

- **Node.js**: The base for running and building projects.
- **Decentraland SDK**: Enables creating scenes and experiences for the Decentraland platform.
- **Ethereum Tools**: Includes `truffle` for smart contract development and `ganache-cli` for simulating an Ethereum blockchain.

## Getting Started

### Prerequisites

- [Docker](https://www.docker.com/products/docker-desktop) installed and running.
- [Visual Studio Code](https://code.visualstudio.com/) with the [Remote - Containers](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) extension installed.

### Steps

1. Clone this repository:

   ``` sh
   git clone <repository-url>
   ```

2. Open the project in VS Code.

   ``` sh
   code <repository-path>
   ```

3. Once in VS Code, open the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS) and select the `Remote-Containers: Open Folder in Container` option. Choose the repository's root directory.

4. The container will build based on the provided `Dockerfile` and launch. It might take a few minutes the first time as it downloads and configures the environment.

5. Once the container is running, you're all set! You can start developing within a consistent environment configured for Decentraland development.

## Forwarded Ports

- `8000`: You might use this for local development servers.
- `8500`: Another port you might use for local development.

## Extensions Included

- ESLint: For linting JavaScript code.
- TSLint: For linting TypeScript code.
- EditorConfig: Helps maintain consistent coding styles.
- Prettier: Code formatter.

Remember, the specifics provided here are based on the earlier `Dockerfile` and `devcontainer.json` examples. You might need to adjust content based on your actual configuration or additional features you include.

---

## Colophon

### Authors

This is an open-source project by the **[Block Foundation](https://www.blockfoundation.io "Block Foundation website")**.

The Block Foundation mission is enabling architects to take back initiative and contribute in solving the mismatch in housing through blockchain technology. Therefore the Block Foundation seeks to unschackle the traditional constraints and construct middle ground between rent and the rigidity of traditional mortgages.

website: [www.blockfoundation.io](https://www.blockfoundation.io "Block Foundation website")

### Development Resources

#### Contributing

We'd love for you to contribute and to make this project even better than it is today!
Please refer to the [contribution guidelines](.github/CONTRIBUTING.md) for information.

### Legal Information

#### Copyright

Copyright &copy; 2023 [Stichting Block Foundation](https://www.blockfoundation.io/ "Block Foundation website"). All Rights Reserved.

#### License

Except as otherwise noted, the content in this repository is licensed under the
[Creative Commons Attribution 4.0 International (CC BY 4.0) License](https://creativecommons.org/licenses/by/4.0/), and
code samples are licensed under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0).

Also see [LICENSE](https://github.com/block-foundation/community/blob/master/src/LICENSE) and [LICENSE-CODE](https://github.com/block-foundation/community/blob/master/src/LICENSE-CODE).

#### Disclaimer

**THIS SOFTWARE IS PROVIDED AS IS WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
