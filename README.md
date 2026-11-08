# 🧭 Onboarding Command Center

**One dashboard, one checklist, one new-hire form for every hire type.**
Built with **Power Apps · SharePoint Lists · Power Automate**. Live and in pilot use.

### 👉 [Try the live demo](https://sylim-analytics.github.io/onboarding-command-center/)
> Interactive mockup with fictional data. No sign-in needed. Its Notification Timeline tab simulates the messages; the demo sends nothing.

## The Problem
Onboarding lived in 6 places: notice emails, a separate Microsoft Form, Planner (capped at 20 tasks), OneNote checklists, bookmarked sites, and confirmation emails. Four hire types (employee, contractor, intern, transfer) needed different steps, and no one could see overall progress.

## The Solution
Enter a hire once. The app builds everything else.

| Component | Role |
|---|---|
| **Task Matrix** | Rule engine: tasks by hire type, phase (pre/post arrival), and owner (supervisor/admin) |
| **Power Automate** | Pings the admin when an HR or contractor onboarding email arrives; creates each hire's checklist and New Hire form; notifies the supervisor; sends early, final, and follow-up reminders only while supervisor tasks are still open |
| **Power Apps** | Dashboard (pipeline, hires by type, avg. % complete), active hires, checklist with links and emails built in |

**Key idea:** change a rule once, and every future checklist follows.

## Impact
- Replaced Planner, OneNote, and a separate Form with **one app**
- Removed the 20-task limit with role-based checklists for **4 hire types**
- Gave supervisors and admins **live progress** for every hire
- Added **automatic pings and reminders** (admin ping on each new-hire email; early, final, and follow-up reminders to the supervisor) that fire only while tasks are open

## Skills
Data modeling · Workflow automation · Power Apps · Process redesign · Prototyping (HTML/CSS/JS) · Pilot and governance planning
