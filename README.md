# EcoVeriSight: AI-Based Environmental Compliance & Permit Screening System
**Environmental Hacks Hackathon (WeMakeDevs & AWS)**  
**Team Name:** The NEXORA  

---

## 📌 Overview
**EcoVeriSight** is an AI-powered automated document and compliance screening platform adapted for environmental governance. It verifies industrial environmental clearance certificates, waste disposal manifests, and carbon emission logs to detect fraud, forged permits, and regulatory non-compliance in real-time.

---

## 🚀 Key Features
- **AI Tamper Detection:** Utilizes Error Level Analysis (ELA) to catch digital edits, spliced text, and forged stamps on environmental permits and clearance certificates.
- **Smart Manifest Cross-Check:** Validates document text and checksum math against environmental safety standards to spot altered data.
- **1:1 Inspector & Facility Verification:** Secures check-ins and compliance audits using biometric and facial validation to block unauthorized filings.
- **Tamper-Proof Ledger:** Records all industrial compliance decisions and clearances using SHA-256 chained blocks ensuring logs cannot be altered.
- **Automated Risk Triage:** Generates a 0-100 environmental risk score; auto-clears compliant facilities and flags suspicious logs for regulatory review.

---

## 🛠️ Tech Stack & AWS/Cloud Architecture
- **Frontend:** React 18, TypeScript, Vite
- **AI & Vision:** OpenCV, PyTorch, Tesseract OCR, ELA (Error Level Analysis)
- **Backend & Database:** FastAPI, PostgreSQL / Supabase
- **Security & Audit:** SHA-256 Chained Ledger
- **Cloud Infrastructure:** Integrated with AWS S3 for secure document storage and AWS Lambda/Textract for scalable processing workflows.

---

## 📊 Impact & Performance
- **Speed:** Sub-15 seconds clearance and document audit latency.
- **Efficiency:** Drastically reduces manual backlog for environmental regulatory boards.
- **Compliance:** Air-gapped secure auditing backed by a 256-bit cryptographic audit trail.
