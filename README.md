# Nikto Web Server Scanning Project

## Objective
The Nikto Web Server Scanning project was designed to understand and implement web application security assessments using the Nikto tool. The primary goal was to scan a vulnerable web server to identify potential vulnerabilities and generate a comprehensive penetration testing report. This project enhanced my ability to conduct security assessments, analyze scan results, and document findings effectively.

### Skills Learned
- In-depth understanding of web server vulnerabilities and scanning techniques.
- Proficiency in using Nikto for web application security assessments.
- Ability to analyze and interpret scan results to identify security risks.
- Enhanced skills in creating detailed penetration testing reports.
- Familiarity with network configuration and virtual environments for testing.

### Tools Used
- **Nikto**: A web server scanner that performs comprehensive tests against web servers for multiple items, including dangerous files/programs and version-specific problems.
- **Kali Linux**: An open-source Linux distribution used for penetration testing and security auditing.
- **Nmap**: A network scanning tool used to discover hosts and services on a computer network.

## Steps

### 1. Vulnerable Web Server Installation
Before using Nikto, I set up a vulnerable web server by downloading a vulnerable virtual machine from [VulnHub](https://www.vulnhub.com/entry/colddbox-easy,586/). The VM was imported into VirtualBox, and the network settings were configured to ensure proper connectivity.

### 2. Network Configuration
I installed and configured Kali Linux in my VirtualBox environment, ensuring that the network settings were appropriately set for lab use. I documented the IP address of my Kali Linux host for reference during scans.

### 3. Nmap Scans
I switched to the root user on my Kali Linux machine to perform network scans using Nmap. The following tasks were completed:
- Conducted a scan of the LAB network to identify all active IP addresses.
- Narrowed down the possible web server IP addresses through various Nmap commands to identify running services.

### 4. Nikto Scanning
Using the identified web server IP address, I executed multiple Nikto commands to scan for vulnerabilities. Each command output was saved to a file for documentation in my penetration testing report. Commands included:
- `nikto -h `: Basic scan of the host.
- `nikto -h  -output `: Scan with results outputted to a specified file.

### 5. Generating the Report
I compiled my findings into a structured report, including:
- **Test Overview**: Objectives of the test.
- **Testing Plan**: Details of my setup (OS, IP, tools).
- **Test Results**: Documenting findings for each scan.
- **Test Summary**: Overall findings and recommendations.

## Conclusion
This project provided practical experience with tools like Nmap and Nikto for conducting security assessments. I learned how to combine multiple tools effectively during penetration testing phases and improved my ability to document findings in a professional manner. This knowledge will be invaluable in pursuing a career in cybersecurity.
