# Be Aware — Security Awareness Program & Gophish Proof of Concept

A targeted anti-phishing program for a fintech's development team: a hands-on "spot the signs" awareness workshop plus a working, privacy-respecting phishing simulation built with Gophish. Cybersteps Cyberanalyst program (Module 2).

> **Focus:** Human factor / Security awareness (GRC) · **Stack:** Gophish · Docker · MailHog

## Context
Developers are a prime target: they work in public on GitHub and constantly handle new tools and credentials (API keys, test logins), where a single leaked key can be critical. The scenario: credential phishing via a fake developer-tool invitation that asks users to sign in with their work credentials.

## Deliverable 1 — Awareness workshop
A ~10-minute interactive session built around *recognition*, not lecturing: participants see the exact phishing e-mail and fake login page they would face and jointly mark the warning signals, then take away one rule — never sign in through a link in an e-mail; open the service yourself and report anything suspicious.

## Deliverable 2 — Gophish PoC
A fully local, isolated simulation: **Gophish** in **Docker** with **MailHog** as a test SMTP server (nothing leaves the lab). A look-alike landing page records the *action*, not the password — credential capture is disabled by design. After submitting, targets are redirected to a transparent awareness debrief, turning the mistake into a learning moment without shaming.

## Results (live dashboard)
Across four simulated developer targets: **4 sent · 2 opened · 2 clicked · 1 submitted · 0 reported.** The standout finding is the **0 reported** — the missing reporting reflex is the real gap, which is why the workshop emphasises the reporting process.

## Why it matters
Instead of an expensive annual mandatory training, this is a repeatable, measurable, audience-specific program on an open-source basis — and compliance-friendly: no real addresses, no stored credentials, fully isolated.

## Report
Full project report → [`Be-Aware_Report.pdf`](./Be-Aware_Report.pdf)

## Skills
Security awareness · phishing simulation (Gophish) · Docker · social-engineering analysis · security communication · metrics-driven program design · GRC / human factor

---
*Fictional targets and an isolated lab; no real e-mail addresses or credentials were used, and passwords are never stored.*
