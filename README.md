# Soc-phishing-investigation
# SOC Analyst Study Project — Phishing Alert Investigation

![TryHackMe](https://img.shields.io/badge/Platform-TryHackMe-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Entry--Level-blue)

## Background

While attempting the TryHackMe SOC Level 1 path before completing
the foundational modules, I found myself struggling to follow the
investigation workflow without a structured reference. Instead of
skipping the experience, I decided to document the entire process
as a learning resource — building a step-by-step tutorial that I
could use as a reference during future investigations.

## What this project is

A complete phishing alert investigation tutorial built from real
simulated alerts in the TryHackMe SOC Simulator scenario
**"Introduction to Phishing."**

The tutorial walks through the full Level 1 SOC Analyst workflow:
from receiving an alert in the queue, to writing the final
incident report.

## Investigation Workflow Covered

| Step | Description |
|------|-------------|
| 01 — Read the Alert | Collect all fields: sender, recipient, timestamp, URL |
| 02 — Identify Red Flags | Spot phishing indicators in email content |
| 03 — Check Firewall Logs | Correlate email with firewall alerts |
| 04 — Build the Timeline | Connect events in chronological order |
| 05 — Classify and Report | True Positive vs False Positive + incident report |

## Skills Demonstrated

- Phishing email analysis and red flag identification
- Firewall log correlation and endpoint investigation
- Attack timeline construction
- True Positive vs False Positive classification
- Incident report writing (IOCs, closure rationale, remediation)

## Tools and Platforms

- TryHackMe SOC Simulator
- Claude AI (used as a study and documentation tool)

## Files in this Repository

- `tutorial/soc_phishing_tutorial.pdf` — Full investigation tutorial with screenshots
- `screenshots/` — Real alert screenshots from the SOC Simulator

## Current Certification Progress

- [ ] CompTIA Security+ *(in progress)*
- [ ] TryHackMe Pre Security *(92% complete)*
- [ ] TryHackMe Cyber Security 101 *(upcoming)*
- [ ] TryHackMe SOC Level 1 *(upcoming)*
- [ ] Splunk Core Certified User *(upcoming)*

## Note on AI Usage

This tutorial was developed with the assistance of Claude AI
to help structure the investigation methodology and generate
the documentation format. All analytical decisions, alert
classifications, and learning outcomes reflect my own
understanding of the material.

---
*This project is part of my self-directed transition into
cybersecurity, targeting an entry-level SOC Analyst role.*
