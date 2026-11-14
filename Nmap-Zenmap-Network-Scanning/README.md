🔍 Network Scanning Using Nmap and Zenmap

📌 Project Overview

This project demonstrates basic network scanning and service detection using Nmap and Zenmap in a Kali Linux environment.

Network scanning is an important cybersecurity technique used to identify active hosts, examine network ports, and detect services running on a system.

In this practical project, Nmap was used through the Kali Linux terminal to perform service detection and port scanning. Zenmap was also used to perform scanning through a graphical user interface.

The scanning activities were performed against the localhost IP address ("127.0.0.1") in a controlled testing environment.

---

🎯 Project Objectives

The main objectives of this project are:

- To understand the fundamentals of network scanning.
- To verify Nmap installation and version.
- To perform basic port scanning.
- To understand service version detection.
- To explore open, closed, and filtered port states.
- To perform network scanning using Zenmap.
- To save scan results in a text file.
- To understand the importance of network scanning in cybersecurity.

---

🛠️ Tools and Technologies

Tool| Purpose
Kali Linux| Operating system for security testing
Nmap| Network scanning and service detection
Zenmap| Graphical interface for Nmap
Oracle VirtualBox| Virtual machine environment
Windows| File management and documentation

---

💻 Project Environment

- Operating System: Kali Linux
- Nmap Version: 7.99
- Target IP Address: 127.0.0.1
- Target: Localhost
- Scanning Tools: Nmap and Zenmap

---

⚙️ Practical Implementation

1. Nmap Version Verification

Command:

nmap --version

Purpose:

To verify that Nmap is installed and identify its version.

Result:

Nmap version 7.99 was successfully verified.

2. Network Interface Identification

Command:

ip -br addr

Purpose:

To display the available network interfaces and their IP addresses.

3. Service Version Detection

Command:

nmap -sV 127.0.0.1

Purpose:

To identify services and their versions on discovered open ports of the localhost system.

4. Fast Port Scanning

Command:

nmap -F 127.0.0.1

Purpose:

To perform a fast scan of commonly used TCP ports.

5. Saving Scan Results

Command:

nmap -sV 127.0.0.1 -oN /home/kali/Downloads/nmap_results.txt

Purpose:

To perform service version detection and save the scan output in normal text format.

The output file was successfully generated and transferred from Kali Linux to Windows using a VirtualBox shared folder.

6. Graphical Scanning Using Zenmap

Zenmap was opened in Kali Linux.

The target IP address was configured as:

"127.0.0.1"

The scan profile was selected and the scan was executed.

The Nmap Output tab displayed the scanning results.

A screenshot of the completed scan was captured for documentation.

---

📊 Results and Observations

The scanning activities were completed successfully.

The following observations were recorded:

- Nmap version 7.99 was verified.
- The localhost target was identified as active.
- Service detection scanning was completed.
- The scan output reported 1000 TCP ports as closed.
- No open TCP ports were reported in the saved scan output.
- Zenmap successfully displayed the scan results.
- The Nmap output was saved in a text file.
- Screenshots and result files were organized for project documentation.

Important Observation

A closed port indicates that the target system is reachable, but no application is listening on that port.

These results represent the scanning observations at the time of testing. They do not establish that the entire system is completely secure.

---

🔐 Cybersecurity Learning Outcomes

Through this project, I gained practical knowledge of:

- Basic network scanning techniques.
- Nmap command-line operations.
- TCP port scanning.
- Service version detection.
- Understanding port states.
- Using Zenmap for graphical scanning.
- Saving and organizing scan results.
- Documenting cybersecurity practical activities.

---

📝 Conclusion

This project provided practical experience in network scanning using Nmap and Zenmap in a Kali Linux environment.

The activities helped develop an understanding of network discovery, port scanning, service detection, and scan result analysis.

Nmap was used to execute scanning commands, while Zenmap provided a graphical interface to perform and examine the scan.

The localhost target ("127.0.0.1") was used for controlled testing. The scan reported that the host was active and the scanned 1000 TCP ports were closed.

The scan results were successfully saved, transferred, and organized for documentation.

Overall, this project improved my practical understanding of fundamental network scanning techniques and their importance in cybersecurity.

---

📚 References

- Nmap Official Website: https://nmap.org/
- Nmap Documentation: https://nmap.org/book/man.html
- Kali Linux Documentation: https://www.kali.org/docs/

---

Project: Week 2 – Project 5
Topic: Network Scanning Using Nmap and Zenmap
Status: Completed
