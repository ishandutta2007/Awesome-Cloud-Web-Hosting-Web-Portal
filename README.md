# Awesome-Cloud-Web-Hosting-Web-Portal

## Top Cloud Web Hosting & Web Portal Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Static Site Hosting, Managed WordPress & Cloud Application Deployment*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Web Hosting & Web Portals**. These tools provide the infrastructure and deployment pipelines for hosting websites and web applications—covering static site generators, managed WordPress hosting, serverless deployment platforms, and self-hosted control panels that eliminate server administration overhead.

**Examples** include AWS Amplify, Google Cloud Web Hosting, Microsoft Azure App Service, Vercel, Netlify, Cloudflare Pages, WP Engine, Kinsta, Bluehost, and Zoho Sites (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted web hosting control panels, open-source deployment platforms, and community-driven site builders—ideal for developers, system administrators, and organizations seeking data sovereignty and predictable costs over fully managed SaaS lock-in.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global **web hosting market** is substantial and growing, with cloud hosting disrupting legacy shared hosting models. **Shared hosting controlled 37.28% of revenue in 2025** but is losing ground as users migrate to cloud platforms offering auto-scaling and stronger security; **cloud hosting is forecast to grow at a 10.53% CAGR** through 2031 . Public cloud accounts for **45.58% of 2025 spend**, while hybrid and multi-cloud environments grow at 10.75% CAGR .

The sector is **highly fragmented despite hyperscaler dominance**. **AWS, Microsoft Azure, and Google Cloud collectively control over 60% of the cloud infrastructure market**, but in web hosting specifically, **AWS powers only ~5.1% of all websites**, and the **top 10 hosting providers account for roughly 33.6% of the overall hosting market**—leaving most of the market spread across thousands of smaller providers [citation:2]. This is not a winner-take-all market; managed WordPress hosts, static site platforms, and regional providers all maintain viable positions alongside the hyperscalers.

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[AWS Amplify](https://aws.amazon.com/amplify/)** | Fullstack web and mobile hosting with CI/CD, CDN, and backend services. Includes 1,000 build minutes/month, 5 GB CDN storage, and 15 GB data transfer free [citation:3][citation:15]. | Build: $0.01/min (standard); CDN storage: $0.023/GB/month; transfer: $0.15/GB [citation:3] | **12-month free trial**: 1,000 build mins/mo, 5 GB CDN storage, 15 GB transfer, 500K SSR requests [citation:3]. New AWS customers: up to **$200 credits** for 6 months [citation:3]. |
| **[Microsoft Azure App Service](https://azure.microsoft.com/en-us/products/app-service/)** | Managed web app hosting with auto-scale, deployment slots, and custom domains. Supports .NET, Java, Node.js, Python, PHP [citation:5]. | Free (F1); Basic (B1): ~$13/month; Standard (S1): ~$73/month [citation:5] | **Free tier (F1)**: shared compute, 1 GB storage, 165 MB/day bandwidth; no SLA [citation:5] |
| **[Vercel](https://vercel.com/)** | Frontend cloud for static sites and serverless functions with Git integration. Hobby tier free for personal, non-commercial use [citation:6]. | Pro: $20/month (includes usage credit); Enterprise: custom [citation:6] | **Hobby (free)**: 100 GB Fast Data Transfer, 1M CDN requests, 4 CPU-hrs active CPU, 1M function invocations; non-commercial only [citation:6] |
| **[Netlify](https://www.netlify.com/)** | Static site hosting and serverless functions. Moved to a five-meter credit system for new accounts (Sept 2025); legacy Starter plan no longer offered to new signups [citation:7]. | Pro: $20/seat/month (includes credit allowance) [citation:7] | **Free tier** available under credit system; exact allotment depends on usage split across bandwidth, compute, requests, AI inference, and deploys [citation:7] |
| **[Cloudflare Pages](https://pages.cloudflare.com/)** | Static site hosting with unlimited bandwidth on all tiers. Integrates with Cloudflare Workers for dynamic functionality [citation:8]. | Pro: $20/month (5,000 builds/mo); Business: $200/month [citation:8] | **Free**: unlimited bandwidth, 500 builds/month, unlimited sites [citation:8] |
| **[WP Engine](https://wpengine.com/)** | Managed WordPress hosting with daily backups, 24/7 support, and WP/PHP/MySQL management [citation:9]. | Essential: $28/month (annual, discounted) [citation:9] | No free tier; **60-day money-back guarantee** typically offered. Business tier adds 99.99% uptime SLA and phone support [citation:9]. |
| **[Kinsta](https://kinsta.com/)** | Managed WordPress hosting with Google Cloud infrastructure. Premium plans include staging environments and CDN. | WP 2 plan: $70/month (2 WordPress installs, 20 GB storage, 50 GB CDN) [citation:10] | No free tier; **30-day money-back guarantee** available. |
| **[Bluehost](https://www.bluehost.com/)** | Shared, VPS, and dedicated hosting. Promotional pricing for new customers; "unmetered" bandwidth subject to Acceptable Use Policy [citation:11]. | Shared hosting: promotional rates available; regular renewal rates higher [citation:11] | No permanent free tier; **30-day money-back guarantee** on hosting plans. Free domain for first year on qualifying plans [citation:11]. |
| **[Zoho Sites](https://www.zoho.com/sites/)** | Website builder within the Zoho ecosystem. Starter plan: 5 pages, 500 MB storage, 10 GB/month bandwidth, 5 forms [citation:12]. | Starter (annual): paid tier; Pro (annual): 50 pages, 100 GB storage, flat-rate bandwidth [citation:12] | **Free plan** available: single-page website, 100 MB storage, 5 MB max file size [citation:12] |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Coolify](https://github.com/coollabsio/coolify)** | [![Stars](https://img.shields.io/github/stars/coollabsio/coolify?style=social&color=white)](https://github.com/coollabsio/coolify/stargazers) | Self-hosted Heroku/Vercel/Netlify alternative. Deploy static sites, Node.js, PHP, and databases on your own VPS with Git integration and automatic SSL. |
| **[CapRover](https://github.com/caprover/caprover)** | [![Stars](https://img.shields.io/github/stars/caprover/caprover?style=social&color=white)](https://github.com/caprover/caprover/stargazers) | Scalable PaaS on Docker. Deploy apps from Git or Docker images with a web GUI, automatic reverse proxy, and one-click app templates. |
| **[Dokku](https://github.com/dokku/dokku)** | [![Stars](https://img.shields.io/github/stars/dokku/dokku?style=social&color=white)](https://github.com/dokku/dokku/stargazers) | Lightweight Heroku alternative. Git-push deployments to Docker containers on a single server. Battle-tested and widely adopted. |
| **[CloudPanel](https://github.com/cloudpanel-io/cloudpanel-ce)** | [![Stars](https://img.shields.io/github/stars/cloudpanel-io/cloudpanel-ce?style=social&color=white)](https://github.com/cloudpanel-io/cloudpanel-ce/stargazers) | Modern server control panel for PHP, Node.js, and static sites. Nginx-based with Let's Encrypt SSL, MySQL/MariaDB, and firewall management. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[HestiaCP](https://github.com/hestiacp/hestiacp)** | [![Stars](https://img.shields.io/github/stars/hestiacp/hestiacp?style=social&color=white)](https://github.com/hestiacp/hestiacp/stargazers) | Fork of VestaCP with active development. Web server control panel with Nginx/Apache, PHP, DNS, mail, and database management. |
| **[aaPanel](https://github.com/aaPanel/aaPanel)** | [![Stars](https://img.shields.io/github/stars/aaPanel/aaPanel?style=social&color=white)](https://github.com/aaPanel/aaPanel/stargazers) | Web hosting control panel with one-click LEMP/LAMP stack installation, file manager, and app store for WordPress, Laravel, and more. |

**Frameworks for building custom systems**: Combine **Coolify** or **CapRover** for Git-push deployments, **Dokku** for lightweight Heroku-style hosting, and **CloudPanel** or **HestiaCP** for traditional web hosting control panels—creating a fully self-hosted web hosting platform on a single VPS or dedicated server.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Web hosting platforms handle credentials, SSL certificates, and potentially sensitive user data; enforce strong authentication, automatic backups, and least-privilege access to control panels.
- SaaS hosting pricing varies dramatically by traffic volume and resource consumption; serverless platforms (Vercel, Netlify) can produce unpredictable bills under high traffic. Self-hosted control panels require server maintenance, security updates, and backup strategies.

---

**Made for developers, system administrators, and organizations building web hosting infrastructure.**  
Let's make cloud web hosting more open, portable, and cost-transparent.
