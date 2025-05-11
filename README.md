# Automated Network Reconnaissance using Nmap and Bash

A simple, beginner-friendly tool for automating network scanning tasks using Nmap and Bash scripting on Linux.

## Project Overview

This project helps beginners understand how cybersecurity professionals gather information about computer networks, identify potential vulnerabilities, and create a basic automated tool.

## Objectives

- Understand basic Nmap usage for scanning networks
- Learn to write Bash scripts to automate common scanning operations
- Develop a beginner-friendly tool that:
  - Accepts a target IP range or domain
  - Performs basic scans (ping, port, OS detection)
  - Saves output in organized files

## Tools & Technologies Used

- **Nmap**: For network and vulnerability scanning
- **Bash (Linux Shell Scripting)**: To automate the tasks
- **GitHub**: For version control and public project hosting

## Project Structure
nmap-bash-scanner/
├── README.md
├── scan.bat
├── results/
│   └── [targetname]_scan.txt
└── LICENSE

## Installation

1. Ensure you have Nmap installed on your system:
   - For Windows: Download and install from https://nmap.org/download.html
   - For Linux: `sudo apt install nmap`

2. Download or clone this repository

## Usage

1. Run the script:
   - On Windows: Double-click scan.bat or run it from Command Prompt
   - On Linux: `./scan.sh`

2. Enter the target IP or domain when prompted.

3. The script will perform the following scans:
   - Ping scan to check if the host is up
   - Port scan to find open ports
   - OS detection and service version detection

4. Results will be saved in a text file inside the `results/` folder.

## Warnings and Ethical Considerations

- **Always obtain permission before scanning any network or system you don't own.**
- **Unauthorized scanning may be illegal in many jurisdictions.**
- This tool is intended for educational purposes and legitimate network administration tasks only.

## Project Milestones

- [x] Setup Nmap and Bash environment
- [x] Write the core script
- [x] Test on multiple IPs/domains
- [x] Create documentation with README

## License

This project is licensed under the MIT License - see the LICENSE file for details.
