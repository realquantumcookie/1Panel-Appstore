# DPanel

DPanel is a lightweight visual management panel for Docker and Podman containers.

![](https://img.shields.io/badge/Copyright-arch3rPro-ff9800?style=flat&logo=github&logoColor=white)

## Overview

DPanel provides a native Chinese interface that is more suitable for Chinese environments, while also supporting English, Japanese, and multiple other languages. The installation is simple with extremely low resource consumption, making it perfect for various NAS devices, set-top boxes, and small servers. The panel runs as a container without requiring privileges, making it dependency-free and non-intrusive to the host system, ensuring safety and reliability.

## Features

The panel provides essential container management functionality including:

- **Container Management**: Manage Docker/Podman containers
- **Compose Management**: Support for multiple types of Compose projects
- **Image Management**: Container image management and operations
- **File Management**: Manage container internal files
- **Nginx Integration**: Built-in Nginx for convenient container port forwarding
- **Multi-Server Support**: Add and manage multiple Docker servers via Docker API and SSH
- **Host Management**: Manage host systems through SSH and SFTP

## Default Credentials

```
Username: admin
Password: admin
```

## Installation

DPanel runs as a container and can be easily deployed using Docker Compose or other container management tools. For specific installation instructions, please refer to the included docker-compose.yml file.

## System Requirements

- Minimal resource requirements
- Compatible with NAS devices, set-top boxes, and small servers
- Supports Docker and Podman container runtimes

## License

Copyright © arch3rPro