# Session 01 — MyFirstHack Days 1–3

**Career-path notes:** Still deciding — MyFirstHack builds toward SOC Analyst (detection/investigation) or GRC Analyst (governance, risk & compliance).

## Day 1 — The Cybersecurity Landscape

**Core idea:** Cybersecurity is the digital version of the physical security you already practice — protecting computers, networks, data, and people from digital attacks.
**Quiz takeaway:** Cybersecurity, in simple terms, is protecting computers, networks, and data from attacks (not building software or fixing machines). Most cyberattacks start with something simple, like a weak password or a suspicious email.
**Case study — Colonial Pipeline:** May 7, 2021 — one compromised employee password (no 2FA) let attackers lock the company out of its own systems. Result: 6-day pipeline shutdown, gas shortages across multiple states, $4.4M ransom paid. Point: most attacks exploit basic mistakes, not sophistication.
**Career paths introduced:** SOC Analyst (SIEM dashboard, investigating alerts, detective work) vs. GRC Analyst (compliance checks like GDPR, vendor risk, writing policy).

## Day 2 — Why Most Beginners Fail (And How You Won't)

**Core idea:** Day 2 is statistically the most dangerous point in a 90-day program — not because content gets harder, but because this is where "signed up enthusiastically" meets "actually has to show up daily." Most people who quit don't quit because it's too hard; they quit for a handful of avoidable, predictable reasons.
**Quiz takeaway:** Consistency beats intensity — showing up for 30 minutes daily beats occasional long sessions.

## Day 3 — Your First Security Audit *(Milestone Day)*

**Core idea:** A 5-step self-audit methodology — **Scope → Intelligence → Exposure → Severity → Remediation** — applied to your own digital life. This produces a real portfolio artifact: a "Personal Security Audit Report."
**Quiz takeaway:** N/A (this day is fully hands-on, no separate quiz captured).
**Portfolio artifact:** A filled-out Personal Security Audit Report (scope, executive summary, findings by severity, actions taken, remediation plan). ⚠️ See the root README's privacy note — publish the *process and learning*, not the literal list of your real accounts and unpatched gaps.

## Hands-on tasks

### Day 1 — 3 tasks

**Task 1 — Find Out What's Already Out There**
Check haveibeenpwned.com with your primary email.
_Capture:_ total breach count · top 3 breach companies + year · your honest gut reaction.

**Task 2 — Map Your Current Knowledge**
Self-rate 1–5 on 10 core areas: networking, Linux/command line, encryption, firewalls, spotting phishing, malware types, penetration testing, incident response, cloud security basics, compliance (GDPR/HIPAA etc.).
_Capture:_ your 10 scores, saved somewhere safe — the program revisits this exact list on Day 20 to show the jump.

**Task 3 — See What the Jobs Actually Want**
On LinkedIn Jobs, open 3 "SOC Analyst" listings and 2 "GRC Analyst" listings in your area. Read the Requirements sections.
_Capture:_ the 5 most common requirements repeated across all 5 listings (things like SIEM, Splunk, ISO 27001, incident response, risk assessment) — the program revisits this list at Day 90.

### Day 2 — 2 tasks

**Task 1 — Block Your 30 Minutes**
Create a recurring 30-minute calendar event for your daily learning slot.
_Capture:_ the exact time window you picked · whether you actually set it as recurring.

**Task 2 — Name Your Most Likely Trap**
Pick the one beginner-failure trap you're most at risk for: The Overwhelm Spiral (bookmark everything, finish nothing) · Tutorial Hell (consume content instead of doing) · The Fundamentals Boredom Wall (bored by basics, want the "cool stuff") · The Life-Got-In-The-Way Trap (missed commitments are a pattern for you).
_Capture:_ which trap · one specific sign you'll notice when it's happening · what you'll do instead.

### Day 3 — 5 steps *(Milestone Day — produces a portfolio artifact)*

**Step 1 — Scope your audit:** write down your primary email, your 5 most important accounts, your primary device, your home network name.

**Step 2 — Gather intelligence:** revisit HaveIBeenPwned reading it as an auditor (note date + what was exposed per breach, and the single worst breach); also run your email through Epieos (a free OSINT tool) to see what's publicly linkable to it (photos, accounts, services).

**Step 3 — Identify your current exposure:** check active/unrecognized sessions on your primary email account; check 2FA status (ON / OFF / SMS-only) on each of your 5 key accounts; count how many accounts an attacker could take over via "Forgot password" on your email alone.

**Step 4 — Rate and remediate:** sort every finding into Critical / High / Medium / Low; then actually fix one thing right now (enable 2FA on the most important account missing it, or upgrade SMS-2FA to an app, or revoke one unused third-party app / fix one reused password).

**Step 5 — Write your audit report:** fill in the full Personal Security Audit Report template (Scope → Executive Summary → Findings by severity → Actions Taken → Remediation Plan) using Steps 1–4, save it dated (e.g. `personal-security-audit-2026-XX-XX.md`), and screenshot the Findings section.
⚠️ See the root README's privacy note before publishing this one — write up the process/methodology and counts, not your real account names or literal unpatched gaps.

## Key takeaways (across all 3 days)

- Cybersecurity fundamentals matter because most real-world breaches (like Colonial Pipeline) come from basic failures, not sophisticated hacking.
- Two realistic entry paths exist from this program: SOC Analyst and GRC Analyst — no need to choose a lane yet.
- Most people who quit learning programs don't quit from difficulty — they quit from inconsistency. The fix is a fixed daily time slot.
- Day 3 turns self-reflection into an actual portfolio artifact using a real audit methodology (Scope → Intelligence → Exposure → Severity → Remediation).

## Proof / files

## LinkedIn post

```
Day 1-3 of 90 with @MyFirstHack — kicking off my cybersecurity journey.

Three days in and I've already: run my own email through HaveIBeenPwned and found out exactly which breaches I never knew about, self-rated where I actually stand across 10 core security topics (revisiting this on Day 20 to see the jump), scoped out what real SOC and GRC Analyst job listings actually ask for, named the exact habit-trap most likely to make me quit, and run my first full personal security audit using a real 5-step methodology — Scope, Intelligence, Exposure, Severity, Remediation.

That audit was the one that hit hardest: your primary email isn't just an account, it's the master key to almost everything else you own online.

Following MyFirstHack's 90-day path from beginner to cybersecurity foundations, tracking the whole thing here: https://github.com/AnmolNisar/30-Days-Cybersecurity-Journey

#myfirsthack #cybersecurity
```

## Next up

Do the actual hands-on tasks for Days 1–3, add your own screenshots/notes to this folder, then move to Session 02 (Days 4–6: how computers work, the internet, and IP addresses).
