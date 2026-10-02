🛡️ Mediroza General Hospital — Black-Box Penetration Testing

📋 Project Overview

The project focuses on an authorized black-box penetration test and vulnerability assessment of the Mediroza General Hospital web application. The objective is to investigate potential security weaknesses, assess access controls, analyze protected PDF documents, investigate sensitive information exposure, and prepare a professional penetration testing report.

🎯 Assessment Details




| Parameter | Details |
|---|---|
| Client | Mediroza General Hospital |
| Target | https://medirozahospital.com |
| Assessment Type | Black-Box Penetration Test |
| Program | NetworkWalks Cybersecurity Program |
| Batch | B083 |
| Duration | 5 Days |
| Testing Scope | Authorized target domain only |
| Authorization | Written authorization stated in the project brief |



🎯 Project Objectives

The project consists of four major milestones.

M1 — Initial Access

Directory: "M1-INITIAL-ACCESS/"

The first milestone focuses on identifying exposed entry points and examining the web application's authentication and access-control mechanisms.

Tasks:

- Conduct reconnaissance on the target.
- Identify exposed application entry points.
- Analyze authentication mechanisms.
- Examine application input handling.
- Investigate access controls in the authorized environment.
- Document evidence relating to the three patient laboratory PDF reports specified in the assignment.

Deliverable: Evidence of access and the three PDF files within the authorized lab exercise.

M2 — Data Extraction and PDF Security Analysis

Directory: "M2-DATA-EXTRACTION/"

The second milestone focuses on analyzing the protection mechanisms applied to the three retrieved PDF documents.

Tasks:

- Identify the encryption mechanisms used by each PDF.
- Analyze document protection.
- Select suitable offline analysis tools and wordlists.
- Evaluate appropriate recovery methods.
- Validate recovered document contents.
- Record the process and supporting evidence.

Deliverable: Evidence of successful document access and recovery within the authorized exercise.

M3 — Critical Data Exposure

Directory: "M3-CRITICAL-DATA-EXPOSURE/"

The third milestone investigates further exposure that may be revealed by analyzing the retrieved files and related information.

Tasks:

- Examine document properties and metadata.
- Investigate references to additional server resources.
- Analyze potential directory and legacy-resource exposure.
- Investigate the specified employee salary information.
- Investigate the specified hospital shareholder information.
- Document the exposure chain and potential business impact.

Deliverable: Documented evidence and a readable summary of the identified exposure, with sensitive information protected.

M4 — Professional Penetration Testing Report

Directory: "M4-PENTEST-REPORT/"

The final milestone brings the assessment together in a structured technical report.

The report includes:

1. Executive Summary
2. Scope and Methodology
3. Findings and Proof of Exploitation
4. Risk Ratings and Justification
5. Recommendations and Remediation

Deliverable: A professional penetration testing report submitted to the instructor.

🧭 Methodology

The project follows a structured penetration testing workflow:

1. Reconnaissance and Footprinting
2. Application Mapping
3. Authentication and Access-Control Analysis
4. Initial Access Assessment
5. Document Retrieval and Analysis
6. PDF Encryption Analysis
7. Metadata and Resource Investigation
8. Sensitive Information Exposure Assessment
9. Risk Assessment
10. Reporting and Remediation

🛠️ Tools and Technologies


## Tools Used

| Tool | Purpose |
|---|---|
| Kali Linux | Security testing environment |
| Burp Suite | HTTP traffic inspection and request analysis |
| cURL | HTTP reconnaissance |
| Web Browser | Manual application exploration |
| `file` | File-type identification |
| `pdfinfo` | PDF document inspection |
| ExifTool | Metadata analysis |
| QPDF | PDF structure and encryption analysis |
| Git and GitHub | Version control and documentation |


Tools are selected according to the task and the authorized scope of the assessment.

📊 Findings and Risk Assessment

The following areas represent the assessment objectives. Confirmed findings and severity ratings should be added only after validating the technical evidence.


## Areas of Investigation

| ID | Area of Investigation | Category |
|---|---|---|
| MED-01 | Authentication and access controls | Authentication / Authorization |
| MED-02 | Protection of patient PDF documents | Data Protection / Cryptography |
| MED-03 | Potential sensitive information disclosure | Information Disclosure |
| MED-04 | Potentially exposed directories or legacy resources | Security Misconfiguration |
| MED-05 | Potential exposure of organizational information | Sensitive Data Exposure |


Each confirmed finding should include:

- Finding title and description
- Affected component
- Evidence and reproduction steps
- Potential impact
- Risk rating and justification
- Recommended remediation

📸 Evidence and Documentation

Evidence is organized according to the four project milestones.

- M1: Initial access and application assessment
- M2: PDF security analysis and recovery evidence
- M3: Metadata investigation and exposure evidence
- M4: Final report and remediation recommendations

Screenshots and supporting evidence should be clearly labelled. Patient records, credentials, employee salaries, shareholder details, and other confidential information must be redacted before public publication.

🔐 Authorization and Rules of Engagement

This project follows the scope and rules described in the NetworkWalks Week 4 project brief.

Testing is restricted to the authorized target domain. Denial-of-service testing, social engineering, and testing outside the agreed scope are excluded.

All activities must remain within the written authorization and the project's rules of engagement.

⚠️ Responsible Use

This repository is intended for educational and authorized security-testing purposes. Do not perform penetration testing against any system without explicit permission from its owner.
