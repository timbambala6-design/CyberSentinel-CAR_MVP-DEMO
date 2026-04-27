# CyberSentinel-CAR_MVP-DEMO
Prototype de la CyberSentinel en République Centrafricaine pour Orange
# 🛡️ CyberSentinel CAR

> **AI-Powered Mobile Money Fraud Protection for Central Africa**
> *Born in Africa. Built for the World.*

[![OSVP 2026](https://img.shields.io/badge/Orange%20OSVP-2026%20Applicant-E84000?style=for-the-badge)](https://poesam.orange.com)
[![Country](https://img.shields.io/badge/Country-Central%20African%20Republic-003082?style=for-the-badge)](https://en.wikipedia.org/wiki/Central_African_Republic)
[![Organization](https://img.shields.io/badge/By-ONE%20YOUNG%20LEGACY-1A1A2E?style=for-the-badge)](https://github.com)
[![License](https://img.shields.io/badge/License-MIT-00C896?style=for-the-badge)](LICENSE)

---

## 🌍 What is CyberSentinel CAR?

CyberSentinel CAR is an AI-powered cybersecurity and digital fraud prevention platform built for mobile money users across Central Africa. It protects the most vulnerable users of Orange Money — women traders, youth entrepreneurs, and rural communities — who have no tools to recognize or report digital fraud.

In the Central African Republic and across francophone Sub-Saharan Africa, mobile money is the primary financial infrastructure for millions of people. Yet every day, these users lose their savings to SIM-swap attacks, phishing SMS, fake agent scams, and social engineering — with zero protection and zero recourse.

**CyberSentinel CAR changes that.**

---

## 🚨 The Problem

| Fraud Type | Description | Impact |
|---|---|---|
| Phishing SMS | Fake Orange Money messages stealing PINs | Most common — daily incidents in Bangui |
| SIM-Swap | Duplicate SIM cards emptying mobile wallets | Victims lose entire savings in minutes |
| Fake Agents | Fraudsters posing as Orange agents in markets | Targets women traders specifically |
| Advance Fee | Fake government aid requiring upfront payment | Targets vulnerable and rural populations |
| QR Code fraud | Fraudulent QR codes redirecting payments | Growing rapidly in urban markets |

Women market traders in Bangui are the most frequently targeted victims. They represent 60%+ of Orange Money daily users in the informal economy — and have zero access to fraud protection tools in their own languages.

---

## ✅ Our Solution — 3 Layers of Protection

### Layer 1 — 🤖 AI Fraud Alert System
A lightweight NLP model trained on 5,000+ documented fraud SMS patterns from francophone Africa. When a user forwards a suspicious message, the system returns a risk score (0–100) and a detailed alert in **French and Sango** within 15 seconds.

### Layer 2 — 📚 Daily Micro-Learning (WhatsApp + USSD)
2-minute daily digital security lessons delivered via WhatsApp and USSD (no smartphone required). Content in Sango, French, and Lingala. Designed around everyday market scenarios familiar to users in Bangui.

### Layer 3 — 📊 Community Fraud Reporting Database
Simple fraud reporting via WhatsApp and USSD. Reports are aggregated into a monthly threat intelligence bulletin — the **first community-powered cybersecurity database of Central African mobile fraud** — shared with Orange Centrafrique, financial regulators (COBAC), and humanitarian partners.

---

## 🖥️ MVP Demo

The interactive MVP prototype is available in this repository as a single HTML file.

**To run it locally:**
```bash
git clone https://github.com/YOUR_USERNAME/cybersentinel-car.git
cd cybersentinel-car
open CyberSentinel_CAR_MVP.html
# or double-click the file — no server or installation needed
```

**What the demo includes:**
- 🤖 Live WhatsApp bot simulation with AI fraud scanner
- 📍 Bangui fraud hotspot map (PK5, Combattant, Miskine...)
- 📊 Real-time dashboard with KPIs and alert feed
- 🏗️ Full technical architecture with interactive accordion
- 🇨🇫 Multilingual alerts (French + Sango)

---

## 🏗️ Technical Architecture

```
┌─────────────────────────────────────────────────────┐
│                    USER CHANNELS                    │
│         WhatsApp │ USSD (*XXX#) │ SMS Alerts        │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│              AI / NLP ENGINE                        │
│   Python · spaCy · scikit-learn · FastAPI           │
│   Risk score 0–100 · Response < 500ms               │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│           INTEGRATION LAYER                         │
│  Twilio WhatsApp API │ Africa's Talking USSD        │
│  Orange Centrafrique SMS Gateway                    │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│        FRAUD INTELLIGENCE DATABASE                  │
│   PostgreSQL · Python ETL · Auto-reporting          │
│   Anonymized · GDPR compliant · AWS Lightsail       │
└──────────────────────┬──────────────────────────────┘
                       │
┌──────────────────────▼──────────────────────────────┐
│          PARTNER DASHBOARD                          │
│   React · D3.js · REST API · Role-based access      │
│   For: Orange Centrafrique · COBAC · NGOs           │
└─────────────────────────────────────────────────────┘
```

**Tech Stack:**
- **AI/NLP:** Python, spaCy 3.7, scikit-learn, BERT multilingual
- **API:** FastAPI, Redis cache, Docker
- **WhatsApp:** Twilio WhatsApp Business API
- **USSD:** Africa's Talking API
- **Database:** PostgreSQL 16, Python ETL pipeline
- **Dashboard:** React 18, D3.js, JWT authentication
- **Hosting:** AWS Lightsail (optimized for CAR infrastructure)

---

## 📈 Impact Targets — Year 1

| Metric | Target |
|---|---|
| Users protected by AI alert system | 50,000+ |
| Fraud awareness lessons delivered | 200,000+ |
| Fraud reports collected | 10,000+ |
| Women among primary users | 60%+ |
| Estimated fraud losses prevented | €150,000+ |

---

## 🗓️ Roadmap

**Phase 1 — May to July 2026 · Build & Validate**
NLP model training, WhatsApp bot live, pilot with 500 users in Bangui, Orange Centrafrique partnership validation.

**Phase 2 — August to October 2026 · Scale & Intelligence**
5,000 active users, fraud intelligence database live, first CAR fraud bulletin published, OSVP International Finals.

**Phase 3 — 2027 · Expand Africa**
50,000+ users in CAR, model licensing to Cameroon and DRC, B2B threat intelligence revenue, Orange Digital Center integration across 17 countries.

---

## 💰 Revenue Model

CyberSentinel CAR is a social enterprise designed for financial sustainability from Year 2:

- **B2B Threat Intelligence** — Monthly fraud bulletins sold to Orange, banks, and humanitarian operators
- **Platform Licensing** — White-label model licensed to Orange operations in other countries
- **CSR Partnerships** — Corporate co-funding from telecoms committed to consumer protection
- **Training & Certification** — Paid digital security modules via Skills Bridge Academy

---

## 👤 About the Founder

**Timothée Bambala Gandombi** — Bangui, Central African Republic

Founder & President of ONE YOUNG LEGACY (OYL) · Co-Founder of CAYPA (UN-affiliated) · Civil Engineering degree · C1 English · YALI Alumni · Harvard Aspire Leaders Program Alumni · ECOSOC Youth Forum Speaker

> *"In the CAR, digital financial inclusion is growing — but cybersecurity literacy is zero. CyberSentinel CAR protects the people who have the most to lose and the fewest tools to protect themselves."*

---

## 🤝 Partners & Affiliations

- **ONE YOUNG LEGACY (OYL)** — Founding organization
- **CAYPA** — Central African Young Professionals Association (UN Major Group affiliated)
- **Orange Centrafrique** — Prospective technical and distribution partner
- **UNDP CAR** — Prospective humanitarian integration partner
- **Skills Bridge Academy** — Digital literacy deployment infrastructure

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

## 📬 Contact

**Timothée Bambala Gandombi**
Founder, CyberSentinel CAR / ONE YOUNG LEGACY
Bangui, Central African Republic

---

<div align="center">

**CyberSentinel CAR · ONE YOUNG LEGACY**

*Born in Africa. Built for the World.*

🇨🇫 · 🛡️ · 🌍

</div>

