<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Calogero%20Romano&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Sito%20web%20e%20CMS%20per%20un%20agronomo%20consulente&descSize=18&descAlignY=58" alt="Calogero Romano" width="100%" />
</p>

<p align="center"><a href="README.md">🇬🇧 English</a> · <b>🇮🇹 Italiano</b></p>

<p align="center">
  <img src="https://img.shields.io/badge/codice-privato-555555?style=for-the-badge&logo=github" alt="Codice privato" />
  <img src="https://img.shields.io/badge/vetrina-progetto-36BCF7?style=for-the-badge" alt="Vetrina del progetto" />
</p>

> [!NOTE]
> Questo repository è una **vetrina del progetto**: il codice sorgente è privato. Una demo è disponibile su richiesta.

## 🧭 Panoramica

Sito web e **sistema di gestione dei contenuti** per il Dott. Calogero Romano, agronomo consulente: un sito pubblico per presentare servizi e lavori svolti, prenotazione online degli appuntamenti, un blog e un'area riservata in cui il cliente gestisce tutto senza toccare il codice.

*Progetto per un cliente.*

## ✨ Funzionalità principali

- 🌿 **Sito pubblico**: servizi, portfolio dei lavori, blog, pagine legali
- 📅 **Prenotazione online** sincronizzata con Google Calendar
- ✉️ **Email automatiche** di conferma delle prenotazioni
- 📝 **CMS con editor di testo** per scrivere e pubblicare articoli e lavori
- 🔐 **Area admin** con autenticazione
- 🍪 **Pronto per il GDPR**: banner dei cookie e pagine legali
- 🧪 **Modalità mock**: tutto il sito gira in locale senza servizi esterni, per sviluppo e demo veloci

## 🏗️ Architettura

```mermaid
flowchart LR
    U([Visitatore]) --> S[Sito Next.js]
    A([Admin]) --> CMS[Area CMS]
    S --> DB[(Supabase)]
    CMS --> DB
    S --> GC[Google Calendar]
    S --> M[Servizio email]
```

## 🧰 Tecnologie

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Google Calendar](https://img.shields.io/badge/Google_Calendar-4285F4?style=flat&logo=googlecalendar&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat&logo=zod&logoColor=white)
![TipTap](https://img.shields.io/badge/Editor_TipTap-000000?style=flat)

## 📬 Contatti

Realizzato da **Salvatore Cutaia**, ingegnere informatico specializzato in agenti AI e automazioni.

[![GitHub](https://img.shields.io/badge/GitHub-Salvo1583-181717?style=flat&logo=github)](https://github.com/Salvo1583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salvatore_Cutaia-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-cutaia-6047b0155/)
[![Website](https://img.shields.io/badge/Website-neuralform.it-111111?style=flat&logo=googlechrome&logoColor=white)](https://neuralform.it/)
