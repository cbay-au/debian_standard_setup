# DigitalOcean Droplet Setup Script

This repository contains a Bash script designed to automate the setup of a Debian-based server, particularly useful for setting up a DigitalOcean droplet. The script installs various utilities and configures the system for development and operational tasks.

## Features

- Interactive menu system for selecting components to install
- Automatic privilege escalation handling for non-root users
- System updates and upgrades
- Installation of essential packages and tools
- Configuration of `.bashrc` and other shell settings
- Installation of development tools like Python, Go, and Docker
- Setup of custom scripts and configurations

## Prerequisites

- A Debian-based server (e.g., a DigitalOcean droplet)
- Either root access or a user with sudo privileges
- `curl` installed on the server

## Usage

To run the script, use the following command:

### Running Specific Functions

To run only the `wsl` function options, use:

## Script Functions

- **`main`**: The default function that runs the full setup process.

## Error Handling

The script includes error handling to ensure that any issues during execution are logged and the script exits gracefully.

## Logging

- Standard output is logged to `script.log`.
- Errors are logged to `script_error.log`.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or support, please contact Leighton at leighton@clucas.xxx.