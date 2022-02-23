# Python Remote-Container Development Environments

## Description

VSCode Docker remote container development environment for Python

## Installed Extensions

### Common

Please refer to [base image README.md](../base/README.md) .

### Language-Specific

- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance)
- [Python Docstring Generator](https://marketplace.visualstudio.com/items?itemName=njpwerner.autodocstring)
- [Better TOML](https://marketplace.visualstudio.com/items?itemName=bungcip.better-toml)
<!-- - [reStructuredText](https://marketplace.visualstudio.com/items?itemName=lextudio.restructuredtex) -->
<!-- - [reStructuredText Syntax highlighting](https://marketplace.visualstudio.com/items?itemName=trond-snekvik.simple-rst) -->

## Notice

### Common

- [`.devcontainer/docker-compose.yml`](./.devcontainer/docker-compose.yml) and [`.devcontainer/Dockerfile`](./.devcontainer/Dockerfile) are completely same with [`../base/.devcontainer`](../base/.devcontainer) one. However, currently docker-compose build with their symlinks are not working properly. So now they are just copied ones (hoping to fix this issue: [https://github.com/docker/compose/issues/7397](https://github.com/docker/compose/issues/7397)) .

For other notice(s), please refer to [base image README.md](../base/README.md) .