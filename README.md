# Hi, I'm Wilfred Chukwu 👋

**Senior Product Engineer** · 8+ years shipping production software remotely · Based in the Philippines (UTC+8)

[![Portfolio](https://img.shields.io/badge/Portfolio-iamfredcode.com-d4a373?style=for-the-badge&logo=googlechrome&logoColor=white)](https://iamfredcode.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Wilfred%20Chukwu-0A66C2?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0yMC40NSAyMC40NWgtMy41NXYtNS41N2MwLTEuMzMtLjAzLTMuMDQtMS44NS0zLjA0LTEuODUgMC0yLjEzIDEuNDUtMi4xMyAyLjk0djUuNjdIOS4zN1Y5aDMuNDF2MS41NmguMDVjLjQ3LS45IDEuNjMtMS44NSAzLjM2LTEuODUgMy42IDAgNC4yNiAyLjM3IDQuMjYgNS40NXY2LjI5Wk01LjM0IDcuNDNhMi4wNiAyLjA2IDAgMSAxIDAtNC4xMiAyLjA2IDIuMDYgMCAwIDEgMCA0LjEyWk03LjEyIDIwLjQ1SDMuNTZWOWgzLjU2djExLjQ1Wk0yMi4yMyAwSDEuNzdDLjc5IDAgMCAuNzcgMCAxLjczdjIwLjU0QzAgMjMuMjMuNzkgMjQgMS43NyAyNGgyMC40NmMuOTggMCAxLjc3LS43NyAxLjc3LTEuNzNWMS43M0MyNCAuNzcgMjMuMjEgMCAyMi4yMyAwWiIvPjwvc3ZnPg%3D%3D)](https://www.linkedin.com/in/wilfred-chukwu-891830174/)
[![Email](https://img.shields.io/badge/Email-Get%20in%20touch-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:wilfredchukwu1@gmail.com)
[![CV](https://img.shields.io/badge/CV-Download-131210?style=for-the-badge)](https://iamfredcode.com/Wilfred_Chukwu_Resume.pdf)

I build software that scales, not only in traffic and codebase size, but in the value it keeps delivering as both grow. For 8+ years I've worked with remote teams across the US, Europe and Asia, owning products from architecture and data design through deployment, SEO and revenue.

## How I build now: Claude Code and AI agents

Claude Code is my main development environment, and I've shipped an AI feature to production.

- **AI Affiliate Manager (MCP server).** Merchants run [Arkvon](https://devarkvon.it.com/ai-affiliate-manager), my affiliate-program SaaS, from Claude or ChatGPT. It has 17 read tools and 8 action tools, OAuth 2.1 sign-in with PKCE and rotating refresh tokens, a per-workspace limit on actions and an audit log. It went from plan to production in 2 days, security review included.
- **Context agents can trust.** Each of Arkvon's 55 modules has a doc, a short rule file with the reason behind every do and don't, and a row in an index that each repo's `CLAUDE.md` loads. Agents read a module's doc before changing it and update it in the same commit.
- **Parallel sessions, one pull request each.** I run several Claude Code sessions at once, each in its own git worktree. Every session ends in a pull request that GitHub Actions checks (type-check, 800+ tests, lint, build), and nothing merges without my approval.
- **Guardrails.** Before the MCP sign-in shipped, a separate agent reviewed it the way an attacker would; I fixed the 7 issues it found, with tests. Agents work only against the dev database, and I run production migrations myself.

→ [How I build with AI agents](https://iamfredcode.com/#ai)

## Tech stack

| Area | Tools |
| --- | --- |
| **AI & agents** | ![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=for-the-badge&logo=claude&logoColor=white) ![MCP servers](https://img.shields.io/badge/MCP%20servers-131210?style=for-the-badge&logo=modelcontextprotocol&logoColor=white) ![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white) |
| **Languages** | <img src="https://skillicons.dev/icons?i=ts,js,py" alt="TypeScript, JavaScript, Python" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,express,django,flask,fastapi" alt="Node.js, Express, Django, Flask, FastAPI" /> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=nextjs,react,vue,vite,tailwind,threejs" alt="Next.js, React, Vue, Vite, Tailwind CSS, Three.js" /> |
| **Data** | <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis" alt="PostgreSQL, MongoDB, Redis" /> |
| **Infrastructure** | <img src="https://skillicons.dev/icons?i=docker,nginx,linux,aws,git,githubactions,selenium" alt="Docker, Nginx, Linux, AWS, Git, GitHub Actions, Selenium" /> |

Also: system design, API design, database architecture, authentication (OAuth 2.1), performance optimization, payments and payouts (Stripe, PayPal, Wise, crypto), SEO.

More at **[iamfredcode.com](https://iamfredcode.com)**
