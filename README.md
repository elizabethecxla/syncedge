# SyncEdge

SyncEdge is a Python program designed to enable quick switching between multiple desktops and manage virtual desktops on Windows. This tool provides a simple interface to navigate through your virtual desktops efficiently.

## Features

- List available virtual desktops.
- Switch to a specified virtual desktop.
- Automatically cycle through desktops with a configurable delay.

## Requirements

- Windows 10 or later.
- Python 3.x.
- Administrative privileges to access virtual desktop management.

## Installation

1. Clone the repository or download the `syncedge.py` file.
2. Ensure Python 3.x is installed on your system.
3. Open a terminal or command prompt and navigate to the directory where `syncedge.py` is located.

## Usage

Run the program using the following command:

```bash
python syncedge.py
```

The program will list the available virtual desktops and automatically switch between them every 5 seconds. You can modify the delay by adjusting the `time.sleep(5)` value in the code.

## Notes

- This script uses Windows APIs, which require administrative privileges.
- The current implementation includes placeholder functions for listing and switching desktops. Future versions will include complete implementations for these functionalities.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License.