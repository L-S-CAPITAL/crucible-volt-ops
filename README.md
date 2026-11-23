# CRUCIBLE // VOLT-OPS (SYS-VER 4.2)
### Tactical Electrical Service Account Management & Field Margin Sentinel

> **Live System:** [https://l-s-capital.github.io/crucible-volt-ops/](https://l-s-capital.github.io/crucible-volt-ops/)  
> **Target Role:** Electrical Service Account Manager ($125,000–$140,000 + Super)  
> **Sectors:** Commercial Facilities, Industrial Infrastructure, Critical Systems  
> **Architect:** Tobias Hall (L-S CAPITAL / UEE22020 Graduate)

---

## 1. System Overview & The Core Operational Problem

In mid-tier and Tier-1 commercial electrical service operations, Account Managers run multimillion-dollar client portfolios across commercial office towers, industrial manufacturing facilities, and hospital/institutional sites.

Most contracting firms run legacy ERPs (SimPRO, AroFlo, Jobpac, Pronto). While these tools log invoices, they have five critical operational blindspots that destroy profitability:

1. **Mid-Flight Margin Drift:** Account Managers only find out a job lost money *two weeks after it finishes* when the post-mortem invoice is drafted.
2. **Technician Non-Billable Leakage:** Field electricians waiting for site inductions, keys, or security access burn billable hours ($95–$140/hr in lost revenue).
3. **Lazy Closeouts & AS/NZS 3000 Exposure:** Technicians writing one-line notes (*"repaired light, all good"*) delays billing by days and leaves the contractor exposed to compliance liabilities.
4. **Copper & Cable Volatility in Quoting:** Quoting fixed-price switchboard or riser jobs without live commodity hedging leads to margin erosion when copper spot prices surge.
5. **Client Contact Churn:** When a commercial Facility Manager leaves CBRE or JLL for Dexus or Knight Frank, contractors without a system lose the account.

**CRUCIBLE // VOLT-OPS** was engineered as a single-pane operational cockpit to solve these exact five bottlenecks in real-time.

---

## 2. The Five Tactical Modules

### Module 1: Mid-Flight Margin & Labour Burn Sentinel (`#sentinel`)
* **Real-time Cost Tracking:** Tracks active jobs (e.g. *Dexus 180 Ann St MSB CT Metering*, *Port of Brisbane Cold Storage VSD Replacement*).
* **Early Slippage Warning:** Automatically flags when a technician hits 70% or 90% of quoted hours while work is still in progress.
* **1-Click Mid-Flight Variation Injector:** Calculates the exact additional labour and material cost of a site obstruction and drafts a formal client variation request before the tech leaves site, protecting the 38% target gross margin.

### Module 2: Technician Utilization & Zero-Downtime Dispatch Board (`#dispatch`)
* **Fleet Live Status:** Monitors field techs (Senior Sparkies, Dual-Trade Techs, Apprentices) across Brisbane.
* **Target Utilization:** Tracks daily Billable vs. Non-Billable time against an 85%+ KPI target.
* **"Downtime Absorber" Quick-Reroute:** When a tech is blocked by a site security delay, 1 click reroutes them to an adjacent statutory compliance task (e.g., nearby RCD testing), saving hours of dead time.

### Module 3: AS/NZS 3000 QA Auditor & Note Closeout Gate (`#auditor`)
* **Pre-Invoice Clearance:** Audits technician job notes before pushing to Finance.
* **Mandatory Testing Verification:**
  * Insulation Resistance (Megger > 1 MΩ)
  * Earth Continuity (< 0.5 Ω)
  * RCD Trip Times (< 300 ms)
  * LOTO & Switchboard Isolation Photo Verification
* **Training Needs Identification:** Scores technicians to inform quarterly reviews.

### Module 4: Quote & Copper-Indexed Margin Calculator (`#quoter`)
* **Live Estimator:** Combines labour multipliers (Senior Sparky $125/hr, Apprentice $65/hr) with cable run sizing.
* **Copper Indexing (Crucible Engine):** Automatically adjusts cable price buffers based on live London Metal Exchange (LME) copper spot data ($9,240 USD/t).
* **Target GP Gauge:** Enforces healthy profit margins (39.2% target) and generates client-ready proposals with 72-hour automated follow-up reminders.

### Module 5: Client Health, Statutory Recurrence & Contact Mover Radar (`#accounts`)
* **Statutory Compliance Watchdog:** Auto-tracks recurring mandatory inspection cycles across commercial towers and industrial sites:
  * AS/NZS 2293 Emergency Light 90-Min Discharge (6-monthly)
  * AS/NZS 3760 RCD Testing (6-monthly)
  * AS/NZS 3000 / Insurance Annual Thermographic Scanning
* **Contact Mover Radar:** Detects when key facility managers switch companies (e.g. Sarah Jenkins moving to Dexus Waterfront) and pre-drafts warm transition outreach proposals to capture the new building portfolio.

---

## 3. How to Run & Deploy

### Quick Local Preview
Simply double-click `index.html` to open it in any modern browser (Chrome, Edge, Firefox, Brave):
```
file:///C:/Users/tobia/.gemini/antigravity/scratch/voltflow-am/index.html
```

Or run via any local server:
```bash
cd C:\Users\tobia\.gemini\antigravity\scratch\voltflow-am
npx serve .
# or
python3 -m http.server 8080
```

### Deploy to GitHub Pages / Vercel
You can create a repository under `L-S-CAPITAL/voltflow` and enable GitHub Pages, giving you an instant live URL (e.g., `https://l-s-capital.github.io/voltflow/`) to include in your application to Job Capital.

---

## 4. Application Integration & Interview Pitch

### Cover Letter Snippet:
> *"Unlike candidates who only offer general talk about client relationships, I bring a unique hybrid advantage: hands-on electrotechnology trade foundation (UEE22020), deep familiarity with AS/NZS 3000 standards, and a systems engineering background. To demonstrate how I actively manage technician utilization, eliminate non-billable downtime, and protect job margins in real-time rather than relying solely on post-job reviews, I engineered a working operational prototype tailored specifically to this role: [CRUCIBLE // VOLT-OPS Live Demo]."*

### Interview Demo Strategy:
When meeting the General Manager and Job Capital recruiter:
1. Open the dashboard on your laptop or iPad in dark mode.
2. Show them **Module 1 (Margin Sentinel)**: Explain how you prevent margin slippage *mid-flight* by issuing variations while the technician is still on the riser.
3. Show them **Module 3 (QA Auditor)**: Explain how you enforce AS/NZS 3000 testing data before jobs are handed to Finance, cutting client billing disputes to near-zero.
4. Show them **Module 5 (Contact Mover Radar)**: Show how you retain institutional client relationships and capture new building portfolios when Facility Managers change firms.
