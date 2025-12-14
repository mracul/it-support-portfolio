```markdown
# CODEX — MSP-Aligned GitHub Portfolio (IT Support / Service Desk)

Purpose: This document is the **complete guide** for building a minimal, professional GitHub portfolio aimed at **entry-level IT Support / Service Desk roles in MSP environments**.  
Goal: Create **one repo** that proves support-oriented thinking: **clear documentation, methodical troubleshooting, and basic IT support fundamentals**.  
Non-goals: flashy personal website, complex tech stack, “engineer portfolio”, overclaiming skills.

---

## 1) Target Outcome (what “done” looks like)

You have a public GitHub repository with:

- A clean landing page published on GitHub Pages:  
  `https://<username>.github.io/it-support-portfolio/`
- A small, professional structure with **Markdown artifacts**:
  - Troubleshooting playbooks (support-oriented)
  - Labs/learning notes (hands-on, practical)
- Content that is **credible for L1 MSP roles**:
  - No exaggerated claims (no “admin”, “engineer”, “cloud” unless used hands-on)
  - No personal history essays
  - Strong clarity, structure, escalation mindset

---

## 2) Repo Naming + Principles

### Recommended repo name
- `it-support-portfolio`

### Tone + positioning rules
- Write for an MSP hiring manager skimming fast.
- Prioritize **accuracy, clarity, and process** over “passion” or hype.
- Use a “service desk” voice: calm, structured, escalation-aware.
- Avoid vendor name-dropping unless actually used.

---

## 3) Final Structure (minimal, expandable)

Create exactly this to start:

```

it-support-portfolio/
│
├── index.md                 # GitHub Pages landing page
├── README.md                # Repo overview (short)
│
├── troubleshooting/
│   ├── wifi-basic.md
│   ├── device-not-detected.md
│   └── peripheral-checklist.md
│
├── labs/
│   ├── networking-basics.md
│   ├── os-troubleshooting.md
│   └── hardware-diagnostics.md
│
└── assets/
├── diagrams/
└── screenshots/

````

Notes:
- `assets/` starts empty. Add diagrams/screenshots later if helpful.
- Keep it small. Ship early.

---

## 4) GitHub Setup (repo + Pages)

### 4.1 Create the repository
1. Go to GitHub → **New repository**
2. Name: `it-support-portfolio`
3. Visibility: **Public**
4. Initialize: optional (either is fine). If not initialized, you’ll add files locally.

### 4.2 Enable GitHub Pages
After pushing content:
1. Repo → **Settings**
2. **Pages**
3. Source: **Deploy from a branch**
4. Branch: `main`
5. Folder: `/ (root)`
6. Save

Resulting URL:
- `https://<username>.github.io/it-support-portfolio/`

---

## 5) Local Setup (recommended workflow)

### 5.1 Clone repo
```bash
git clone https://github.com/<username>/it-support-portfolio.git
cd it-support-portfolio
````

### 5.2 Create folders + files

```bash
mkdir -p troubleshooting labs assets/diagrams assets/screenshots
touch index.md README.md
touch troubleshooting/wifi-basic.md troubleshooting/device-not-detected.md troubleshooting/peripheral-checklist.md
touch labs/networking-basics.md labs/os-troubleshooting.md labs/hardware-diagnostics.md
```

### 5.3 Commit + push

```bash
git add .
git commit -m "Initial MSP-aligned IT support portfolio structure"
git push origin main
```

---

## 6) Content Standards (this is what makes it valuable)

### 6.1 Content rules (non-negotiable)

* Every doc must be easy to skim.
* Use headings and checklists.
* Use “first-line support” logic:

  * Gather info → quick wins → isolate cause → resolve → confirm → document → escalate if needed.
* Include escalation criteria (what would make you escalate / to whom).
* Keep examples generic and non-confidential.

### 6.2 Avoid

* Long autobiographical paragraphs
* Overclaiming (no AD/M365/Jira/Intune unless you’ve used it)
* “Case studies” initially (optional later)
* Fancy site design or frameworks

---

## 7) Required Files (what to put in each)

### 7.1 `README.md` (short, professional)

Purpose: explain what the repo is in 2–5 lines.

Template:

```markdown
# IT Support Portfolio

This repository contains troubleshooting playbooks and hands-on labs created to demonstrate practical skills relevant to entry-level IT support and service desk roles.

