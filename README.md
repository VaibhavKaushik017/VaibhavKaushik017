<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Vaibhav%20Kaushik&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Full-stack%20engineer%20%7C%20AI-first%20products%20%7C%20Real-time%20systems&descSize=16&descAlignY=58" width="100%" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3200&pause=900&color=00E5A8&center=true&vCenter=true&width=700&lines=%24+whoami+%E2%86%92+Vaibhav+Kaushik;%24+ship+--ai+--realtime+--typescript;%24+npm+publish+authx+datakit+schedkit+integrakit;%24+status+%E2%86%92+building+things+people+actually+use" alt="typing" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/vaibhavkaushik017"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:kaushikvaibhav017@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=VaibhavKaushik017&style=flat-square&color=00e5a8&label=VISITORS" />
</p>

## `~/about.ts`

```ts
const vaibhav = {
  role: "Software Engineer @ DCKAP",
  previously: "Software Engineer @ Zedblock (Jul 2024 – Jun 2026)",
  stack: ["TypeScript", "NestJS", "Next.js", "MongoDB", "LiveKit", "Remotion"],
  shipped: {
    aiVideoGenerator: "Oculer.video",
    realtimeVoiceAgent: "WebSockets + LiveKit",
    aiWebsiteBuilder: "Aasp.ai",
    aiMarketingPlatform: "Division50 (lead dev, built in under a month)",
    npmPackages: ["authx", "datakit", "schedkit", "integrakit"],
  },
  buildingOnTheSide: "TourFlips: AI travel guide for Indian domestic trips",
  lookingFor: "high-ownership roles on scalable, AI-first products",
} as const;
```

## 🧩 How I build: one set of modules, many products

I turned recurring backend needs into reusable NestJS modules, then used them to ship whole products fast.

```mermaid
flowchart LR
    subgraph Modules["Reusable modules (npm packages)"]
        A[authx<br/>auth]
        D[datakit<br/>schema-driven CRUD + aggregation APIs]
        S[schedkit<br/>scheduled API triggers]
        I[integrakit<br/>third-party integrations]
    end
    A --> P1[Oculer.video]
    A --> P2[Aasp.ai]
    D --> P3[Division50]
    S --> P3
    A --> P3
    classDef mod fill:#0f2027,stroke:#00e5a8,color:#fff;
    class A,D,S,I mod;
```

## 🛠️ Arsenal

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,nodejs,nestjs,react,nextjs,tailwind,mongodb,postgres,supabase,redis,docker,gcp,githubactions,git,postman&perline=8" />
</p>

| | |
|---|---|
| **Real-time and AI** | WebSockets · LiveKit · WebRTC · Remotion · ElevenLabs · Google Gemini |
| **Auth and payments** | JWT · OAuth · Keycloak · Razorpay · Dodo Payments |
| **Infra** | GCP Cloud Run · Hetzner · PM2 · Coolify · GitHub Actions |

## 🔥 Shipped

<details>
<summary><b>Oculer.video</b>: AI text-to-video generator</summary>
<br>

- Next.js dashboard (123+ commits): Remotion-based player, export queue with progress tracking, template selection, brand kits, ElevenLabs voice
- Payment service from scratch in NestJS (112+ commits): Razorpay subscription lifecycle, webhooks, plan enforcement, usage metering
- Auth service (65+ commits): JWT, Google OAuth, onboarding, role-based sessions
- Deployed to GCP Cloud Run, with the render workers on Hetzner via SSH and PM2
</details>

<details>
<summary><b>Real-time AI voice calling agent</b></summary>
<br>

- NestJS backend handling WebSocket sessions, realtime audio streaming and the agent state machine
- Next.js call UI with connection status, audio visualization and session controls
- LiveKit tools-server so the agent can call APIs and look up data mid-conversation
</details>

<details>
<summary><b>Aasp.ai</b>: AI website builder with one-click deploy</summary>
<br>

- Admin panel and dashboard in Next.js for generated sites, users and deployment status
- Auth service (custom + Keycloak) and payments (Razorpay + Dodo Payments)
- One-click pipeline to publish a generated site to production
</details>

<details>
<summary><b>Division50</b>: AI marketing platform (lead developer)</summary>
<br>

- Delivered the full platform in under a month by reusing the modules above
- Backend APIs generated through the Data Module, including aggregation pipelines
</details>

<details>
<summary><b>DCKAP Integrator</b>: ERP-first integration platform</summary>
<br>

- Led the frontend migration to TypeScript with incremental adoption alongside the existing JavaScript
- Shipped AI-powered workflow summaries, scheduler validation, credential management and DataHub improvements
- Wrote technical requirement documents and assessed backward compatibility for new capabilities
</details>

## 🌱 Currently building

**TourFlips**: an AI-powered travel guide for Indian domestic trips (NestJS, Next.js, Supabase Postgres, Redis, Gemini).

## 🐍 Contribution snake

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/VaibhavKaushik017/VaibhavKaushik017/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/VaibhavKaushik017/VaibhavKaushik017/output/github-snake.svg" />
    <img alt="contribution snake" src="https://raw.githubusercontent.com/VaibhavKaushik017/VaibhavKaushik017/output/github-snake.svg" />
  </picture>
</p>

## 📊 Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=VaibhavKaushik017&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=VaibhavKaushik017&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<sub>Most of my work lives in private company repositories, so the public graph understates what I ship.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" width="100%" />
