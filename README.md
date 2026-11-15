# 🛡️ Cloud IAM Security Policy

This project demonstrates **Least-Privilege Access Control** using a real-world JSON Identity and Access Management (IAM) policy to protect sensitive cloud storage.

## 🔐 Key Security Controls
* **Read-Only Public Reports:** Allows junior analysts to view public files without editing rights.
* **Delete & Exposure Protection:** Explicitly blocks file deletions and prevents private storage buckets from being made public.
* **MFA Enforcement:** Blocks all access to the `company-confidential-vault` unless Multi-Factor Authentication (MFA) is active.
