# 🛡️ CVE-2026-64638: Pre-Auth Reflected XSS on ProRx Pharma Staging

This repository contains the documentation and responsible disclosure timeline for a security vulnerability I discovered in the staging infrastructure of ProRx Pharma (managed by White Tiger Cyber).

## 📖 Case Summary
- **Target:** `stg-prorxpharmaorders-dev.kinsta.cloud` (ProRx Pharma Staging)
- **Vulnerability:** Pre-Authentication Reflected Cross-Site Scripting (XSS)
- **CVE ID:** CVE-2026-64638
- **Severity:** High
- **Status:** **Resolved & Patched** (WordPress updated to v7.0.3)

## 🤝 Responsible Disclosure Timeline
1. **Discovery:** Identified the staging subdomain via OSINT (Censys enumeration).
2. **Reporting:** Reached out directly to Mark Baldwin (CEO, White Tiger Cyber) with the PoC.
3. **Coordination:** Collaborated to verify asset ownership and provided clear reproduction steps.
4. **Remediation:** The client successfully patched the vulnerability and updated the WordPress core.
5. **Recognition:** Received an official Letter of Appreciation for the ethical disclosure.

## 📄 Letter of Appreciation
As a testament to the collaborative nature of this disclosure, White Tiger Cyber issued a formal letter of recognition.

[📥 Download/View the Letter of Appreciation (PDF)](./assets/letter_of_appreciation.pdf)

## 📝 Technical Write-up
For a detailed breakdown of the vulnerability (sanitized for public viewing), please read the full write-up here:
👉 **[Read the CVE-2026-64638 Write-up](./reports/CVE-2026-64638.md)**

---
**Researcher Contact:**
- **Name:** Aditia Saputra
- **Email:** adityaodoy12t@gmail.com
