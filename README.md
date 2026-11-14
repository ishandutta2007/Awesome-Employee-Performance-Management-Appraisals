# Awesome-Employee-Performance-Management-Appraisals

## Top Employee Performance Management & Appraisals Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Review Cycles, Goal Alignment & Continuous Feedback*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Employee Performance Management & Appraisals**. These tools help organizations run review cycles, align individual goals with company objectives, and build continuous feedback cultures—covering everything from lightweight review tools to full HRIS-integrated talent suites.

**Examples** include Lattice, 15Five, Leapsome, Betterworks, PerformYard, Small Improvements, Culture Amp, and open-source alternatives like Frappe HR and Horilla HRMS (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted performance management, open-source appraisal workflows, and community-driven HR platforms—ideal for organizations seeking data sovereignty and avoiding per-employee pricing that compounds across headcount. The open-source landscape is genuinely functional: **Frappe HR** provides a complete HRMS with appraisal cycles and goal tracking , and **Horilla HRMS** offers performance management within a broader open-source HR suite .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global employee performance management software market is valued at approximately **$3.5B to $4.5B** (projected to exceed $8B by 2030, expanding at ~10–12% CAGR). The sector is **moderately fragmented**—dominated at the top end by enterprise HCM suites (Workday, SAP SuccessFactors, Oracle) while remaining fiercely contested by specialized, high-growth continuous feedback, OKR, and engagement platforms across SMB and mid-market buyers.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Est. Revenue) | Pricing (Starting) | Free Tier / Trial Limits | Description |
|---|---|---|---|---|
| **[Lattice](https://lattice.com/)** | **$3.0B valuation** (~$130M+ ARR) | **$10/seat/month** (Performance module; min. $4,000/yr annual agreement) | No permanent free tier; live demo / pilot via sales inquiry | Performance management platform connecting reviews, goals, and 1:1s. Goals & OKRs available at $8; Engagement at $4. Implementation included. |
| **[Culture Amp](https://www.cultureamp.com/)** | **$1.5B valuation** (~$100M–$175M ARR) | **~$5–$14/employee/month** (Min. annual spend ~$4,500/yr) | No permanent free tier; product walkthrough via sales consultation | Enterprise engagement and performance platform with validated survey instruments, research-backed benchmarks, and 360° reviews for 200+ seat organizations. |
| **[Leapsome](https://www.leapsome.com/)** | **$800M valuation** (~$35M ARR) | **€7/employee/month** (~$7.50/seat/mo; billed annually) | **14-day free trial** (Full sandbox access; requires sales enablement) | People enablement and performance management platform featuring continuous feedback, review cycles, and competency frameworks. |
| **[15Five](https://www.15five.com/)** | **$250M–$500M valuation** (~$100M ARR) | **$11/user/month** (Perform tier, billed annually) | **14-day free trial** (Access to core features without permanent free plan) | Performance management system with weekly check-ins, continuous feedback, OKRs, and AI-assisted review drafting. |
| **[Betterworks](https://www.betterworks.com/)** | **$177M valuation** (~$40M ARR) | **$8/user/month** (Performance tier, billed annually) | No permanent free tier; sandbox evaluation via sales demo | Enterprise-oriented performance management platform built around OKRs, continuous conversations, feedback, and calibration reviews. |
| **[PerformYard](https://www.performyard.com/)** | **~$95M funding** (~$57M ARR) | **$5/person/month** ($5–$15/person/month based on modules; billed annually) | No permanent free tier; customized live guided demo via sales | Dedicated performance review and goal tracking tool with flexible review workflows, customizable forms, and no extra onboarding fees. |
| **[Small Improvements](https://www.small-improvements.com/)** | **Bootstrapped** (~$5.6M ARR) | **$3/user/month** (Launch plan, billed annually; min. 20 users) | **30-day free trial** (Full access to reviews & feedback features; min. 20 users for paid plans) | Lightweight, self-serve friendly performance reviews, 360-degree feedback, and 1:1 meeting tracking designed for small-to-midsize businesses. |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Frappe HR](https://github.com/frappe/hrms)** | [![Stars](https://img.shields.io/github/stars/frappe/hrms?style=social&color=white)](https://github.com/frappe/hrms/stargazers) | **The most complete open-source HRMS with performance management built in.** Part of the Frappe/ERPNext ecosystem. Features: **goal tracking aligned with KRAs**, employee self-evaluation, and **appraisal cycle management**. Integrated with leave, attendance, payroll, and expense claims in a single platform. Python/Vue stack with REST API and mobile app. **Best for organizations already on Frappe/ERPNext** or wanting an integrated HR suite without per-employee fees. |
| **[Horilla HRMS](https://github.com/horilla/horilla-hr)** | [![Stars](https://img.shields.io/github/stars/horilla/horilla-hr?style=social&color=white)](https://github.com/horilla/horilla-hr/stargazers) | **Comprehensive open-source HRMS with performance management module.** Features: **goal setting, reviews, and continuous feedback** alongside recruitment, onboarding, attendance, leave, payroll, and asset management. REST API, LDAP integration, and role-based dashboards. **Best for SMBs wanting a full HR suite with performance included** without enterprise pricing . |
| **[MeepleOS](https://github.com/JustGoscha/meepleOS)** | [![Stars](https://img.shields.io/github/stars/JustGoscha/meepleOS?style=social&color=white)](https://github.com/JustGoscha/meepleOS/stargazers) | **Lightweight performance review tool for engineering managers.** MIT licensed, vanilla JavaScript with zero setup. **Role-specific evaluations** for Software Engineers, Product Managers, and UX/UI Designers, with **level-specific guidance** from junior to senior roles. Auto-save and export results. **Best for engineering leaders wanting a simple, self-contained review framework** without a full HR platform . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[QuarterMaster](https://socket.dev/npm/package/%40imponenm%2Fquartermaster)** | — | **Automates performance review drafting from GitHub contributions.** CLI tool that fetches merged PRs, code reviews, and commits, then passes them to an LLM (Anthropic, OpenAI, or local Ollama) to generate structured reviews. Aligns contributions to goals from a markdown file. **Not a performance management platform**—a developer-focused review drafting tool . |

**Frameworks for building custom systems**: Choose **Frappe HR** for a complete HRMS with goal tracking and appraisal cycles integrated with payroll , **Horilla HRMS** for a broader HR suite with performance management included , or **MeepleOS** for a lightweight engineering-focused review framework —all without per-employee pricing that scales with headcount.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Performance management platforms handle sensitive employee data including ratings and feedback; enforce strict access controls, manager-only visibility rules, and compliance with applicable employment regulations. **Performance data breaches erode trust irreparably.**
- **Pricing varies significantly and total cost extends beyond list rates.** **Lattice requires a $4,000 minimum annual agreement** . **15Five's add-ons are priced on three different units** (per user, per employee, per manager)—Kona Coach at $19/manager and Content at $49/manager can add substantial cost . **Leapsome's HRIS Foundation is free only until December 31, 2026** (then €7/employee/month) . **Betterworks requires negotiation**—multi-year commitments and bundled modules unlock 15–30% lower pricing . **Small Improvements is the most transparent entry point** at $3/user/month with a 30-day trial . **Open-source options are functional but less feature-rich**: Frappe HR is the most complete but requires the Frappe ecosystem , and Horilla provides a broader HR suite with performance included . Validate implementation effort, integration requirements, and total cost against your actual headcount before committing.

---

**Made for HR leaders, people operations teams, and managers building performance culture.**  
Let's make employee performance management and appraisals more open, fair, and growth-oriented.
