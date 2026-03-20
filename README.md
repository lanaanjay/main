<p align="center">
  <a href="https://github.com/[username]/[repo-name]">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=32&pause=1000&color=60A5FA&center=true&vCenter=true&width=500&lines=Lanjay;Cloudflare+Full-Stack+Boilerplate" alt="Lanjay - Cloudflare Powered" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Cloudflare-%23F38020.svg?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/Wrangler-%23F38020?style=for-the-badge&logo=cloudflare-workers&logoColor=white" alt="Wrangler" />
  <img src="https://img.shields.io/badge/Workers-Edge%20Runtime-blueviolet?style=for-the-badge&logo=cloudflare&logoColor=white" alt="Workers" />
  <img src="https://img.shields.io/badge/Pages-Frontend%20Hosting-FF69B4?style=for-the-badge&logo=cloudflare-pages&logoColor=white" alt="Pages" />
  <img src="https://img.shields.io/badge/TypeScript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript" />
</p>

<p align="center">
  <strong>Modern · Performant · Edge-first · Full-stack Cloudflare boilerplate</strong><br>
  Built for learning clean architecture, Agile workflow, and blazing-fast deployment
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#features">Features</a> •
  <a href="#tech-stack">Tech Stack</a> •
  <a href="#project-structure">Structure</a> •
  <a href="#getting-started">Get Started</a> •
  <a href="#deployment">Deploy</a> •
  <a href="#contributing">Contributing</a>
</p>

<br>

## ✨ Features

- ⚡ **Edge-first architecture** — Everything runs on Cloudflare's global network
- 🛠 **Separated backend & frontend** in monorepo style
- 🔧 **Wrangler** for local dev + deployment (both Workers & Pages)
- 🚀 **Zero-config CI/CD** potential with GitHub Actions + Cloudflare
- 📊 **Agile workflow** integrated with **Jira**
- 🧹 Clean folder structure + TypeScript ready
- 🌐 **Frontend**: Static + possible SPA (React/Vue/Svelte-ready)
- 🔒 Built-in utils, services, routes pattern for scalability

<br>

## 🛠 Tech Stack

| Layer         | Technology                          | Purpose                              |
|---------------|-------------------------------------|--------------------------------------|
| Backend       | Cloudflare Workers                  | Serverless API & edge logic          |
| CLI/Deploy    | Wrangler                            | Local dev, deploy, bindings          |
| Frontend      | Cloudflare Pages                    | Jamstack / SPA hosting               |
| Language      | TypeScript                          | Type safety across full-stack        |
| Task Mgmt     | Jira + Agile                        | Sprint planning & issue tracking     |
| VCS           | GitHub                              | Source control & collaboration       |

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,cloudflare,git,github,vscode&theme=dark&perline=7" alt="Tech icons" />
</p>

<br>

## 📂 Project Structure

<details>
<summary><strong>Click to expand folder structure</strong> 🗂️</summary>

```text
.
├── src
│   ├── backend               # Cloudflare Worker backend
│   │   ├── index.ts          # Main entry point
│   │   ├── routes            # Route handlers / API endpoints
│   │   ├── services          # Business logic, external integrations
│   │   └── utils             # Helpers, validators, formatters
│   └── frontend              # Cloudflare Pages frontend
│       ├── index.html        # Entry point
│       ├── src               # Source code (components, pages, etc)
│       ├── components        # Reusable UI components
│       └── assets            # Static images, fonts, etc
├── public                    # Static assets served directly
├── wrangler.toml             # Worker + Pages config
├── package.json              # Dependencies & scripts
├── tsconfig.json             # TypeScript config
├── README.md
└── .gitignore
