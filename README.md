# My Bun Template

A template repository for projects using Bun, Biome, and TypeScript.

## Overview

This template provides basic settings and a recommended directory structure to help you quickly start your Bun project.

## Features

- **Development Environment Setup**: Includes configuration files for VSCode (`.vscode`) and DevContainer (`.devcontainer`) to support a smooth development environment setup.
- **Bun Configuration**: Comes with a `bunfig.toml` file to easily manage your Bun settings.
- **GitHub Template**: This repository is set as a GitHub template, making it easy to use as a base for new projects.

## Usage

1. **Create a Repository**:
   - Use this template to create a new repository.

2. **Install Dependencies**:
   - Bun directly handles external modules, so no special installation steps are required.

3. **Run Scripts**:
   - Use the following command to run Bun scripts:

     ```bash
     bun run your_script.ts
     ```

## Development Environment Setup

- **Deprecation of DevContainer**:
  - While this repository includes a DevContainer configuration to quickly set up a development environment, it is considered **deprecated** for the following reasons:
    - **Overhead from Virtual Layers**: Using DevContainer adds extra resource requirements, which can result in slower performance.
    - **Limited Benefits**: Bun is lightweight and easy to configure, making it unnecessary to rely on DevContainer for most use cases. A direct local development setup is recommended for a simpler and more efficient experience.
  - You can safely remove the DevContainer configuration if it is not needed for your workflow.

## Contribution

Contributions are welcome! Please follow these steps:

1. Fork this repository.
2. Create a new branch.
3. Commit your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
