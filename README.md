# PRODIGY_CS_05_Packet_Sniffer

## Overview

The `PRODIGY_CS_05_packet_sniffer` is a Python-based tool designed to capture and analyze network packets. It provides detailed insights into network traffic by displaying key information such as source and destination IP addresses, protocols used, and payload data. This tool is intended for educational purposes, offering a hands-on approach to understanding network traffic and packet analysis.

## Features

- **Packet Capture**: Captures network packets using the Scapy library.
- **IP Address Display**: Shows the source and destination IP addresses of captured packets.
- **Protocol Identification**: Identifies and displays the protocol used (e.g., TCP, UDP, ICMP).
- **Payload Preview**: Provides a preview of the payload data contained within the packets.

## Prerequisites

- **Python**: Python 3.x is required.
- **Scapy**: The Scapy library must be installed.
- **Npcap or WinPcap**: Required for Windows users to capture network packets.

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/pksooraj/PRODIGY_CS_05_packet_sniffer.git
    ```

2. **Navigate to the Project Directory**:
    ```bash
    cd PRODIGY_CS_05_packet_sniffer
    ```

3. **Install Required Python Packages**:
    Install the Scapy library using pip:
    ```bash
    pip install scapy
    ```

4. **Install Npcap (Windows Users Only)**:
    Download and install Npcap from [Npcap's official site](https://nmap.org/npcap/). During installation, select:
    - "Install Npcap in WinPcap API-compatible Mode"
    - "Install for all users (requires a reboot)"

## Usage

1. **Open a Terminal**:
    - **Windows**: You may need to run the terminal as Administrator.
    - **Linux/Mac**: Use `sudo` to ensure sufficient privileges.

2. **Run the Packet Sniffer**:
    ```bash
    python packet_sniffer.py
    ```

3. **View Output**:
    The script will display captured packets, including:
    - Source and destination IP addresses
    - Protocols used
    - A snippet of the payload data

## Troubleshooting

- **Npcap Issues**: Ensure Npcap is installed correctly and running. Refer to the [Npcap troubleshooting guide](https://nmap.org/npcap/guide/npcap-troubleshooting.html) for assistance.
- **Permissions**: Run the script with administrative privileges if you encounter permission errors.
- **Service Status**: Verify that the Npcap service is running using the Services application (`services.msc` on Windows).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
