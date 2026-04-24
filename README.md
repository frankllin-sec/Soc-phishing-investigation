
# SOC Analyst Study Project — Phishing Alert Investigation

# SOC Analyst Study Project — Phishing Alert Investigation

![TryHackMe](https://img.shields.io/badge/Platform-TryHackMe-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Level](https://img.shields.io/badge/Level-Entry--Level-blue)

## Background

While attempting the TryHackMe SOC Level 1 path before completing
the foundational modules, I found myself struggling to follow the
investigation workflow without a structured reference. Instead of
giving up, I decided to document the entire process as a learning
resource — building a step-by-step tutorial using real simulated
alerts from the SOC Simulator.

## What this project is

A complete phishing alert investigation tutorial built from real
simulated alerts in the TryHackMe SOC Simulator scenario
**"Introduction to Phishing."**

The tutorial walks through the full Level 1 SOC Analyst workflow:
from receiving an alert in the queue to writing the final
incident report.

## Investigation Workflow

| Step | Description |
|------|-------------|
| 01 — Read the Alert | Collect all fields: sender, recipient, timestamp, URL |
| 02 — Identify Red Flags | Spot phishing indicators in the email content |
| 03 — Check Firewall Logs | Correlate the email alert with the firewall alert |
| 04 — Build the Timeline | Connect all events in chronological order |
| 05 — Classify and Report | True Positive vs False Positive + incident report |

## Alert Screenshots

### Alert 8814 — Phishing Email Received
![Alert 8814](https://github.com/frankllin-sec/Soc-phishing-investigation/blob/main/screenshots/SOC%20Analyst%20Study%20Project%20—%20Phishing%20Alert%20Investigation1.png)

### Alert 8816 — Firewall Blocked the Connection
![Alert 8816](https://github.com/frankllin-sec/Soc-phishing-investigation/blob/main/screenshots/SOC%20Analyst%20Study%20Project%20—%20Phishing%20Alert%20Investigation3.png)

## Full Tutorial

For the complete step-by-step investigation with detailed
analysis, download the PDF below:

📄 [Download Full Tutorial PDF](https://github.com/frankllin-sec/Soc-phishing-investigation/blob/main/soc_phishing_tutorial_final.pdf) 

## Skills Demonstrated

- Phishing email analysis and red flag identification
- Firewall log correlation and endpoint investigation
- Attack timeline construction
- True Positive vs False Positive classification
- Incident report writing (IOCs, closure rationale, remediation)

## Tools and Platforms

- TryHackMe SOC Simulator
- Claude AI (used as a study and documentation tool)

## Note on AI Usage

This tutorial was developed with the assistance of Claude AI
to help structure the investigation methodology and generate
the documentation format. All analytical decisions, alert
classifications, and learning outcomes reflect my own
understanding of the material.

---

