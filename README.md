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
| [ParaFatecMobile](https://github.com/thepreiss/ParaFatecMobile) | PWA | React 19, Tailwind 4, TanStack Query |
| [ParaFatecClient](https://github.com/thepreiss/ParaFatecClient) | PWA | React 19, Leaflet, Framer Motion |
| [ParaFatecMigration](https://github.com/thepreiss/ParaFatecMigration) | Web | React 19, Gemini API, ECharts, jsPDF |
| [ParaFatecAutoAtendimento](https://github.com/thepreiss/ParaFatecAutoAtendimento) | PWA Mobile | React 19, Vite 8 |
| [ParaFatecPOS](https://github.com/thepreiss/ParaFatecPOS) | Android | Kotlin 2.0, Jetpack Compose, ESC/POS |
| [ParaFatecTerminal](https://github.com/thepreiss/ParaFatecTerminal) | Android | Java, API 15, OTA Updates |
| [ParaFatecAutomation](https://github.com/thepreiss/ParaFatecAutomation) | Python | YOLOv8, OpenCV, EasyOCR, ONVIF |
| [ParaFatec-Privacy](https://github.com/thepreiss/ParaFatec-Privacy) | Static Web | HTML/CSS — [live ↗](https://privacy-parafatec.web.app) |

> All repos are private — code shown live on request. Full ecosystem documentation: [PARAFATEC.md](./PARAFATEC.md)

---

## 📦 Other Projects

**[BuscaTransporte](https://buscatransporte.com.br)** — Transport Search Platform
Web platform connecting parents with school transporters in the region. Live in production. Project paused — reached deployment but didn't validate enough traction to justify growth investment.
→ [`thepreiss/project`](https://github.com/thepreiss/project)

**MoralCar** — Automotive Business Platform *(in development)*
Web platform for an automotive services business. Active development.
→ [`thepreiss/moral-car`](https://github.com/thepreiss/moral-car)

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

Desenvolvedor Full Stack e Engenheiro de Operações de TI com 10 anos de experiência em ambientes de missão crítica (IBM e Proxxi). Histórico comprovado em automação de processos (Java/Selenium), gestão de incidentes em escala e sustentação de SLAs. No último ano, projetou e entregou do zero um ecossistema de software com nove produtos em produção. Disponível para oportunidades **presenciais ou híbridas na Região de Campinas/SP ou Salvador/BA**, e **remoto globalmente**.

📄 Documentação do ecossistema ParaFatec: [PARAFATEC.md](./PARAFATEC.md)

---
