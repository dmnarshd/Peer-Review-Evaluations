# Peer Review Evaluations Database

## Overview
A comprehensive Microsoft Access database system designed to manage faculty peer review evaluations at PMU. The system allows visitors to anonymously schedule evaluation visits and rate faculty on teaching method, classroom management, and student engagement. It includes a user-friendly dashboard with forms, reports, and automated status tracking.

## Tools Used
- Microsoft Access (database, forms, reports)
- SQL (queries, action queries)
- VBA/Macros (form automation)

## Features
- **Quick Access Menu** — central dashboard for all operations
- **Schedule New Visit** — assign visitors to faculty and courses with dates
- **Submit Evaluation** — rate faculty on 3 criteria with automatic average calculation
- **Anonymous Visitor Data** — visitor identities are hidden in all reports
- **Automated Status Tracking** — visits marked "Pending" or "Completed" via SQL action query
- **Navigation Menu** — tabbed interface to browse all data, reports, and forms
- **Pre-built Queries** — frequently asked questions answered with one click
- **Reports** — view all visits, completed visits, and faculty rating summaries

## System Structure

### Forms
- `frmQuickAccess` — main menu
- `frmScheduleVisit` — schedule new evaluation visits
- `frmSubmitEvaluation` — enter ratings and comments
- `frmNavigation` — full navigation menu

### Queries
- Update Status (action query)
- Visits completed count
- Average ratings per faculty
- Visits scheduled count
- Ratings for specific faculty
- Visits per faculty

### Reports
- All Visits Report
- Completed Visits Report
- Faculty Rating Summary

## What I Learned
- Designing relational databases with multiple related tables
- Building forms and navigation menus in MS Access
- Writing SQL action queries to automate status updates
- Creating reports for data analysis
- Managing user anonymity and data privacy in database design

## Screenshots

### Quick Access Menu
![Quick Access Menu](screenshots/quick_access_menu.png)

### Schedule New Visit
![Schedule New Visit](screenshots/schedule_visit.png)

### Submit Evaluation
![Submit Evaluation](screenshots/submit_evaluation.png)

### Navigation Menu
![Navigation Menu](screenshots/navigation_menu.png)

### Frequently Asked Queries
![FAQ Queries](screenshots/faq_queries.png)

## Files
- `Group 7 Manual.pdf` — Full user manual with setup and usage instructions
- `peer_review.accdb` — Microsoft Access database file (if included)
- `screenshots/` — System screenshots

## Course
MISY 3331 — Advanced Database Systems
Prince Mohammad Bin Fahd University