Focus areas:
- Structured troubleshooting
- Clear documentation
- Core IT support fundamentals
```

### 7.2 `index.md` (GitHub Pages landing)

Purpose: recruiter-facing summary. Keep it MSP-aligned.

Suggested content blocks:

* Title + role intent (Entry-level IT Support / Service Desk)
* What the portfolio contains (Troubleshooting Playbooks + Labs)
* Support mindset (calm, methodical, document, escalate)
* Certifications planned (A+, ITIL 4)
* Contact links

(Use the latest index.md you already wrote as the baseline.)

---

## 8) Troubleshooting Playbook Template (use for all in `troubleshooting/`)

Each playbook MUST follow this structure:

```markdown
# <Issue Name>

## Scope
- What this playbook covers
- What it does NOT cover

## Symptoms (what the user reports)
- Bullet list

## Initial Questions (info gathering)
- Device / OS / location / last known working
- Error messages (exact text)
- Recent changes

## Quick Checks (fast wins)
- Power, cables, reboot, airplane mode, etc.

## Step-by-Step Troubleshooting
1. Start with simplest checks
2. Verify expected outcomes after each step
3. Narrow variables (different device/network/port)

## Likely Causes
- List likely causes from most common → least

## Resolution / Workaround
- What to do when you identify each cause

## Validation (confirm it’s fixed)
- Tests to run
- User confirmation

## Escalation Criteria
Escalate if:
- Security risk suspected
- Repeated failures after standard checks
- Requires permissions/admin access
- Hardware replacement required
- Impacts multiple users / site-wide outage

## Notes (optional)
- Any pitfalls, logs to capture, screenshots to request
```

---

## 9) Lab Note Template (use for all in `labs/`)

Each lab MUST follow this structure:

```markdown
# <Lab Name>

## Goal
What you are learning or proving.

## Setup
- Devices/OS used
- Tools used (only if actually used)
- Network context (home Wi-Fi, router, etc.)

## Procedure
- Steps taken (numbered)

## Observations
- What happened
- What changed when variables changed

## What I Learned
- 3–6 bullets, practical takeaways

## Relevance to IT Support
- 2–4 bullets mapping to service desk work (triage, documentation, escalation)

## Next Steps (optional)
- Small extension ideas (don’t bloat)
```

---

## 10) Minimal Starter Content (ship fast)

### 10.1 First three playbooks

Start with these:

* `troubleshooting/wifi-basic.md`
* `troubleshooting/device-not-detected.md`
* `troubleshooting/peripheral-checklist.md`

Aim: 1–2 pages each, clean structure.

### 10.2 First three labs

Start with these:

* `labs/networking-basics.md` (IP, DHCP, DNS basics)
* `labs/os-troubleshooting.md` (startup/performance/basic checks)
* `labs/hardware-diagnostics.md` (peripheral/ports/basic hardware isolation)

Keep them simple. Depth comes later.

---

## 11) Quality Gate (before linking on resume)

Before you link this portfolio:

* Landing page loads on GitHub Pages.
* README is clean and short.
* At least **1 playbook + 1 lab** are complete.
* Spelling + formatting look professional.
* No confidential workplace data.

---

## 12) How to Use This Codex With an Agent

Instruction for your agent:

* Create repo with exact structure above.
* Populate `README.md` and `index.md`.
* Write the first 1–3 playbooks using the provided template.
* Write the first 1–2 labs using the provided template.
* Push to GitHub and enable Pages.
* Confirm final URL and list of files.

Success criteria:

* Portfolio is public, accessible, and recruiter-readable in under 60 seconds.

---

## 13) Optional Enhancements (ONLY after baseline is shipped)

Do not do these until baseline is live:

* Add diagrams in `assets/diagrams/`
* Add a “tools used” section only when true
* Add a simple changelog
* Add case studies later once you have more IT-context material

---

## 14) Quick Command Summary

```bash
git clone https://github.com/<username>/it-support-portfolio.git
cd it-support-portfolio

mkdir -p troubleshooting labs assets/diagrams assets/screenshots
touch index.md README.md
touch troubleshooting/wifi-basic.md troubleshooting/device-not-detected.md troubleshooting/peripheral-checklist.md
touch labs/networking-basics.md labs/os-troubleshooting.md labs/hardware-diagnostics.md

git add .
git commit -m "Initial MSP-aligned IT support portfolio structure"
git push origin main
```

Then enable Pages:
Settings → Pages → Deploy from branch → main → / (root)

---

End of CODEX.

```
::contentReference[oaicite:0]{index=0}
```
