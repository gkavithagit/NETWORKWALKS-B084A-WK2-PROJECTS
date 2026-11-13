🔍 Footprinting Using theHarvester

📌 Project Overview

This project is part of Week 2 – Project Module 4 (W2-PM4) of my cybersecurity internship.

The project focuses on understanding and performing basic footprinting using theHarvester, an open-source OSINT tool available in Kali Linux.

theHarvester helps security professionals gather publicly available information about domains, including email addresses, subdomains, hostnames, and other related information from supported data sources.

🎯 Objectives

- Understand the fundamentals of footprinting.
- Explore the features of theHarvester.
- Learn basic theHarvester commands.
- Perform a basic domain footprinting demonstration.
- Generate JSON and XML output reports.
- Analyse the collected information.

🛠️ Tools & Technologies

Tool| Purpose
Kali Linux| Operating system
theHarvester| OSINT and footprinting
Terminal| Command execution
JSON| Structured report output
XML| Structured report output

⚙️ Practical Implementation

1. Verify theHarvester

theHarvester -h

Displays the help menu and available options.

2. Basic Footprinting

theHarvester -d example.com -b crtsh

Performs a basic demonstration using "example.com" and the "crtsh" data source.

3. Generate Reports

theHarvester -d example.com -b crtsh -f footprinting_report

Generates the following output files:

- "footprinting_report.json"
- "footprinting_report.xml"

📊 Results & Analysis

- Successfully verified theHarvester in Kali Linux.
- Explored the available command-line options.
- Executed a basic footprinting demonstration.
- Generated JSON and XML report files.
- The demonstration returned empty host and Shodan result arrays.

Note: "example.com" is a reserved example domain. This practical exercise demonstrates basic tool usage and report generation, not a successful real-world information-gathering assessment.

📚 Learning Outcomes

Through this project, I gained practical knowledge of:

- Footprinting fundamentals.
- Open-source intelligence (OSINT).
- Using theHarvester in Kali Linux.
- Command-line tool execution.
- JSON and XML report generation.
- Analysing footprinting output.

⚠️ Disclaimer

This project is intended for educational purposes only. Footprinting and information gathering should only be performed on domains and systems that you own or have explicit permission to assess.

👨‍💻 Author

KAVITHA G

Cybersecurity Student | Cybersecurity Intern

---

⭐ This project represents my hands-on learning experience in cybersecurity and OSINT.
