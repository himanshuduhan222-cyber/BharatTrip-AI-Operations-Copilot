# ✈️ BharatTrip AI Operations & Refund Reconciliation Copilot

An enterprise-grade AI Operations prototype built for TravClan to eliminate financial leakage, automate cross-ledger reconciliation, and streamline customer refund workflows.

## 🚀 Business Impact & Objective
* **Problem Addressed:** Addressed a 226% surge in escalations (149 active cases) and ₹18.62 Lakhs in financial losses driven by "false closures" (where support tickets were marked closed before finance settlement).
* **Core Goal:** Achieve zero-headcount operational efficiency through automated reconciliation, dark-matter unstructured message parsing, and intelligent ticket routing.

---

## 🛠️ System Architecture & Modules

1. **Ticket Reconciliation Lookup (Module 1):**
   * Cross-examines support claims against finance ledgers in real-time.
   * Features an AI Copilot recommendation engine that automatically flags status discrepancies (e.g., Support marked "Closed" vs. Finance marked "Pending").

2. **Informal Intake AI Parser (Module 2):**
   * Parses unstructured customer complaints and chats (WhatsApp, email) to automatically extract structured payloads (Ticket ID, route, urgency level, sentiment).

3. **Operational Discrepancy Dashboard (Module 3):**
   * Provides system-wide operational metrics, tracking escalation surges, data volumes, and consolidated ledger views across `Support_Tracker` and `Finance_Tracker` sheets.

---

## ⚙️ Tech Stack
* **Framework:** Streamlit
* **Data Processing:** Pandas, OpenPyXL
* **Runtime:** Python 3.15

---

## 🚀 Local Installation & Execution

1. Clone or place the project files in your working directory:
   ```bash
   cd BharatTrip_AI_Ops