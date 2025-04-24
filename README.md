# devcontainer-mstoecker

A Visual Studio Code devcontainer configuration based on Ubuntu 24.04 with tools for Azure, Terraform, and Databricks development.

## Features

This devcontainer includes:

- **Base Image**: Ubuntu 24.04
- **Tools**:
  - Azure CLI
  - Terraform
  - Databricks CLI
  - Docker-in-Docker support
  - GitHub CLI
  - Common utilities (git, curl, wget, jq, etc.)
- **VS Code Extensions**:
  - Azure Terraform
  - Terraform
  - Azure CLI
  - Azure Functions
  - Docker
  - Azure Resource Manager
  - Python
  - Databricks
  - YAML
  - Azure Account
  - GitHub Copilot
  - GitLens

## Usage

1. Ensure you have [VS Code](https://code.visualstudio.com/) and the [Remote - Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers) installed.
2. Clone this repository.
3. Open the repository folder in VS Code.
4. When prompted to "Reopen in Container", click "Reopen in Container" to start the development container.
   - Alternatively, use the VS Code command palette (F1) and select "Remote-Containers: Reopen in Container"

## Customization

You can customize this devcontainer by:

- Adding additional packages to the Dockerfile
- Adding more VS Code extensions in devcontainer.json
- Modifying the features section in devcontainer.json