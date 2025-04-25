
# The Lakeshore Repeater Association Flex Broadcast Wedge

A utility for enabling SmartSDR to discover and connect to a remote FlexRadio over the LRA Wireguard VPN, without requiring a SmartLink account. Provided and maintained by the [Lakeshore Repeater Association (LRA)](https://www.kr9rk.com/) for use by its members.

---

## Table of Contents

- [Overview](#overview)
- [Requirements](#requirements)
- [Installation](#installation)
    - [Installing Python on Windows](#installing-python-on-windows)
- [Usage](#usage)
    - [Running the Script on Windows](#running-the-script-on-windows)
- [Security \& Legal Notice](#security--legal-notice)
- [Support](#support)
- [Contributing](#contributing)
- [License](#license)
- [About Lakeshore Repeater Association](#about-lakeshore-repeater-association)

---

## Overview

**Flex Broadcast Wedge** (`flex-wedge.py`) is a Python script that allows SmartSDR clients to discover and connect to a FlexRadio transceiver on a remote network via the LRA Wireguard VPN, bypassing the need for a SmartLink account. *Note: MacOS users do not need to use this script.*

---

## Requirements

- Python 3.7 or newer
- LRA Wireguard VPN connection to the remote FlexRadio network
- FlexRadio SmartSDR Software

---

## Installation

### Installing Python on Windows

If you do not already have Python installed, download the latest version for Windows from the official Python website:

- [Download Python for Windows](https://www.python.org/downloads/windows/)[^1]

After downloading, run the installer and **ensure you check the box to "Add Python to PATH"** during installation for easier command-line use.

To verify your installation, open `Command Prompt` or `PowerShell` and run:

```powershell
python --version
```

or

```powershell
py --version
```

You should see output such as `Python 3.x.x` indicating Python is installed.

### Install Dependencies

From your terminal or command prompt, run:

```powershell
pip install requests
```

---

## Usage

### 1) Connect to LRA Wireguard VPN
### 2) Connect to DLI to Power ON FlexRadio
### 3) Open up SmartSDR
### 4) Run the Script

a. **Open Command Prompt or PowerShell**
    - Press the `Win` key, type `cmd` or `PowerShell`, and press `Enter`.
b. **Navigate to the script directory**

For example, if you saved `flex-wedge.py` to your Desktop:

```powershell
cd Desktop
```

c. **Run the script**

```powershell
python flex-wedge.py
```

or

```powershell
py flex-wedge.py
```

*(Use `python` or `py` depending on your system configuration.)*
4. **Acknowledge the warning** by typing `YES` when prompted.
5. **SmartSDR should now be able to discover the LRA FlexRadio** as if it were on the local network.

### 5) Click on the FlexRadio in SmartSDR to Connect and Operate Remotely

---

## Security \& Legal Notice

> **WARNING: USE AT YOUR OWN RISK**
>
> This script is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and noninfringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the script or the use or other dealings in the script.
>
> By using this script, you acknowledge and agree that you understand this warning, and any use of the script is entirely at your own risk. Any damage caused by the deployment or use of this script is the sole responsibility of the user, and the authors or distributors of this script cannot be held liable for any adverse consequences arising therefrom.

---

## Support

For support, questions, or to request configuration access, please contact the LRA leadership team:

- Email: BOARD@KR9RK.COM
- Website: [kr9rk.com](https://www.kr9rk.com/)

---

## Contributing

Contributions are welcome from LRA members. Please open an issue or submit a pull request for review.

---

## License

This project is licensed under the terms of the GNU General Public License v3.0 (GPLv3). See the [LICENSE](LICENSE) file for details.

---

## About Lakeshore Repeater Association

The Lakeshore Repeater Association operates multiple ham radio repeater systems across Southeast Wisconsin and supports remote operations for its members. To learn more or to become a member, visit [kr9rk.com](https://www.kr9rk.com/).

---

*This project supports LRA’s mission to expand remote HF access for members. Please consider supporting our ongoing initiatives, including Project North Star.*

