# CYBER SECURITY INTERNSHIP - Task 3: Basic Vulnerability Scan

**Objective:** Use a free tool to identify common vulnerabilities on a personal computer (Host PC) and document the findings, focusing on critical issues and remediation steps.

**Tool Used:** Nessus Essentials (Tenable)

**Target:** Local Host PC (IP: 10.22.172.159)

## Process Summary

1.  **Tool Selection:** Due to network issues with the OpenVAS VM, the approved alternative tool, Nessus Essentials, was installed directly on the host machine.
2.  **Scan Configuration:** A **Basic Network Scan** was created targeting the local host IP (10.22.172.159).
3.  **Execution & Analysis:** The scan ran for **18 minutes** and was successful. The scan returned **4 Medium** severity findings and **37 Informational** findings, with **no Critical or High** vulnerabilities detected.
4.  **Key Findings:** The primary concerns identified were related to **SSL Certificate misconfigurations** and a lack of required **SMB Signing**, which could expose the system to Man-in-the-Middle (MITM) attacks if accessed remotely.
5.  **Deliverables:** The final report and screenshots are provided as proof of execution and analysis.

## Deliverables in this Repository

| File Name | Description |
| :--- | :--- |
| `Vulnerability_Scan_Report.docx` | Formal report detailing the 4 Medium findings, CVSS scores, and mitigation steps. |
| `Screenshot_Scan_Configuration.jpg` | Proof of the scan setup (Scan Name, Target IP). |
| `Screenshot_Critical_Results.png` | Proof of the scan's outcome (Vulnerability Severity Breakdown and Scan Details). |
