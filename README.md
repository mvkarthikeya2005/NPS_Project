
# Zphisher Phishing Toolkit

![Screenshot 2024-09-06 190452](https://github.com/user-attachments/assets/ed51f7cc-69d3-44ad-ab3d-15716352a192)

## Overview

Zphisher is a powerful phishing tool designed for educational purposes and ethical hacking. This project showcases how Zphisher can be used to create phishing pages to demonstrate vulnerabilities in web security. This repository contains the setup and usage instructions for running Zphisher on Kali Linux.

**Important:** This project is intended for educational and ethical use only. Unauthorized use of phishing tools is illegal and unethical. Always obtain explicit permission before testing any systems or networks.

*This project is based on the original Zphisher tool by [htr-tech](https://github.com/htr-tech/zphisher) and serves as an educational demonstration of phishing techniques for cybersecurity awareness.*

## Prerequisites

Before you begin, ensure you have the following:

- Kali Linux installed on your machine
- Basic knowledge of Linux commands and terminal usage
- Understanding of phishing and ethical hacking principles
- Git installed on your system

## Installation

1. **Clone this Repository:**
   ```bash
   git clone https://github.com/mvkarthikeya2005/zphisher-project.git
   cd zphisher-project
   ```

2. **Update your system:**
   ```bash
   sudo apt update
   sudo apt full-upgrade -y
   ```

3. **Install Dependencies:**
   ```bash
   sudo apt-get install -y git curl php
   ```

4. **Set Up Zphisher:**
   
   Clone the original Zphisher repository:
   ```bash
   git clone --depth=1 https://github.com/htr-tech/zphisher.git
   cd zphisher
   ```

5. **Run Zphisher:**
   ```bash
   bash zphisher.sh
   ```

   On first launch, it will install the dependencies automatically and Zphisher will be ready to use.

## Usage

1. **Navigate to Zphisher directory:**
   ```bash
   cd zphisher
   ```

2. **Start Zphisher:**
   ```bash
   bash zphisher.sh
   ```

3. **Select Phishing Template:**
   Follow the on-screen prompts to select a phishing template and configure your attack.

4. **Deploy Phishing Page:**
   After configuration, Zphisher will guide you through deploying the phishing page. Ensure you have the proper permissions to use the phishing page in your testing environment.

## Ethical Considerations

- **Use Responsibly:** Only use this tool in environments where you have explicit permission to test and evaluate security.
- **Legal Compliance:** Be aware of and comply with all local, national, and international laws regarding cybersecurity and phishing.
- **Educational Purpose:** This project is intended for educational and ethical hacking purposes only.

## Contributing

If you have suggestions, improvements, or fixes, feel free to contribute to this project by creating a pull request or opening an issue.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

- [Zphisher GitHub Repository](https://github.com/htr-tech/zphisher) - Original tool by htr-tech
- [Kali Linux Documentation](https://www.kali.org/docs/) - Official Kali Linux documentation
