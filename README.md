# DevOps Workstation Setup

This repository documents the setup of my local DevOps workstation and the core tools I will be using throughout my Cloud and DevOps labs.

The goal of this lab was to install the required tools, verify that they are working correctly, and prepare my environment for upcoming practical DevOps tasks.

## Tools Installed

| Tool | Version | Use |
| --- | --- | --- |
| Git | 2.56.0.windows.1 | Version control and tracking changes |
| Azure CLI | 2.90.0 | Managing Azure resources from the terminal |
| Docker | 29.8.2 | Building and running containerized applications |
| Terraform | 1.16.5 | Managing infrastructure as code |
| Visual Studio Code | 1.137.0 | Main development environment |

## Verification

I verified each tool from the terminal using the following commands:

```powershell
git --version
az version
docker --version
terraform -version
code --version
```

For Docker, I also ran:

```powershell
docker run hello-world
```

The `hello-world` container was downloaded and executed successfully, confirming that Docker Desktop and the Docker engine were working correctly.

## What I Learned

Setting up the tools helped me understand the role each one plays in a DevOps workflow.

- **Git** is used to track changes and manage different versions of a project.
- **Azure CLI** makes it possible to work with Azure directly from the terminal.
- **Docker** packages applications into containers so they can run consistently across different environments.
- **Terraform** allows infrastructure to be defined and managed through code.
- **VS Code** provides the workspace and terminal where these tools can be used together.

One thing I noticed during the setup was that installing a tool does not always mean the terminal can use it immediately. In some cases, I had to restart the terminal so Windows could recognize the updated PATH.

## Environment

- Operating System: Windows
- Architecture: x64
- Terminal: PowerShell
- Editor: Visual Studio Code
- Docker Backend: WSL 2

## Repository Purpose

This repository is part of my DevOps learning and will serve as evidence of the practical labs and exercises I complete as I continue working with cloud, containers, infrastructure as code, and deployment workflows.

## Author

Chinedum Anderson