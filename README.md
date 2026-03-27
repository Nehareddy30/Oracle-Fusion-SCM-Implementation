
# Oracle Fusion SCM Implementation — ShopNest Inc.

![Oracle Fusion](https://img.shields.io/badge/Oracle-Fusion_Cloud_SCM-blue)
![ERP](https://img.shields.io/badge/ERP-Implementation-green)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

## Overview
This project documents the end-to-end ERP system design and Oracle Fusion Cloud SCM implementation plan for **ShopNest Inc.**, a fictional mid-size e-commerce company with $120M annual revenue and 3 warehouses across the US.

## Business Problem
ShopNest operated with disconnected spreadsheets, resulting in:
- No real-time inventory visibility across 3 warehouses
- Manual email-based PO process with no audit trail
- Frequent stockouts and overstocking
- No centralized supplier database
- Manual invoice verification causing payment errors

## Solution
Designed an Oracle Fusion Cloud SCM implementation covering:
- **Oracle Inventory Management** — real-time stock, automated reorder triggers
- **Oracle Purchasing** — structured POs, approval workflows, audit logs
- **Oracle Supplier Portal** — centralized vendor registry
- **Oracle Payables** — automated 3-way match (PO + GRN + Invoice)
- **Oracle Analytics Cloud** — procurement dashboards and KPIs

## Project Deliverables
| File | Description |
|------|-------------|
| `01_business_overview.md` | Company profile and problem statement |
| `02_p2p_process_flow.png` | 8-step Procure-to-Pay flow diagram |
| `03_erd_diagram.png` | Entity Relationship Diagram |
| `04_gap_analysis.xlsx` | AS-IS vs TO-BE gap analysis |
| `05_implementation_plan.md` | 6-month phased rollout plan |

## Key ERP Concepts Demonstrated
- Procure-to-Pay (P2P) process design
- 3-way match control (PO + GRN + Invoice)
- ERP data modeling and entity relationships
- AS-IS / TO-BE gap analysis methodology
- Oracle Fusion Cloud SCM module mapping

## Implementation Timeline
| Phase | Duration | Scope |
|-------|----------|-------|
| Phase 1 | Months 1-2 | Inventory, reorder automation, PO workflows |
| Phase 2 | Months 3-4 | Supplier portal, 3-way match, Payables |
| Phase 3 | Months 5-6 | OAC dashboards, reporting, optimization |

## Tools & Technologies
Oracle Fusion Cloud SCM · Oracle OAC · SQL · ERD Design · Lucidchart · Excel

Implementation timeline
Phase	Duration	Scope
Phase 1	Months 1–2	Inventory visibility, reorder automation, PO workflows
Phase 2	Months 3–4	Supplier portal, 3-way match, Payables automation
Phase 3	Months 5–6	OAC dashboards, KPI reporting, optimization

Author
Built as a portfolio project to demonstrate Oracle Fusion Cloud SCM knowledge and ERP implementation methodology. Connect on [LinkedIn](www.linkedin.com/in/neha-pannala)).
