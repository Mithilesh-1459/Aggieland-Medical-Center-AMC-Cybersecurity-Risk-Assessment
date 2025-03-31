# Aggieland Medical Center (AMC) Cybersecurity Risk Assessment

This README summarizes the goals, analysis, and key findings from the **Qualitative Cybersecurity Risk Assessment** conducted for Aggieland Medical Center (AMC). This project was completed as part of ISTM 635: Business Information Security at Texas A&M University.

---

## 🧠 Business Case

Healthcare institutions are frequent targets of cyberattacks due to the high value of protected health information (PHI) and sensitive data. The Aggieland Medical Center (AMC), a healthcare provider with a wide range of digital systems handling patient data, scheduling, billing, and treatment, faces numerous vulnerabilities and threats across its IT infrastructure.

This project aimed to systematically evaluate the cybersecurity risks AMC faces, prioritize those risks, and recommend mitigation strategies based on NIST SP 800-30 Rev. 1 guidance.

---

## 🎯 Project Objective

To assess the cybersecurity posture of AMC and:
- Identify critical business processes and corresponding IT assets
- Detect system vulnerabilities from technical, administrative, and physical standpoints
- Recognize threat agents and threat events tied to those vulnerabilities
- Estimate the likelihood and impact of each threat event
- Calculate overall cybersecurity risk levels for prioritization

---

## 📊 Success Metrics

- ✅ Identification of all mission-critical IT assets supporting scheduling, treatment, and billing
- ✅ Comprehensive mapping of vulnerabilities to real-world threats
- ✅ Quantitative and qualitative estimation of threat event likelihood and impact
- ✅ Final prioritization of threat events based on calculated risk scores (FIVs)
- ✅ Actionable recommendations aligned with HIPAA compliance and cybersecurity best practices

---

## 🔍 Key Methodology & Frameworks Used

- **NIST SP 800-30 Rev. 1** – Guide for Conducting Risk Assessments
- **CVSS v3.1** – Exploitability Scoring System
- **HIPAA** – Regulatory guidance for protecting electronic health information
- **Threat Likelihood & Risk Matrices** – Tables B–E provided consistent and structured measurement

---

## 🏥 Business Processes and Associated IT Assets

1. **Appointment Scheduling (AS)**
   - Patient Data Information Server (PDIS)
   - Financial Record Keeping Server (FRKS)
   - Email Server (ES)

2. **Patient Treatment and Monitoring (PTM)**
   - Emergency Care Data System (ECDS)
   - Pharmacy System (RxS)
   - Email Server (ES)

3. **Patient Billing (PB)**
   - Financial Record Keeping Server (FRKS)
   - Pharmacy System (RxS)
   - Email Server (ES)

---

## ⚠️ Major Findings

- **Three Threat Events Were Ranked as Very High Risk:**
  - PDIS V1 T1 – Remote Code Execution via Remote Desktop Client
  - PDIS V2 T2 – Exploitable RPC Vulnerability on Windows 10
  - RxS V22 T22 – SQL Server Elevation of Privilege

- **Three Additional Threat Events Ranked as High Risk:**
  - ECDS V12 T12 – Unmonitored Workstations
  - ECDS V19 T19 – Outdated Vulnerability Management Policies
  - RxS V19 T19 – Same as above, impacting pharmaceutical data

- **Primary Risk Drivers:**
  - Legacy systems (e.g., outdated Sendmail and Windows 7)
  - Inadequate employee training and awareness
  - Weak physical controls and room security
  - Lacking encryption for email communication

---

## 📌 Risk Assessment Highlights

- Each threat was evaluated on: motivation, capability, exploitability, and potential damage
- Impact on Confidentiality, Integrity, and Availability (CIA triad) was calculated
- Business disruption, financial cost, and HIPAA legal penalties were factored into the Final Impact Value (FIV)
- Final cybersecurity risk was scored using the NIST-based matrix (Very Low to Very High)

---

## 🛡️ Recommendations Summary

- Immediately patch vulnerabilities ranked Very High (e.g., SQL server exploits, RDP/RPC flaws)
- Enforce physical workstation security and access controls
- Encrypt all sensitive email communications
- Launch continuous training programs on HIPAA, password security, and phishing
- Implement formal, recurring vulnerability assessments

---

## 📁 Deliverables

- 📄 **Final Report (PDF):** Includes tables of vulnerabilities, threat IDs, impact scoring, and prioritized risks
- 🖥️ **Methodology:** Structured using NIST frameworks, CVSS scoring, and HIPAA legal scales
- 🛠️ **Threat Matrix Tables:** Helped stakeholders clearly understand technical, organizational, and regulatory risk levels

---

## ✅ Project Outcome

This risk assessment provided AMC with a clear view of its cyber vulnerabilities and risk priorities. The organization can now proceed with informed decisions about resource allocation, mitigation actions, and regulatory compliance, significantly strengthening its overall security posture.

---

> For details, see the full report attached in this repository.

