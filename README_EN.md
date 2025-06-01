# 📦 ARCHI.Tech-_2025 — Data Architecture for the Digital Ruble Platform (CBDC)

## 🧩 Project Overview

This repository contains materials related to the data architecture of the Central Bank Digital Currency (CBDC) platform — the digital ruble. The model was developed as part of the **ARCHI.Tech 2025** hackathon and follows the requirements set by the Bank of Russia for the secure, transparent, and compliant exchange of information.

The conceptual model describes key entities and processes, including digital wallets, signature mechanisms (digital certificate + device fingerprint), electronic message interactions (ES), client consents, payment orders, and operational audit logging.

---

## 📁 Repository Structure

```bash
├── /presentation/         # Final project presentation (PowerPoint)
├── /images/               # UML diagram visualizations
└── README.md              # Project description
```

📎 **The full HTML-exported model from Enterprise Architect** is available via:  
👉 [https://disk.yandex.ru/d/gJC5k6_4m2LoVw](https://disk.yandex.ru/d/gJC5k6_4m2LoVw)

---

## 📌 Key Architecture Principles

- One digital wallet per participant (individual, legal entity, financial intermediary, or special participant)
- All signed operations require a valid pair: digital certificate + device fingerprint
- Interactions between entities are based on standardized electronic messages (ES)
- Separation of operational and analytical data layers
- Full compliance with Russian legislation (Federal Law 152, AML/CFT regulations, and the CBDC concept)

---

## 🚀 Technologies Used

- **Enterprise Architect** — for UML class modeling
- **Microsoft PowerPoint** — for visual presentation
- **Enterprise Architect HTML Export** — to share the model in browser-friendly format

---

## 🔗 Useful Links

- 📎 [Project model and presentation (Yandex.Disk)](https://disk.yandex.ru/d/gJC5k6_4m2LoVw)
- 📘 [Bank of Russia — ES Message Standard Documentation](https://www.cbr.ru/fintech/dr/doc_dr/albums_r/)
- 📄 [Digital Ruble Concept (PDF)](https://www.cbr.ru/content/document/file/120075/concept_08042021.pdf)

---

## 📄 License

This project is distributed under the **MIT License** — free use, copying, and modification is permitted with attribution.

---

👤 *Author: Team Olga_001*  
🏁 *Hackathon: ARCHI.Tech 2025*
