# Linux Kernel Auto Remover
A simple script to automatically remove old Linux kernel versions after a new one has been installed.

## Description
This script uses a combination of a post-installation hook and a systemd service to remove old Linux kernel versions. The script checks if the newly installed kernel has the same major version as the currently running kernel, and if so, removes the old kernel.

## Installation
Copy the files to there destinations, make the scripts executable, reload the systemd daemon and enable the service.

## Usage
The script will automatically run after a new kernel has been installed and will remove the old kernel if it has the same major version as the newly installed kernel.

## License
This project is licensed under the MIT License.

## Contributing
Contributions are welcome! If you have any suggestions or bug reports, please open an issue or submit a pull request.