# README.md
# Top 3 IT Incidents (AKA “Why I’m An Ops Beast”)

> **TL;DR**  
> I built three bullet-proof SOPs to nuke your worst IT headaches—FAST.  
> Copy. Paste. Win.

---

## 0. Why You Should Care
- **MFA dies?** Sales reps miss money.  
- **VPN pukes?** Engineers can’t ship code.  
- **Printer offline?** Finance can’t cut checks.  
Mess with cash flow → Nobody’s happy. I fixed that.

## 1. What’s Inside (Swipe-File)
| Folder | What You Get | Why It Matters |
| --- | --- | --- |
| `SOP_MFA_Not_Working.md` | 6-step rescue plan + escalation tree | Saves deals in <30 min |
| `SOP_VPN_Fails.md` | 7-step tunnel triage | Keeps dev velocity 🔥 |
| `SOP_Printer_Offline.md` | 8-step printer CPR | Finance prints $$ again |
| `Personas/*` | 3 user backstories | Empathy = faster fixes |
| `Policy_MFA_Backup_Code.md` | Zero-downtime MFA policy | Aligns w/ NIST 800-63B |
| `Scripts/VPN_Health_Check.ps1` | 60-second health check | Catch outages before users do |
| `SLA_Priority.md` | P1‒P4 response matrix | ITSM street cred |
| `Incident_Communication_Templates.md` | Email + Slack scripts | Stop writing from scratch |
| `Post_Incident_Review.md` | Drop-in PIR doc | Learn → improve → repeat |
| `Change_Request_Form.md` | Change gate template | No cowboy fixes |
| `Compliance_Notes.md` | NIST / CIS / ISO cheatsheet | Earn the auditor’s nod |
| `Printer_Network_Map.md` | ASCII network map | Visual: see, solve, done |

> **Screenshots & videos**  
> Anywhere you see `[INSERT SCREENSHOT]` or `[YOUTUBE LINK]`—drop your real stuff. Recruiters love receipts.

---

## 2. Fast Demo (Tabletop Style)
1. **Pick a pain** (`MFA`, `VPN`, or `Printer`).  
2. Open the matching SOP.  
3. Role-play the user + the IT hero.  
4. Follow the bullets—time how fast you “fix” it.  
5. Show the SLA doc → prove you hit the clock.  
6. Close with the Post-Incident Review.  
👉 That’s how you sell “I run tight ops” in an interview.

---

## 3. Architecture at a Glance
```mermaid
flowchart LR
  User -->|“Help!”| Triage --> Decide
  Decide -->|MFA| MFA --> Close
  Decide -->|VPN| VPN --> Close
  Decide -->|Printer| PR --> Close
  Close --> Review
