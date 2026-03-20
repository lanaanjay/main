# Project Name

<p align="center">
  <svg width="760" height="160" viewBox="0 0 760 160" fill="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Project banner">
    <rect x="1" y="1" width="758" height="158" rx="18" fill="#0B1220" stroke="#334155"/>
    <rect x="32" y="32" width="104" height="96" rx="14" fill="#111827" stroke="#475569"/>
    <path d="M58 78L80 56L102 78L80 100L58 78Z" fill="#60A5FA"/>
    <path d="M80 44V56" stroke="#93C5FD" stroke-width="4" stroke-linecap="round"/>
    <path d="M80 100V112" stroke="#93C5FD" stroke-width="4" stroke-linecap="round"/>
    <path d="M44 78H56" stroke="#93C5FD" stroke-width="4" stroke-linecap="round"/>
    <path d="M104 78H116" stroke="#93C5FD" stroke-width="4" stroke-linecap="round"/>
    <rect x="172" y="38" width="520" height="16" rx="8" fill="#1F2937"/>
    <rect x="172" y="66" width="420" height="12" rx="6" fill="#334155"/>
    <rect x="172" y="90" width="480" height="12" rx="6" fill="#334155"/>
    <rect x="172" y="114" width="360" height="12" rx="6" fill="#334155"/>
    <text x="172" y="145" fill="#CBD5E1" font-family="Arial, sans-serif" font-size="14">
      Cloudflare Wrangler · Workers · Pages · Agile · Jira
    </text>
  </svg>
</p>

## Overview

Repository ini dibuat untuk mendukung pengembangan project berbasis Cloudflare dengan struktur terpisah antara backend dan frontend.

Project ini menggunakan:

- `Wrangler` untuk deployment dan local development
- `Cloudflare Workers` untuk backend
- `Cloudflare Pages` untuk frontend
- `Jira` untuk manajemen tugas secara Agile
- `GitHub` sebagai repository utama dan version control

Project ini disusun sebagai bagian dari proses pembelajaran dan implementasi praktik pengelolaan proyek software secara terstruktur.

## Project Structure

```bash
.
├── src
│   ├── backend
│   │   ├── index.ts
│   │   ├── routes
│   │   ├── services
│   │   └── utils
│   └── frontend
│       ├── index.html
│       ├── src
│       ├── components
│       └── assets
├── public
├── wrangler.toml
├── package.json
├── README.md
└── .gitignore
