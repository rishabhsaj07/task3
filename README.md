 Task 3: Vulnerability Scanning Using Nessus Essentials

# Cybersecurity Internship

This task involved performing a *basic vulnerability scan* on my local machine using *Nessus Essentials* — a free, powerful vulnerability scanner developed by Tenable. The objective was to identify and document common vulnerabilities, understand their risks, and recommend possible mitigations.

---

# Tool Used

- Nessus Essentials
- OS: Linux 



# Target

- Target IP: 127.0.0.1 (Localhost)
- Scan Type: Basic Network Scan


# Scan Summary

| Severity     | Count |
|--------------|-------|
|  Critical    | 2     |
|  High        | 4     |
|  Medium      | 6     |
|  Low         | 3     |
|  Info Only   | 10+   |


# Most Critical Vulnerabilities Found

# 1.SMBv1 Enabled
- Severity: Critical
- CVSS Score: 10.0
- Description: SMBv1 is an outdated protocol vulnerable to several remote code execution attacks (e.g., EternalBlue).
- Fix: Disable SMBv1 via system settings or registry.

# 2.Outdated OpenSSH Server Detected
- Severity: Critical
- CVSS Score: 9.8
- Description: The system is running an outdated OpenSSH version known to have multiple vulnerabilities.
- Fix: Update OpenSSH to the latest stable version using your package manager.


All screenshots from the Nessus dashboard are included in the /screenshots/ folder.

- scan-summary.png – Overall scan result
- critical-vuln-1.png – SMBv1 vulnerability details
- critical-vuln-2.png – OpenSSH vulnerability details
- high-vuln-1.png – SSL Certificate issue
- medium-vuln-1.png – Unused open ports


# Key Concepts Learned

- Basics of vulnerability scanning and risk categorization
- Understanding CVSS (Common Vulnerability Scoring System)
- Difference between vulnerability scanning and penetration testing
- How tools like Nessus detect and classify vulnerabilities

#Special Thanks

Thanks for the hands-on opportunity to explore real-world tools and security practices.