# 90-Day AI Sprint

**Day 1 of 90 · Started 26 July 2026 · Ends 23 October 2026**

Daily builds from a 90-day self-directed programme — Python, AI agents, multi-cloud deployment and PM tooling. Every day has a working deliverable.

---

## What this is

Every day for 90 days: one programming block and one study block. The programming compounds — C, then Python, then APIs, then agents, then deployed applications. The study block rotates through AI, cloud, project management and IT service management.

The rule is that each day produces something that exists as a file, a link or a running service. No day counts as done because I watched a video.

This repo is the evidence.

## Who I am

18 years in flight simulator maintenance, currently a Designated Site Lead at Boeing. PMP, Lean Six Sigma Black Belt, ISO 9001 Lead Auditor, B.Sc. Computer Science. This sprint is about turning that operational and project background into working software.

---

## Progress

| Week | Days | Focus | Status |
|-----:|:-----|:------|:-------|
| 1 | 1–7 | CS50: computational thinking, C basics, algorithms · OpenAI AI Foundations, Google AI Essentials | In progress |
| 2 | 8–14 | CS50: memory, data structures, Python · Google Prompting Essentials, PMI GenAI | — |
| 3 | 15–21 | Python: collections, files, OOP, APIs · PMI courses, Elements of AI | — |
| 4 | 22–28 | Scraping, Flask, first deployment · Anthropic Academy | — |
| 5 | 29–35 | Claude API, agents, automation · MCP, Agent Skills, Subagents | — |
| 6 | 36–42 | pandas, boto3, Lambda, MongoDB · AWS Cloud Practitioner | — |
| 7 | 43–49 | Docker, multi-cloud deployment · Azure AZ-900, Google Cloud | — |
| 8 | 50–56 | PM toolkit in Python · Google Project Management | — |
| 9 | 57–63 | ITSM tooling · ITIL 4 Foundation | — |
| 10 | 64–70 | AI platform, evaluation harness, guardrails · OpenAI Agents | — |
| 11 | 71–77 | Development data tooling · UNICEF, WHO, UN Women | — |
| 12 | 78–84 | Portfolio site · Harvard leadership and rhetoric | — |
| 13 | 85–90 | Capstone: AI-assisted project management tool | — |

---

## Repository structure

```
90-day-ai-sprint/
├── week-01/          C programs: Scratch, Caesar cipher, search algorithms
├── week-02/          Pointers, linked lists, first Python
├── week-03/          Collections, OOP, file I/O, first API calls
├── week-04/          Scraping, Flask, first deployment
├── week-05/          Claude API, agents, automation scripts
├── week-06/          pandas, boto3, MongoDB, AWS deployment
├── week-07/          Docker, multi-cloud deploy tool
├── week-08/          PM toolkit: charter, risks, tasks, Gantt, budget
├── week-09/          ITSM: incidents, changes, CMDB, SLA monitoring
├── week-10/          AI platform: doc Q&A, multi-agent, evals
├── week-11/          Development and humanitarian data tooling
├── week-12/          Portfolio site
├── capstone/         AI-assisted project management tool
├── prompts.md        Reusable prompt library
├── pm-prompts.md     Project-management prompt library
├── certificates.md   Every credential earned, with verification links
├── progress-log.md   Daily log: what was built, what blocked
└── requirements.txt
```

---

## Projects

Filled in as they ship.

| Project | What it does | Week | Link |
|:--------|:-------------|-----:|:-----|
| — | — | — | — |

---

## Certificates

| # | Credential | Issuer | Date | Verify |
|--:|:-----------|:-------|:-----|:-------|
| — | — | — | — | — |

Also tracking PDUs toward PMP renewal. Full list in [`certificates.md`](certificates.md).

---

## Running the code

Most weeks are standalone scripts. From Week 4 onward, packages are required:

```bash
git clone https://github.com/<your-username>/90-day-ai-sprint.git
cd 90-day-ai-sprint
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
```

API keys go in a local `.env` file, which is gitignored and never committed:

```
ANTHROPIC_API_KEY=...
OPENAI_API_KEY=...
```

---

## Log

**Day 1 — 26 July 2026.** CS50 Lecture 0: binary, ASCII, abstraction, algorithms, pseudocode. Built a first Scratch animation. Started OpenAI AI Foundations. Repo created.

---

*Updated daily. If the last commit is more than two days old, hold me to it.*
