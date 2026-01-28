# Spiceworks Help Desk Ticketing Lab (Portfolio)

A hands-on Help Desk ticketing lab using **Spiceworks Cloud Help Desk** to practice real-world ticket triage, automation rules, documentation, and ticket lifecycle handling.

---

## What This Project Demonstrates
- **Ticket lifecycle management** using available statuses: **Open → Waiting → Closed**
- **Rule-based triage automation** (keyword + organization scope) to standardize prioritization
- **Professional ticket documentation**
  - Internal notes (technician-only)
  - Public responses (user-facing)
- Clear **process documentation** exported as a deliverable PDF

---

## Lab Environment
- **Platform:** Spiceworks Cloud Help Desk (web)
- **Organization:** Fenil *(rules are organization-scoped)*
- **Artifacts:** Ticket Rules, sample tickets, internal notes, public updates, closure summaries

---

## Automation Rules Implemented
### 1) Password / Account Rule
- **IF:** Summary contains `password` AND Organization is `Fenil`
- **THEN:** Set **Priority = High**

### 2) Printer Rule
- **IF (Any):** Summary contains `printer` OR `print` AND Organization is `Fenil`
- **THEN:** Set **Priority = Medium**

---

## Test Tickets (Evidence)
- **Ticket #3:** *Printer not printing - urgent*  
  - Priority auto-set to **Medium**
  - Internal technician note added
  - Public response added
  - Closed with resolution summary

- **Ticket #4:** *Password reset needed - locked out*  
  - Priority auto-set to **High**
  - Internal technician note added
  - Public response added
  - Closed with resolution summary

> Screenshots are included as proof of configuration and workflow.

---

## Repository Structure
