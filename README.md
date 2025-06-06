# Task 3: Basic Vulnerability Scan using Nessus Essentials

## Objective
The objective of this task was to perform a basic vulnerability assessment on a personal Windows system using a free vulnerability scanner, specifically Nessus Essentials. The purpose was to identify potential vulnerabilities, misconfigurations, or outdated software that could lead to security risks.

## Tools Used
- "Nessus Essentials" (Tenable)
- "Operating System": Windows 10

## Steps Performed

1. "Installation"  
   Nessus Essentials was downloaded and installed from the official Tenable website. Registration was completed using a valid email to obtain a free activation code. The software was accessed via `https://localhost:8834`.

2. "Scan Configuration" 
   A basic network scan was configured by specifying the local machine’s IP address as the scan target. No credentials were provided (unauthenticated scan).

3. "Scan Execution" 
   The scan was launched and allowed to run until completion. This took approximately 30–45 minutes depending on system performance and scan depth.

4. "Results Review" 
   Upon completion, the results were reviewed in the Nessus dashboard. Vulnerabilities were categorized by severity levels: Critical, High, Medium, Low, and Informational.

5. "Export and Documentation" 
   A PDF report was exported from Nessus containing all identified issues, along with screenshots of the scan process and findings.

## Results Summary

| Severity      | Count |
|---------------|-------|
| Critical      | 1     |
| High          | 4     |
| Medium        | 7     |
| Low           | 5     |
| Informational | 12    |

## Learnings and Outcome
- Gained hands-on experience in performing a vulnerability scan using an industry-standard tool.
- Understood how vulnerabilities are detected and categorized.
- Learned how to interpret security reports and identify mitigation steps for high-risk findings.

## Files Included
- "Nessus_Vulnerability_Report.docx" – Detailed report of the scan.
- "screenshots/" – Folder containing screenshots from the Nessus scan.
- "README.md" – This file.

---

Note : All data was scanned on a personal local machine for educational purposes only.

