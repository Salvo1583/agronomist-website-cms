<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=180&section=header&text=Calogero%20Romano&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Website%20%26amp%3B%20CMS%20for%20an%20agronomist%20consultant&descSize=18&descAlignY=58" alt="Calogero Romano" width="100%" />
</p>

<p align="center"><b>🇬🇧 English</b> · <a href="README.it.md">🇮🇹 Italiano</a></p>

<p align="center">
  <img src="https://img.shields.io/badge/source-private-555555?style=for-the-badge&logo=github" alt="Source private" />
  <img src="https://img.shields.io/badge/project-showcase-36BCF7?style=for-the-badge" alt="Project showcase" />
</p>

> [!NOTE]
> This repository is a **project showcase**: the source code is private. A demo is available on request.

## 🧭 Overview

Website and **content management system** for Dr. Calogero Romano, agronomist consultant: a public site to present services and past work, online appointment booking, a blog, and an admin area where the client manages everything without touching code.

*Client project.*

## ✨ Key features

- 🌿 **Public site**: services, portfolio of past works, blog, legal pages
- 📅 **Online booking** synced with Google Calendar
- ✉️ **Transactional emails** for booking confirmations
- 📝 **Rich-text CMS** to write and publish blog posts and works
- 🔐 **Admin area** with authentication
- 🍪 **GDPR-ready**: cookie banner and legal pages
- 🧪 **Mock mode**: the whole site runs locally without any external service, for fast development and demos

## 🏗️ Architecture

```mermaid
flowchart LR
    U([Visitor]) --> S[Next.js site]
    A([Admin]) --> CMS[CMS area]
    S --> DB[(Supabase)]
    CMS --> DB
    S --> GC[Google Calendar]
    S --> M[Email service]
```

## 🧰 Tech stack

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![Google Calendar](https://img.shields.io/badge/Google_Calendar-4285F4?style=flat&logo=googlecalendar&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat&logo=zod&logoColor=white)
![TipTap](https://img.shields.io/badge/TipTap_editor-000000?style=flat)

## 📬 Contact

Built by **Salvatore Cutaia**, Computer Engineer specialized in AI agents & automations.

[![GitHub](https://img.shields.io/badge/GitHub-Salvo1583-181717?style=flat&logo=github)](https://github.com/Salvo1583)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Salvatore_Cutaia-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/salvatore-cutaia-6047b0155/)
[![Website](https://img.shields.io/badge/Website-neuralform.it-111111?style=flat&logo=googlechrome&logoColor=white)](https://neuralform.it/)
