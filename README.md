
# Repositoria.ir

**Repositoria.ir** is a repository mirroring service designed to provide high-availability access to essential development tools and packages. By mirroring various repositories, we ensure that developers have reliable access to dependencies and builds, especially in regions with connectivity challenges or for organizations requiring private repository mirrors.

## Features

- **Comprehensive Mirrors**: We mirror a wide range of development repositories, including but not limited to:
  - PHP
  - Python
  - Debian
  - Ubuntu
  - Docker registries
  - npm

- **Dedicated Subdomains**: Each mirrored repository is accessible via its dedicated subdomain for streamlined access. For example:
  - `ubuntu.repositoria.ir` for Ubuntu packages
  - `debian.repositoria.ir` for Debian packages

- **High Availability**: Our infrastructure is optimized for performance and reliability, ensuring that mirrored content is consistently accessible.

## Getting Started

To utilize our mirrored repositories:

1. **Select the Appropriate Mirror**: Identify the repository mirror you wish to use (e.g., Ubuntu, Debian).

2. **Update Your Configuration**: Modify your system or development environment's configuration to point to our mirror. For instance, to use the Debian mirror, update your `sources.list` as follows:

   ```bash
   deb http://debian.repositoria.ir/debian/ stable main
