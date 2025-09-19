# EmpowerFi
 A public repo for the **EmpowerFi** project listed on Karma GAP: https://
 gap.karmahq.xyz/project/empowerfi
 This repository contains:- A minimal website (Vite + React + TS) reflecting the GAP sections: 
**Project**, **Updates**, **Funding**, **Impact**, **Team**.- Open source hygiene: CI, issue/PR templates, license, security & 
contribution guides.
 ## Live sections- **Project**: High‑level overview and links- **Updates**: Changelog / announcements- **Funding**: Grants & backers (mirrors GAP where relevant)- **Impact**: Metrics & outcomes- **Team**: Core contributors
 > Edit `web/src/data/project.ts` to update content without touching UI code.
 ## Local development
 ```bash
 corepack enable
 2
pnpm i
 cd web && pnpm i && pnpm dev
 Build
 cd web && pnpm build
