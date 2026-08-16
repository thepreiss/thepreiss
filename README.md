# Emerson Reis — Software Developer & IT Operations Engineer

**Hortolândia, SP — Brazil** · Open to work · [LinkedIn](https://linkedin.com/in/epaular) · emerson.thereis@gmail.com

> Available for **in-person or hybrid** roles in São Paulo Interior (Greater Campinas area) or Salvador, and **fully remote** opportunities worldwide.

---

10 years managing IT operations and SLAs in mission-critical environments — first at IBM handling 500+ incidents/month with consistently the highest First Contact Resolution rate on the team, then at Proxxi coordinating 1,200+ critical incidents/month across 30+ field specialists.

Along the way I built Java/Selenium automations that eliminated 60+ manual hours/month for my own operations team. I served as a business stakeholder on an IBM Watson scheduling rollout — solution design, live demos in English — and developed a taste for solving operational problems with code rather than headcount.

In the past year I shifted to full-stack development, designing and deploying a complete multi-product cloud ecosystem from scratch. My background in how systems fail in production — and why SLAs break — informs how I design and validate what I ship.

Currently finishing a degree in Cybersecurity at FATEC Americana (concluded July 2026) and actively looking for the right opportunity.

---

## 🚗 ParaFatec — Smart Parking Ecosystem

A full parking management platform built from scratch and deployed in a real production environment. Started as a single Android app, evolved into nine integrated products when the original architecture hit its limits (no iOS access, no support for specialized POS hardware).

Nine products. One Firebase project. Zero infrastructure cost.

```
IP Camera → YOLOv8 (LPR) → Firestore ← Android POS (Sunmi, thermal print)
                                  ↓
              Operator Dashboard (PWA) + Client App (PWA) + Admin Hub
                                  ↓
                   Yard Terminal (Android, API 15) — client check-in/check-out
```

| Product | Platform | Stack |
|:---|:---|:---|
| [parafatec-mobile](https://github.com/thepreiss/parafatec-mobile) | PWA | React 19, Tailwind 4, TanStack Query |
| [parafatec-client](https://github.com/thepreiss/parafatec-client) | PWA | React 19, Leaflet, Framer Motion |
| [parafatec-bi-auditor](https://github.com/thepreiss/parafatec-bi-auditor) | Web | React 19, Recharts, jsPDF |
| [parafatec-autoatendimento](https://github.com/thepreiss/parafatec-autoatendimento) | PWA Mobile | React 19, Vite 8, Multi-step Form |
| [parafatec-pos](https://github.com/thepreiss/parafatec-pos) | Android | Kotlin 2.0, Jetpack Compose, Sunmi ESC/POS |
| [parafatec-terminal](https://github.com/thepreiss/parafatec-terminal) | Android | Java API 15, Kiosk Mode, Custom OTA Updates, TLS 1.2 Hack |
| [parafatec-edge-ai](https://github.com/thepreiss/parafatec-edge-ai) | Python | YOLOv8, OpenCV, EasyOCR, ONVIF LPR |
| [parafatec-privacy-public](https://github.com/thepreiss/parafatec-privacy-public) | Static Web | HTML/CSS — LGPD Compliance & LPR Privacy Policies |
| [parafatec-core-legacy](https://github.com/thepreiss/parafatec-core-legacy) | Android | Kotlin 2.0, MVI, Clean Architecture *(Legacy Monolith Showcase)* |

> 📄 Full ecosystem documentation: [PARAFATEC.md](./PARAFATEC.md)

---

## 📦 Other Projects

**[ITSM Automation Scripts](https://github.com/thepreiss/itsm-automation-scripts)**
Java/Selenium scripts built to automate corporate ticket dispatching and SLA management in mission-critical environments.

**[Central de Orçamentos](https://github.com/thepreiss/Central-Orcamentos)**
Dashboard and quotation management platform. 

**[VanPlus](https://github.com/thepreiss/VanPlus)**
Ecosystem for school transport management and route tracking. 

**[JobMatch](https://github.com/thepreiss/JobMatch_ETEC)**
Platform bridging students and local businesses for internships. Built with a dedicated [WebAdmin dashboard](https://github.com/thepreiss/JobMatch-webadmin) and a [MySQL backend](https://github.com/thepreiss/JobMatch-backend-MySQL).

---

## 🛠 Stack

**Languages:** `Python` `Kotlin` `Java` `TypeScript` `HTML/CSS`

**Frontend:** `React 19` `Tailwind CSS 4` `Framer Motion` `Vite` `PWA`

**Android:** `Jetpack Compose` `Material Design 3` `MVI` `Clean Architecture` `Dagger Hilt`

**AI & Automation:** `YOLOv8` `OpenCV` `EasyOCR` `ONVIF/RTSP` `Gemini API` `Java/Selenium`

**Backend & Cloud:** `Firebase (Auth · Firestore · Hosting · App Check · Admin SDK)` `Supabase` `Vercel`

**IT Operations:** `IBM Maximo (ITSM)` `Active Directory (IAM)` `Microsoft Azure` `TCP/IP · DNS · VLANs`

**Tooling:** `TanStack Query` `Leaflet` `jsPDF` `ExcelJS` `ZXing` `GitHub Actions`

---

## 💼 Experience

**Independent Consultant / Solutions Architect** — Americana, SP · *Jan 2026 – Jul 2026*
Designed and deployed the ParaFatec ecosystem: nine integrated products running on zero-cost Firebase infrastructure, with GitHub Actions CI/CD, Edge AI for license plate recognition (YOLOv8/EasyOCR processed 100% on-premise for LGPD compliance), and hardware integrations with Sunmi POS terminals and legacy Android tablets repurposed as kiosks.

**Senior IT Operations Analyst — Proxxi Tecnologia** · *Mar 2017 – Dec 2025*
- Built Java/Selenium automation that batch-processed corporate ticket updates, saving 60+ manual operational hours per month and reducing human error
- Orchestrated routing and dispatch for 1,200+ critical monthly incidents across 30+ field specialists, maintaining strict SLA compliance
- Acted as operational stakeholder on an IBM Watson scheduling implementation — participated in solution design and delivered technical demonstrations in English

**IT Support Analyst (N2) — IBM** · *Mar 2014 – Mar 2017*
- Consistently held the highest First Contact Resolution (FCR) rate on the team while handling 500+ incidents/month
- Managed identity, security groups and network permissions via Active Directory (IAM) across the corporate environment
- Led escalation and cross-team alignment during severe outages, coordinating with global teams in English

---

## 🎓 Education

- **Tecnólogo em Segurança da Informação** — FATEC Americana *(Concluded July 2026)*
- **Bacharel em Sistemas de Informação** — PUC Campinas *(2020)*
- **Técnico em Administração, Desenvolvimento Web e Desenvolvimento de Software** — ETEC Hortolândia

## 📜 Certifications

`Microsoft Azure Fundamentals (AZ-900)` `IBM Security Zero Trust` `Cisco Cybersecurity Essentials` `Agile Explorer (IBM)` `TOEIC L&R`

## 🌐 Languages

**Portuguese** — Native · **English** — B2 Upper-Intermediate (TOEIC certified)

---

## 🇧🇷 Em Português

Desenvolvedor Full Stack e Engenheiro de Operações de TI com 10 anos de experiência em ambientes de missão crítica (IBM e Proxxi). Histórico comprovado em automação de processos (Java/Selenium), gestão de incidentes em escala e sustentação de SLAs. 

No último ano, projetei e entreguei do zero o ecossistema de software **ParaFatec**: uma arquitetura distribuída com 9 produtos em produção, incluindo apps B2B/B2C (React, PWAs), totens legados rodando Kiosk Mode (Java, OTA updates), e sistemas Edge AI para reconhecimento de placas (YOLOv8, processamento 100% local visando compliance com a LGPD). O código-fonte integral destes sistemas, sanitizado, está aberto ao público na listagem de repositórios acima.

Disponível para oportunidades **presenciais ou híbridas na Região de Campinas/SP ou Salvador/BA**, e **remoto globalmente**.

> 📄 Leia o aprofundamento arquitetural: [PARAFATEC.md](./PARAFATEC.md)

---
