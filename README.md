🛡 CertLens Certificate Trust Diagnostics for Enterprises CertLens is an on-prem certificate analysis tool that visually explains why a certificate or keystore fails — not just that it fails. It is built for banks, fintechs, messaging teams, and PKI engineers working with TLS, SWIFT, and secure integrations.

🚨 The Problem Certificate failures are usually caused by: Missing intermediate certificates Wrong trust chains Expired or mis-signed certificates But existing tools (openssl, keytool) show raw data that is hard to interpret.

💡 What CertLens Does Upload a certificate or keystore and CertLens will: Auto-build the trust chain Verify parent/child signatures Detect missing or wrong CAs Assess expiry risk Explain issues in plain English Generate audit-ready PDF reports

🔐 Security First Runs locally or on-prem No data leaves your network Ideal for regulated environments

🏗 Supported Inputs Format Supported .crt / .pem ✅ .jks (Java keystore) ✅ .p12 / .pfx 🔜 🐳 Run with Docker (Recommended) docker run -p 8080:8080 certlens

Then open: http://localhost:8080

🧪 Local Run (Developer) python -m venv venv venv\Scripts\activate pip install -r requirements.txt python app.py

📄 Features Visual trust chain (Leaf → Intermediate → Root) Missing / wrong CA detection Expiry risk scoring Human-readable explanations PDF reports for audits On-prem & Docker ready

🎯 Who It’s For

Banks & Fintechs SWIFT / Messaging integrators PKI & Security teams Compliance & Audit teams Training institutes

📬 Contact

Built by Nav For demos, training, or enterprise licensing — reach out.
