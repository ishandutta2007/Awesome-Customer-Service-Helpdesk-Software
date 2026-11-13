# Awesome-Customer-Service-Helpdesk-Software

# Top Customer Service & Helpdesk Software Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Ticket Management, Shared Inboxes & Omnichannel Customer Support*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Service & Helpdesk Software**. These tools help support teams manage incoming requests across email, chat, phone, and social channels—consolidating conversations, automating routing, and tracking resolution metrics so nothing falls through the cracks.

**Examples** include Zendesk Support, Freshdesk, Zoho Desk, Help Scout, Intercom, Jira Service Management, Front, Gorgias, LiveAgent, and open-source alternatives like Zammad, FreeScout, and osTicket (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted helpdesk platforms, open-source ticketing systems, and community-driven shared inboxes—ideal for organizations seeking data sovereignty and eliminating per-agent licensing costs. The open-source helpdesk landscape is mature and production-ready: Zammad offers the closest Zendesk-like experience, FreeScout nails the Help Scout shared-inbox model, and osTicket handles simple email-to-ticket workflows [citation:1][citation:12].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Zoho Desk](https://www.zoho.com/desk/)** | Context-aware helpdesk within the Zoho ecosystem. Includes email ticketing, social channels, SLAs, workflow automation, and Zia AI (on higher tiers). Standard tier supports unlimited agents. | Standard: **$14/agent/month** (annual); Professional: $23; Enterprise: $40; Express: $7 | **Free**: up to 3 agents, basic email ticketing; **15-day free trial** (auto-downgrades to Free, no credit card) [citation:13] |
| **[Freshdesk](https://www.freshworks.com/freshdesk/)** | Cloud helpdesk with AI-powered service (Freddy). Growth tier covers email support; Pro adds custom dashboards, multilingual helpdesk, and round-robin assignment; Enterprise adds skill-based routing and audit logs. | Growth: **$19/agent/month** (annual); Pro: $55; Enterprise: $89 [citation:4] | No permanent free tier; trial available. Freddy AI Agent includes 500 free sessions, then $49 per 100 [citation:15] |
| **[Zendesk Support](https://www.zendesk.com/)** | Industry-standard ticketing platform. **Standalone Support Team is $19/agent/month** (annual), distinct from Zendesk Suite pricing. Zendesk is transitioning to **Outcome AI Platform** with outcome-based pricing (unlimited seats, pay for eligible outcomes) in Early Access [citation:3][citation:14]. | Support Team: **$19/agent/month** (annual) [citation:13] | No free tier; trial via sales. Outcome AI Platform pricing in EAP [citation:3] |
| **[Help Scout](https://www.helpscout.com/)** | Shared inbox focused on conversation quality. Standard adds AI Inbox assistant; Plus adds unlimited AI Drafts. Docs (knowledge base) costs **$10/user/month extra on Standard**—making Standard+Docs ($35) nearly comparable to Plus ($50) [citation:6]. | Standard: **$25/user/month** (annual); Plus: $50; Pro: $65 [citation:6] | **Free**: 5 users, 1 Inbox, 1 Docs site [from prior research] |
| **[Intercom](https://www.intercom.com/)** | AI-first customer service platform. **Fin AI agent** resolves conversations autonomously at **$0.99 per outcome**; Copilot assists human agents (10 conversations/month included, unlimited at $35/user/month). Fin outcomes often dominate the bill at scale [citation:7]. | Essential: **$29/seat/month** (annual); Advanced: $85 [citation:7] | No permanent free tier; trial available. Fin outcome pricing: $0.99 each [citation:7] |
| **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)** | Atlassian's service management platform. **Free tier: 3 agents, unlimited customers**. Premium adds 24/7 support and advanced automation. Rovo AI credits included on paid plans. Customer Service Management adds **$1 per resolution** on top of agent seats [citation:9]. | Premium: **$55.28/agent/month** [citation:9] | **Free**: 3 agents, unlimited customers, 2 GB storage, 100 emails/day [citation:9] |
| **[Front](https://front.com/)** | Collaborative inbox for shared email, chat, and messaging. Starter supports single channel type; Professional adds omnichannel and macros. 14-day trial of Professional (no credit card) [citation:10]. | Starter: **$25/seat/month**; Professional: $65; Enterprise: $105 [citation:10] | **14-day free trial** of Professional [citation:10] |
| **[Gorgias](https://www.gorgias.com/)** | E-commerce-focused helpdesk (Shopify, BigCommerce, Magento). Automates order-related tickets with macros and intent-based routing. Plans scale by ticket volume rather than seats. | Quote-only (ticket-volume based) | Free trial available; no permanent free tier |
| **[LiveAgent](https://www.liveagent.com/)** | Helpdesk with universal inbox for tickets, chats, calls, and social. **AI assistants run on your own AI provider account**—LiveAgent does not charge for AI usage. Starter up to 5 agents; Enterprise flat fee with 80 agents included [citation:11]. | Starter/Team/Business: per-agent; Enterprise: flat fee + 80 agents [citation:11] | Free trial available; no permanent free tier |
| **[ServiceNow CSM](https://www.servicenow.com/)** | Enterprise customer service management. **Fulfiller seats roughly $100–$200/user/month** at smallest band, falling above 2,500 seats. Now Assist AI adds $25–$75/fulfiller/month on pre-2026 contracts; April 2026 tiers include AI with assist allocation [citation:5]. | Quote-only; ~$100–$200/fulfiller/month (smallest band) [citation:5] | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Zammad](https://github.com/zammad/zammad)** | [![Stars](https://img.shields.io/github/stars/zammad/zammad?style=social&color=white)](https://github.com/zammad/zammad/stargazers) | **The closest open-source Zendesk alternative** and the only tool with built-in importers for Zendesk, Freshdesk, Kayako, and OTRS [citation:12]. Ruby on Rails. Multi-channel intake (email, chat, phone, social), deep REST API, and reporting. **Needs 4–8 GB RAM** (Elasticsearch is the main consumer) [citation:12]. Best for growing support organizations wanting breadth and a modern API. |
| **[FreeScout](https://github.com/freescout-helpdesk/freescout)** | [![Stars](https://img.shields.io/github/stars/freescout-helpdesk/freescout?style=social&color=white)](https://github.com/freescout-helpdesk/freescout/stargazers) | **The best open-source Help Scout-style shared inbox** [citation:12]. PHP/Laravel. Runs comfortably on **1–2 GB RAM** and is the only tool designed for shared hosting [citation:12]. Core software is free; **SLA management and satisfaction surveys are paid modules ($2–$19 each)**—factor these into TCO [citation:12]. Best for small teams, nonprofits, and installs where speed matters more than feature depth [citation:1]. |
| **[osTicket](https://github.com/osTicket/osTicket)** | [![Stars](https://img.shields.io/github/stars/osTicket/osTicket?style=social&color=white)](https://github.com/osTicket/osTicket/stargazers) | **Straightforward email-to-ticket system** for teams with limited process complexity [citation:1][citation:12]. PHP/MySQL. Lightweight (1–2 GB RAM). API is functional but limited in scope [citation:12]. Best when you just need email turned into tickets without a modern, deeply integrated platform. |
| **[UVdesk](https://github.com/uvdesk/uvdesk)** | [![Stars](https://img.shields.io/github/stars/uvdesk/uvdesk?style=social&color=white)](https://github.com/uvdesk/uvdesk/stargazers) | Open-source helpdesk with **customer-facing portal emphasis**. Symfony-based. Community Edition self-hostable; hosted plans available. Includes email ticketing, knowledge base, canned responses, and customer portal. **Advanced reporting, automation, or channel coverage may require paid functionality** [citation:1]. Best for teams wanting portal-led support with PHP/Symfony expertise. |
| **[GLPI](https://github.com/glpi-project/glpi)** | [![Stars](https://img.shields.io/github/stars/glpi-project/glpi?style=social&color=white)](https://github.com/glpi-project/glpi/stargazers) | **Wins when you need assets and tickets together** [citation:12]. IT asset management plus helpdesk. Needs 2–4 GB RAM. API solid for asset-related operations. Best for IT teams managing hardware/software inventory alongside support tickets. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Faveo Helpdesk](https://github.com/ladybirdweb/faveo-helpdesk)** | [![Stars](https://img.shields.io/github/stars/ladybirdweb/faveo-helpdesk?style=social&color=white)](https://github.com/ladybirdweb/faveo-helpdesk/stargazers) | Laravel-based helpdesk with ticket management, knowledge base, and SLA. **Runs paid SaaS tiers alongside the free self-hosted version**—verify edition capabilities before committing [citation:12]. |

**Frameworks for building custom systems**: Choose **Zammad** for Zendesk-like breadth and multichannel intake, **FreeScout** for a lightweight shared-inbox model on minimal hardware, **osTicket** for simple email-to-ticket, and **GLPI** when asset management and ticketing must coexist—all deployable on a $10–$20/month VPS [citation:12].

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Helpdesk platforms handle customer PII and support conversations; enforce role-based access, audit logging, and compliance with applicable data protection regulations.
- **Open-source helpdesk TCO is not zero.** FreeScout gates SLA management and CSAT surveys behind paid modules ($2–$19 each) [citation:12]. Zammad needs 4–8 GB RAM. Budget infrastructure ($10–$20/month VPS), admin time, backups, and security hardening [citation:12]. **SaaS pricing is shifting toward AI outcomes.** Zendesk is moving to Outcome AI Platform with unlimited seats and outcome-based billing [citation:3][citation:14]. Intercom's Fin at $0.99 per outcome can dwarf seat costs at scale—a 10-agent team with 2,000 resolutions/month pays **$1,980 in Fin outcomes alone** vs. $850 in seats [citation:7]. Verify current pricing against vendor pages before committing.

---

**Made for support operations managers, helpdesk administrators, IT service teams, and developers building customer service infrastructure.**  
Let's make customer service helpdesk software more open, affordable, and agent-friendly.
