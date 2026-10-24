# Biter: Trust-Based Dietary Discovery

> **Portfolio project.** A product management case study for Biter, a social food discovery app for people with dietary restrictions. I'm running it from discovery to launch in **Jira** using Scrum, as a solo PM simulating a team's workflow.

**Role:** Product Manager · **Method:** Scrum, 2-week sprints · **Tools:** Jira, Figma, GitHub · **Timeline:** 4 months (Oct 2026 – Feb 2027)

---

## The problem

People with dietary restrictions struggle to choose restaurants with confidence. Menus rarely give reliable allergen or ingredient information, so they piece it together from Google reviews, Facebook groups and phone calls to the restaurant. The research takes longer than the meal, and the stress makes them less willing to try new places.

## The vision

Connect people with dietary needs to trusted, community-validated dining experiences, so they can choose where to eat with confidence.

**Core insight:** trust enables exploration.

## Who it's for

| Segment | Need |
|---|---|
| **Primary:** lactose-intolerant diners | Clear dairy-free options with verified ingredients |
| **Primary:** gluten-sensitive diners | Gluten-free options and cross-contamination awareness |
| Secondary: food-allergy diners | Near-absolute certainty (nuts, shellfish, etc.) |
| Secondary: health-conscious diners | Nutritional transparency |

Target: adults 25–45 in urban areas who dine out 2+ times a week.

## The bet (MVP hypothesis)

> Turning unreliable dietary information into **dish-level, community-validated** insight will increase user confidence and improve conversion and retention among users with dietary needs.

MVP scope: lactose-free and gluten-free filters, basic dish-level tagging, and a one-tap "Was this safe?" (Yes/No) validation.

---

## How I'm running it

The project follows four phases. Each phase is an **epic** in Jira, and the work is planned in two-week sprints.

| Phase | Month | Sprints | Status |
|---|---|---|---|
| 1. Research & Discovery | 1 | Sprints 1–2 | 🟡 In progress |
| 2. Design | 2 | Sprints 3–4 | ⚪ Not started |
| 3. Development | 3 | Sprints 5–6 | ⚪ Not started |
| 4. Launch | 4 | Sprints 7–8 | ⚪ Not started |

### Jira practices used

- **Hierarchy:** Epics → Tasks/Stories → Subtasks
- **Backlog management:** a prioritized backlog. Solution ideas (e.g. *"Filter restaurants by dietary restrictions"*) are deliberately **parked** until research validates them.
- **Sprint planning:** sprint goals, story-point estimates (1/2/3/5/8), and capacity. Each sprint is planned one ahead.
- **Sprint execution:** daily board updates, subtasks, comments and hand-offs, blocker flags
- **Sprint review & retrospective:** documented in [`/retros`](retros/)
- **Reporting:** burndown and velocity charts in [`/jira`](jira/)

### Sprint log

| Sprint | Dates | Goal | Committed | Done |
|---|---|---|---|---|
| Sprint 1 – Discovery | Oct 26 – Nov 6 | Be ready to interview: research plan approved, participants booked, competitor landscape understood | 10 pts | — |
| Sprint 2 – Discovery | Nov 8 – Nov 22 | Complete interviews and turn findings into a research summary | 13 pts | — |

---

## Repository guide

| Folder | What's inside |
|---|---|
| [`00-strategy/`](00-strategy/) | Product brief: vision, segments, value proposition, OKRs, MoSCoW |
| [`01-discovery/`](01-discovery/) | Research plan, interview script, competitive analysis, research summary |
| [`02-design/`](02-design/) | Wireframes, prototype, usability test results |
| [`03-delivery/`](03-delivery/) | PRD, user stories with acceptance criteria |
| [`jira/`](jira/) | Board and backlog screenshots, reports, backlog export |
| [`retros/`](retros/) | Sprint reviews and retrospectives |

## Key decisions

*A running log of product decisions and the reasoning behind them.*

| Date | Decision | Why |
|---|---|---|
| Oct 24, 2026 | Run discovery before writing any feature stories; parked the "dietary filters" story in the backlog | Avoid committing to a solution before validating the problem |
| Oct 24, 2026 | Split discovery into two sprints: prep (plan, recruit, competitors), then interviews and synthesis | Interviews depend on recruiting, so they can't be parallelized |
