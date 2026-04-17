# George — Desenvolvedor de Sistemas de Automação & Vibe Coding

Construo sistemas operacionais com Python, React e Android — da câmera de reconhecimento de placas por IA até o app do cliente no celular.

Nos últimos dois anos, desenvolvi um ecossistema completo de gestão de estacionamento rodando em produção real, com nove produtos interconectados usando o Firebase Spark (plano gratuito) como backbone central. Zero custo de infraestrutura por escolha de arquitetura deliberada — não por limitação.

---

## 🚗 ParaFatec — Smart Parking Ecosystem

O projeto central. Um sistema completo de gestão de estacionamento com reconhecimento automático de placas por IA, quatro PWAs, dois apps Android nativos e um engine de automação em Python — tudo rodando sobre um único projeto Firebase no plano gratuito.

```
Câmera IP → YOLOv8 (LPR) → Firestore → Dashboard Gerencial / App do Cliente
                                  ↓
                    POS Handheld + Terminal de Pátio (Android)
```

| Produto | Plataforma | Função |
|:---|:---|:---|
| [ParaFatecMobile](https://github.com/thepreiss/ParaFatecMobile) | PWA (React 19) | Painel operacional para gestores e operadores |
| [ParaFatecClient](https://github.com/thepreiss/ParaFatecClient) | PWA (React 19) | App do cliente: QR de acesso, histórico, mensalidade |
| [ParaFatecMigration](https://github.com/thepreiss/ParaFatecMigration) | Web (React 19 + IA) | Hub administrativo com auditoria via Gemini AI |
| [ParaFatecAutoAtendimento](https://github.com/thepreiss/ParaFatecAutoAtendimento) | PWA Mobile | Cadastro de novos clientes pelo próprio celular |
| [ParaFatecPOS](https://github.com/thepreiss/ParaFatecPOS) | Android (Kotlin 2) | Terminal de mão Sunmi — check-in, tickets e impressão |
| [ParaFatecTerminal](https://github.com/thepreiss/ParaFatecTerminal) | Android (Java) | Tablet fixo de pátio — check-in de clientes, OTA |
| [ParaFatecAutomation](https://github.com/thepreiss/ParaFatecAutomation) | Python (YOLOv8) | Engine de LPR on-premise, câmeras ONVIF/RTSP |
| [ParaFatec-Privacy](https://github.com/thepreiss/ParaFatec-Privacy) | Static Web | Portal de privacidade (LGPD) — [live ↗](https://privacy-parafatec.web.app) |
| [ParaFatec](https://github.com/thepreiss/ParaFatec) | Android (Kotlin + MVI) | App legado — origem e referência arquitetural do ecossistema |

> Repositórios privados — código apresentado ao vivo. Documentação completa: [PARAFATEC.md](./PARAFATEC.md)

---

## 📦 Outros Projetos

### MoralCar — Em desenvolvimento
Plataforma web para gestão de uma empresa de automóveis. Produto em construção, sem data de lançamento definida.
→ [`thepreiss/moral-car`](https://github.com/thepreiss/moral-car)

### BuscaTransporte — Live
Plataforma de busca de transporte público regional. Hospedada em produção em [buscatransporte.com.br](https://buscatransporte.com.br).
Projeto pausado — chegou ao ar mas não validou tração suficiente para justificar crescimento. Uma lição cara e útil sobre validação de produto antes de infraestrutura.
→ [`thepreiss/project`](https://github.com/thepreiss/project)

---

## 🛠 Stack

**Linguagens**
`Python` `Kotlin` `Java (Android legado)` `TypeScript` `HTML/CSS`

**Frontend & Mobile**
`React 19` `Tailwind CSS 4` `Framer Motion` `Vite` `PWA` `Jetpack Compose` `Material Design 3`

**Automação & IA**
`YOLOv8 (Ultralytics)` `OpenCV` `EasyOCR` `ONVIF/RTSP` `Gemini API`

**Backend & Infraestrutura**
`Firebase (Auth · Firestore · Hosting · App Check)` `Firebase Admin SDK`

**Padrões & Arquitetura**
`MVI` `Clean Architecture` `Dagger Hilt` `TanStack Query` `Offline-First`

**Ferramentas**
`Leaflet` `jsPDF` `ExcelJS` `ZXing` `DataTables.net`

---

## 📫 Contato

- **E-mail:** emerson.thereis@gmail.com
- **GitHub:** [@thepreiss](https://github.com/thepreiss)

---

<sub>O ecossistema completo foi construído com zero custo de infraestrutura — tudo no Firebase Spark Plan. Arquitetura deliberada, não limitação.</sub>
