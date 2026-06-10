# KIU Nexus – Product Capstone 2026

**Project Name:** KIU Nexus  
**Team Name:** Undefined Behaviour  
**Course:** CS-PD-2026 Product Development for Software Engineers  
**Institution:** Kutaisi International University  
**Semester:** Spring 2026  
**Repository Owner:** Giorgi Kveladze (@Giorgi0Kveladze)  
**Live URL:** https://nexus-eight-black.vercel.app

---

## Project Overview

**KIU Nexus** is a unified academic communication and task management platform designed to solve the fragmentation problem third-year Computer Science students face when managing overlapping coursework across Moodle, Microsoft Teams, email, and group chats.

**The Core Problem:**  
Third-year CS students at KIU taking multiple project-based courses experience heightened academic stress and avoidable grade reductions when managing overlapping coursework requirements scattered across five or more different communication platforms.

**The Solution:**  
A centralized dashboard that aggregates all course announcements, deadlines, and assignment requirements in one place, automatically parsing data from university systems and providing intelligent prioritization based on due dates and course weight.

---

## Team Members and Roles

| Name | GitHub | Role | Accountability |
|------|--------|------|-----------------|
| Archil Margvelashvili | @Margvela15 | Program Lead | Deadlines, submissions, team health |
| Nikoloz Jvebenava | @Nikoloz261 | Discovery Lead | Interview quality, synthesis, insights |
| Giorgi Papidze | @wazowski37 | Tech Lead | Architecture, code quality, repo |
| Giorgi Kveladze | @Giorgi0Kveladze | Support Role | Assist tech/discovery as needed |

---

## Project Status

**Current Phase:** MVP Development & GTM Strategy (Week 11/15)  
**Latest Milestone:** Lab 11 Strategic Analysis (June 9, 2026)  
**Next Deadline:** Lab 12 Pitch Rehearsal (June 11, 2026)  
**Demo Day:** June 11, 2026

---

## Repository Structure

```
test/
├── README.md                          # This file
├── .gitignore                         # Git ignore rules
│
├── 00-foundation/                     # Weeks 1-2: Team and Problem
│   ├── team-contract.md              # Team norms and decision-making
│   ├── all-problem-statements.md     # 3H framework problems
│   ├── team-problem-statement.md     # Committed problem + ICP
│   └── team-icp.md                   # Ideal customer profiles
│
├── 01-discovery/                      # Weeks 2-5: Customer Discovery
│   ├── interview-script-v1.md        # Interview methodology
│   ├── interview-script-v2.md        # Refined script post-learnings
│   ├── interview-logs/               # Individual interview records
│   ├── synthesis/                    # Analysis and synthesis
│   │   ├── affinity-map.md
│   │   ├── patterns-analysis.md
│   │   └── final-problem-statement.md
│   └── outreach/
│       ├── outreach-messages.md
│       └── interview-scheduling-tracker.md
│
├── 02-design/                         # Weeks 4-8: Design and Prototyping
│   ├── design-sprint/
│   │   ├── brainstorm-notes.md
│   │   ├── sketches/
│   │   └── design-decisions.md
│   ├── prototypes/
│   │   ├── low-fidelity/
│   │   └── high-fidelity/
│   │       └── figma-link.md
│   └── user-testing/
│       ├── test-plan.md
│       ├── test-session-logs/
│       └── usability-findings.md
│
├── 03-build/                          # Weeks 7-12: MVP Development
│   ├── architecture/
│   │   ├── system-design.md
│   │   ├── tech-stack.md
│   │   ├── architecture-diagram.png
│   │   └── risk-spikes.md
│   ├── src/                          # Next.js + Supabase codebase
│   ├── analytics/
│   │   ├── event-schema.md
│   │   └── dashboard-link.md
│   ├── privacy-security/
│   │   ├── consent-form.md
│   │   └── security-tabletop.md
│   ├── reliability/
│   │   ├── slo-sheet.md
│   │   └── error-budget.md
│   └── roadmap/
│       └── product-roadmap.md
│
├── 04-gtm/                            # Weeks 9-14: Go-to-Market
│   ├── growth-strategy.md
│   ├── loops-and-moats.md
│   ├── experiments/
│   ├── financials/
│   │   ├── unit-economics.md
│   │   ├── growth-projection.xlsx
│   │   └── 12-month-model.xlsx
│   ├── traction/
│   └── marketing/
│       └── landing-page-link.md
│
├── 05-fundraising/                    # Weeks 12-15: Investor Materials
│   ├── pitch-deck.pdf
│   ├── one-pager.pdf
│   └── data-room/
│
├── 06-strategy/                       # Strategic positioning
│   ├── competitive-analysis.md
│   ├── strategy-canvas.md
│   ├── ecosystem-map.md
│   └── moat-statement.md
│
├── 08-legal/                          # Legal and compliance
│   ├── privacy-notice.md
│   └── data-processing-agreement.md
│
└── milestones/                        # Checkpoint documentation
    ├── week-02-milestone.md
    ├── week-04-milestone.md           # Checkpoint 1: Discovery
    ├── week-08-milestone.md           # Checkpoint 2: Design & Architecture
    ├── week-12-milestone.md           # Checkpoint 3: MVP Build
    └── week-15-milestone.md           # Checkpoint 4: Demo Day
```

---

## Key Deliverables Completed

### ✅ Checkpoint 1 – Discovery (Week 4)
- [x] 10+ interview logs with verbatim quotes
- [x] Affinity map and patterns analysis
- [x] Evidence-based final problem statement
- [x] Interview script and synthesis

### ✅ Checkpoint 2 – Design & Architecture (Week 8)
- [x] Lo-fi and hi-fi prototypes (Figma)
- [x] Usability testing logs and findings
- [x] System architecture document
- [x] Tech stack decisions and risk analysis
- [x] Sprint 1 plan

### ✅ Checkpoint 3 – MVP Build (Week 12)
- [x] Live URL deployed to Vercel
- [x] Analytics integration (Mixpanel event schema)
- [x] Sprint retrospectives
- [x] GTM experiment results
- [x] Unit economics model

### 🔄 Checkpoint 4 – Demo Day (Week 15)
- [ ] 8-12 slide pitch deck
- [ ] One-pager (investor summary)
- [ ] 5-minute live pitch
- [ ] Final venture packet review

---

## How to Use This Repository

1. **Understand the Problem:** Start with `/00-foundation/`
2. **Review Customer Discovery:** Check `/01-discovery/` for interview evidence
3. **Explore Design Decisions:** See `/02-design/` for prototypes and testing
4. **Examine the Build:** Look at `/03-build/` for architecture and code
5. **GTM Strategy:** Review `/04-gtm/` for growth and business models
6. **Investor Materials:** See `/05-fundraising/` for pitch and financials

---

## Links

- **Live Product:** https://nexus-eight-black.vercel.app
- **GitHub (Team Repo):** https://github.com/Margvela15/product-capstone-2026
- **Figma Design:** [See `02-design/prototypes/high-fidelity/figma-link.md`]
- **Mixpanel Dashboard:** [See `03-build/analytics/dashboard-link.md`]
- **Pitch Deck:** [See `05-fundraising/pitch-deck.pdf`]

---

## Contact & Questions

- **Instructor:** Zeshan Ahmad | zeshan.ahmad@kiu.edu.ge
- **Program Lead:** Archil Margvelashvili | @Margvela15
- **Repository:** https://github.com/Giorgi0Kveladze/test

---

*Last Updated: June 10, 2026*  
*KIU Nexus | Product Development for Software Engineers | Spring 2026*
