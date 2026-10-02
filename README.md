# Hi, I'm Eduan 👋

Full-stack developer building web apps and the CRM integrations behind them. Most of my day is spent connecting customer-facing websites to Microsoft Dynamics 365, so form submissions, leads and accounts land in the right place without anyone copying and pasting.

### 🔧 What I work on
- **Custom CRM/CMS (solo, in production):** designing, building and running the platform a sales and account management team uses every day, from architecture and security through integrations and new features
- **AI integration:** a custom MCP server that lets an AI assistant read live CRM data and take scoped, auditable actions
- **Web apps:** React + Vite frontends, Node.js + Express APIs
- **Cloud:** Azure hosting and deployment
- **CRM & automation:** Microsoft Dynamics 365, Dataverse, Power Automate
- **Security:** securing website-to-CRM APIs with Microsoft Entra ID (OAuth 2.0) and Azure Key Vault for secrets

### 🚀 What I've built

**Custom CRM/CMS: an Account Accountability & Execution platform**<br>
Built solo from the ground up and running in production for a real sales and account management team. It's a real web app, not a plugin or no-code tool. It has had 120+ hours of development and manages 1,300+ contacts across 700+ accounts.

<details>
<summary><b>What it does</b></summary>

- **Account & relationship management:** accounts, contacts, requirements, opportunities, quotes, orders, products, suppliers, risks and escalations, all linked together, with many-to-many parent/subsidiary relationships shown as an interactive mind-map
- **Sales pipeline:** opportunities tracked stage by stage (Lead → Qualified → Quote → Negotiation → Won/Lost), tied to quotes and orders, with real-time pipeline value rollups
- **Execution tracking:** actions, next steps and follow-ups per account, plus a daily view of everything due across each person's book
- **Team workspace:** internal messaging, a shared calendar synced with Google Calendar, and a task tracker with status boards, drag-and-drop subtasks, start/stop time tracking, comments and activity feeds, all privacy-scoped per person at the database level
- **Documents:** upload and preview of images, PDFs, Word and Excel files at contact and account level, with a company-wide browser for admins
- **Client review links:** secure, token-based pages for client account reviews without giving clients system access
- **Reporting & global search:** cross-entity search and reporting dashboards across the whole dataset
</details>

<details>
<summary><b>Integrations</b></summary>

- **AI assistant via MCP:** a custom Model Context Protocol server and API layer that connects a ChatGPT-based executive assistant to live account, contact and pipeline data, with scoped actions such as logging follow-ups, adding notes and moving opportunity stages
- **GoHighLevel:** bidirectional contact sync, including custom fields, between the marketing/lead platform and the CRM
</details>

<details>
<summary><b>Security & engineering</b></summary>

- Row Level Security enforced on every table at the database level
- TOTP multi-factor authentication, idle session timeouts and server-enforced login lockouts
- Individually revocable personal API keys for every external integration
- Automated dependency vulnerability scanning in CI
- Vitest test suite wired into CI
- Scheduled database backups (GitHub Actions + pg_dump) with automatic restore checks
- dev → main branch workflow with build-gated weekly releases
</details>

**Stack:** React 19, TypeScript, Vite, Supabase (Postgres, Auth, Realtime, Edge Functions, Storage), Render, GitHub Actions

**Website-to-CRM pipeline**<br>
A React + Express system on Azure that sends website form submissions straight into Dynamics 365 as leads and accounts, so nobody re-enters them by hand.

**CRM workflow automation**<br>
Power Automate flows on Dataverse that handle routing, notifications and record updates automatically.

### 🛠️ Tech stack

**Languages**<br>
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)

**Frontend**<br>
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Backend**<br>
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)
![REST APIs](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat&logo=postman&logoColor=white)

**Data**<br>
![Azure SQL Database](https://img.shields.io/badge/Azure_SQL_Database-0078D4?style=flat&logo=microsoftsqlserver&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)

**Security**<br>
![Microsoft Entra ID](https://img.shields.io/badge/Entra_ID_(OAuth_2.0)-0078D4?style=flat&logo=microsoft&logoColor=white)
![Azure Key Vault](https://img.shields.io/badge/Azure_Key_Vault-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Cloud & DevOps**<br>
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

**CRM & Automation**<br>
![Dynamics 365](https://img.shields.io/badge/Dynamics_365-0B53CE?style=flat&logo=dynamics365&logoColor=white)
![Dataverse](https://img.shields.io/badge/Dataverse-088142?style=flat&logo=microsoft&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0066FF?style=flat&logo=powerautomate&logoColor=white)
![Power Apps](https://img.shields.io/badge/Power_Apps-742774?style=flat&logo=powerapps&logoColor=white)

**Tools**<br>
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)
![npm](https://img.shields.io/badge/npm-CB3837?style=flat&logo=npm&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)

### 📌 Currently
- Building my very own CRM, focused on client management

### 📫 Get in touch
- LinkedIn: [Eduan van Waveren](https://www.linkedin.com/in/eduan-van-waveren-49b35a262/)
