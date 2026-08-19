<div align="center">

# Emmanuel Fame

### Software Architect · Backend Engineer · System Builder

I design and ship production software systems — from architecture and backend services  
to infrastructure, integrations, deployment, and ongoing operations.

[![Portfolio](https://img.shields.io/badge/Portfolio-emmanuelfame.netlify.app-7c5cff?style=for-the-badge&logo=vercel&logoColor=white)](https://emmanuelfame.netlify.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Emmanuel_Ayanyemi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/emmanuel-ayanyemi-36865519b/)
[![Email](https://img.shields.io/badge/Email-emmanuelayofame%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:emmanuelayofame@gmail.com)

</div>

---

## About

I'm a software architect and backend-focused engineer interested in systems where reliability,
business workflows, integrations, and infrastructure matter.

My work spans:

- multi-tenant SaaS platforms
- marketplaces and vendor systems
- payment and transaction workflows
- WhatsApp and messaging automation
- REST APIs and backend services
- queues, caching, and real-time infrastructure
- Dockerized production deployments
- dashboards and internal business systems

I recently completed my degree in **Applied Mathematics & Computer Science** at
**Ufa University of Science and Technology**, and I’m continuing into a
**Master’s in Software Engineering**.

Most importantly, I enjoy taking systems from:

`requirement → architecture → implementation → deployment → production`

---

# Selected Production Work

<table>
<tr>
<td width="33%" valign="top">

### Bypass Transfers
**Client Project**

Cross-border transaction platform supporting transfer workflows,
rates, orders, receipts, customer communication, and operational processes.

**My work**
- Backend architecture
- Transaction workflows
- Business logic
- Admin systems
- Production deployment

🌐 [bypasstransfers.com](https://bypasstransfers.com/)

</td>

<td width="33%" valign="top">

### GlyGold
**Founder-Built Platform**

Multi-tenant commerce infrastructure designed for businesses that need
storefronts, orders, payments, messaging, automation, and managed operations.

**My work**
- Platform architecture
- Multi-tenancy
- Provisioning
- Payments
- WhatsApp commerce
- Infrastructure
- Deployment & operations

🌐 [glygold.com](https://glygold.com/)

</td>

<td width="33%" valign="top">

### SAYUZ
**Client Project**

City-aware marketplace connecting users and sellers through listings,
verification, reviews, messaging, discovery, and seller operations.

**My work**
- Marketplace architecture
- Vendor systems
- Trust & verification flows
- Admin infrastructure
- Backend services
- Production deployment

🌐 [sayuz.ru](https://sayuz.ru/)

</td>
</tr>
</table>

---

# Architecture I Work With

```text
Users / Clients
      │
      ▼
Cloudflare / Edge
      │
      ▼
Nginx
      │
      ▼
Laravel / API Layer
      │
      ├── PostgreSQL / MySQL
      ├── Redis
      ├── Queues / Workers
      ├── Payments
      ├── WhatsApp Cloud API
      ├── External APIs
      └── Object / File Storage
             │
             ▼
      Dockerized Infrastructure
