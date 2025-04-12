# Shell Setup

Shell Setup is a repository designed to automate and streamline your shell environment setup with customizable scripts and configurations. It ensures a consistent and efficient command-line experience across different systems. This project is particularly useful for developers who work on multiple systems and want to maintain a consistent shell environment.

## Setup or Installation

Before you start with the setup, ensure that you have a Unix-like shell environment. 

1. Clone this repository to your local machine using `https://github.com/<Your_GitHub_Username>/shell_setup.git`

2. Navigate to the project directory using `cd shell_setup`

3. Run the setup script with `./setup.sh`

Please note that you may need to grant execution permissions to the setup script using `chmod +x setup.sh` before running it.

## Usage

After you've set up the project, you can customize your shell environment by modifying the configuration files in the `config` directory. Here are some examples:

1. To add a new alias, open the `aliases.sh` file and add your alias in the following format:

```bash
alias ll='ls -l'
```

2. To add a new environment variable, open the `env.sh` file and add your variable in the following format:

```bash
export PATH="/usr/local/bin:$PATH"
```

Remember to source your shell profile or restart your terminal session to apply the changes.

## Contributing

We appreciate all contributions. If you're planning to contribute back, please follow the following rules:

1. Make sure your PR (Pull Request) solves a problem. If you're unsure, please open an issue to discuss it before proceeding with a PR.
2. Follow the code style in the existing files.
3. Write detailed commit messages that explain what changes your PR introduces and why.
4. If your PR fixes a bug or adds a feature, please also add a test that verifies this.

## License

This project is licensed under the MIT License. Please see the [LICENSE](LICENSE) file for more details.