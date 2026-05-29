# Real Estate Investment Automation System

**Industry:** Real Estate  
**Stack:** n8n, AI Agent, REST APIs, Google Sheets, Slack, Gmail  
**Demo video:** [Watch the full walkthrough](https://drive.google.com/file/d/11TgDuEtlnMu0DBSbk_kovLGjmxuKo37l/view)

---

## The Problem

A client comes in looking for a property investment opportunity. The company does not already have it at hand. The team has to start working from scratch.

Searching through listings. Calling agents. Comparing multiple opportunities. Checking locations and pricing. Running ROI and cash flow calculations. Trying to organize everything into spreadsheets and reports before management can even review the deal.

When multiple requests come in at the same time, the entire process becomes difficult to manage. Things get missed. Deals get delayed. Hours disappear into manual data gathering that should not require human attention.

---

## The Solution

I built a fully automated investment research and reporting pipeline inside n8n. The moment a client submits their investment requirements, the system takes over.

It matches properties based on the client's criteria, pulls live property data, runs financial analysis, generates a formatted investment report, updates the CRM, and sends instant notifications to the team on Slack. All without anyone touching a spreadsheet.

---

## How It Works

**Step 1 — Client submits investment requirements**  
The workflow triggers the moment a client fills out the intake form. Name, budget, target location, property type, and investment goals are captured automatically.

**Step 2 — AI Agent matches and researches properties**  
An AI Agent processes the client's criteria and queries property listing APIs to find matching opportunities. It filters by location, price range, property type, and availability.

**Step 3 — Financial analysis runs automatically**  
For each matched property, the system calculates ROI, projected cash flow, yield estimates, and key financial metrics. No manual spreadsheet work required.

**Step 4 — Investment report is generated**  
A structured investment report is compiled for the matched properties, including all property details, listing links, agent contacts, and financial projections. Ready for management review.

**Step 5 — CRM is updated**  
All deal data, client requirements, matched properties, and generated reports are pushed into the Google Sheets CRM. Every request has a clean audit trail.

**Step 6 — Team is notified on Slack**  
An instant Slack notification goes to the relevant team channel with a summary of matched properties and a link to the full report.

**Step 7 — Report delivered via Gmail**  
A formatted report email is sent automatically to the client or internal distribution list.

---

## Tools & Stack

| Tool | Role |
|---|---|
| **n8n** | Workflow orchestration and automation engine |
| **AI Agent (OpenAI)** | Property matching logic and natural language processing |
| **REST APIs** | Property listing data and external data sources |
| **Google Sheets** | CRM — stores client requests, matched properties, and reports |
| **Slack** | Real-time team notifications |
| **Gmail** | Automated report delivery |

---

## Results

- Eliminated hours of manual research per client request
- Zero deals missed due to manual process gaps
- Team shifted focus from data gathering to deal review
- All client requests centralized in one trackable system
- System runs 24/7 without supervision

---

## About

Built by **Charles Emmanuel** — AI & Automation Systems Engineer  
Lagos, Nigeria | [LinkedIn](https://linkedin.com/in/charles-emmanuel-automation)  

I build systems that remove repetitive work, improve operational speed, and help businesses scale with structure.
