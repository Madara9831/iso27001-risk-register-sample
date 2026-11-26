# Sample Information Security Risk Register (SME Scenario)

A basic, educational **ISO/IEC 27001-style Risk Register** created for learning and portfolio demonstration purposes based on a hypothetical small e-commerce/SME business in Sri Lanka.

## Risk Scoring Scale (1–5)
- **Likelihood (L):** 1 (Rare) to 5 (Almost Certain)
- **Impact (I):** 1 (Negligible) to 5 (Severe)
- **Risk Score:** `Likelihood × Impact` (1–6: Low | 8–12: Medium | 15–25: High)

## Risk Register Table

| Risk ID | Asset | Threat & Vulnerability | Existing Controls | L | I | Score | Risk Level | Treatment Plan & Target Control |
| :--- | :--- | :--- | :--- | :---: | :---: | :---: | :---: | :--- |
| R-01 | Customer Order Database / Spreadsheet | Unauthorized access due to weak passwords or shared accounts | Basic password protection | 3 | 4 | **12** | Medium | Enforce MFA, unique accounts, and role-based access (ISO 27001 Annex A.5.15 / A.5.17) |
| R-02 | Employee Laptops | Data loss or exposure from lost/stolen devices or malware | Antivirus on some devices | 3 | 4 | **12** | Medium | Enable full-disk encryption (BitLocker/FileVault) and screen auto-lock (A.7.8 / A.8.1) |
| R-03 | Business Email & Cloud Drive | Phishing attack leading to credential theft or data leak | Basic spam filter | 4 | 4 | **16** | High | Enable phishing-resistant MFA, email security rules, and staff awareness training (A.6.3) |
| R-04 | Accounting & Order Records | Accidental deletion or ransomware with no recovery copy | Manual occasional backups | 2 | 5 | **10** | Medium | Schedule automated daily backups and test restoration periodically (A.8.13) |
| R-05 | Third-Party Delivery / Marketing Vendor | Customer contact data mishandled by external vendor | Verbal instructions only | 3 | 3 | **9** | Medium | Sign Data Processing Agreement (DPA) / security terms and review vendor access (A.5.19–A.5.21) |

---

*Note: Created as a student learning exercise for Governance, Risk & Compliance (GRC) studies.*
