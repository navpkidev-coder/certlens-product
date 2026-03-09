# 🛡 CertLens
### Certificate Trust Diagnostics for Enterprises

CertLens is a **certificate intelligence and diagnostics tool** that visually explains **why a certificate or keystore fails — not just that it fails**.

It is designed for teams working with **TLS, PKI, and secure integrations**, particularly in **banking, fintech, and enterprise messaging environments**.

---

# 🚨 The Problem

Certificate outages often happen because of:

- Missing intermediate certificates
- Incorrect trust chains
- Expired certificates
- Mis-signed certificates
- Incomplete keystore configurations

Existing tools such as:

- OpenSSL
- keytool
- Browser TLS errors

provide **raw cryptographic output**, but they rarely explain the **actual root cause of the failure**.

---

# 💡 The CertLens Approach

CertLens reconstructs the **entire trust chain** and provides a **clear visual explanation** of what is happening.

It helps answer questions like:

- Which certificate is missing?
- Which CA should be the parent?
- Does the signature chain match?
- Is the certificate about to expire?
- Is the trust path valid?

All results are displayed in a **human-readable visual format**.

---

# 🔐 Security First

CertLens is designed for **high-security environments**.

It runs completely inside your infrastructure:

- On-prem deployment
- Docker container support
- Offline operation supported

**No certificates or private keys leave your network.**

---

# 🧱 Core Capabilities

- PEM / CRT / DER certificate support
- JKS and PKCS#12 keystore analysis
- Automatic trust chain reconstruction
- Detection of missing or incorrect intermediate CAs
- Certificate expiry risk detection
- Visual certificate chain representation
- Certificate inventory overview
- Audit-ready PDF reports

---

# 📸 Screenshots

### CertLens Overview

<img width="3840" height="3930" alt="certlens-home" src="https://github.com/user-attachments/assets/0f7462ec-669a-48c0-a826-cdb4dff2eadd" />

---

### Certificate Validation

<img width="982" height="898" alt="certlens-validate-upload" src="https://github.com/user-attachments/assets/db5fa1e3-a38e-40e0-be0c-37e7bec45adb" />

---

### TLS Endpoint Analysis

<img width="3840" height="3448" alt="certlens-tls-scan-results" src="https://github.com/user-attachments/assets/3e604a84-22da-460e-b147-d13b74cc8288" />


---

### Certificate Chain Visualization

<img width="3840" height="4428" alt="certlens-chain-analysis" src="https://github.com/user-attachments/assets/50e33295-1f55-4eef-a392-bea4cd4fa810" />


---

### Risk Detection

<img width="3840" height="3488" alt="certlens-risk-detection" src="https://github.com/user-attachments/assets/933f2379-0416-4d09-b35d-29bba19d436d" />


---

# 🎯 Who Uses CertLens

CertLens is built for teams working with **secure communications infrastructure**:

- Banks and Fintech platforms
- SWIFT and financial messaging integrators
- PKI and security engineering teams
- Compliance and audit teams
- Training institutes teaching TLS / PKI

---

# 📦 Deployment

CertLens can be deployed as:

- On-prem application
- Docker container

Due to the **sensitive nature of certificate environments**, the source code is not publicly distributed.

Enterprise deployment packages are available upon request.

---

# 📬 Request a Demo

For demos, training sessions, or enterprise licensing:

📧 **contact.navsatech@gmail.com**

---

# 🏷 Topics

`pki` `tls` `certificates` `security` `banking` `docker` `cryptography`
