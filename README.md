# OCaml DevContainer
This repo can be used to launch an OCaml development environment using Docker and VSCode. It's based on the `ocaml/opam2` Docker image, and uses the VSCode devcontainers feature. The environment comes with some commmon `opam` packages preinstalled.

## Features
- Common IDE features (autocomplete, syntax highlighting, jump-to-definition, etc.) provided by the [reason-vscode](https://github.com/jaredly/reason-language-server) language server.
- Code formatting on save using `ocamlformat` and the [badochov.ocaml-formatter](https://github.com/badochov/ocamlformatter-vscode) extension.
- A fully functional Debian environment that can be accessed through the VSCode integrated terminal or using `docker exec...`.
- Easy to adapt to your use case.

## Requirements
- [Docker](https://docs.docker.com/get-docker/)
- [VSCode](https://github.com/Microsoft/vscode)
- Remote - Containers ([ms-vscode-remote.remote-containers](https://github.com/Microsoft/vscode-remote-release)) extension

## Usage
1. Clone this repo.
2. Start VSCode
3. Run the `Remote-Containers: Open Folder in Container` command.
4. Select this folder.

## Included Opam Packages
- base
- core_kernel
- ounit
- qcheck
- dune
- ocamlformat
