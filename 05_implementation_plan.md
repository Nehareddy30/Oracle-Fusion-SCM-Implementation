# Oracle Fusion SCM — Implementation Plan
## ShopNest Inc. | 6-Month Phased Rollout

---

## Project Overview

| Item | Details |
|------|---------|
| Company | ShopNest Inc. |
| Project | Oracle Fusion Cloud SCM Implementation |
| Modules | Inventory Management, Purchasing, Supplier Portal, Payables, OAC |
| Duration | 6 months |
| Warehouses | New York · Chicago · Los Angeles |
| Go-Live Strategy | Phased rollout — Phase 1 → 2 → 3 |

---

## Phase 1 — Foundation (Months 1–2)

**Objective:** Establish real-time inventory visibility and structured procurement workflows across all 3 warehouses.

### Scope
- Deploy Oracle Inventory Management for live stock tracking (NY, CHI, LA)
- Configure automated reorder point triggers for top 500 SKUs
- Set up structured Purchase Order creation with multi-level approval workflow
- Data migration: migrate item master, warehouse locations, and opening stock balances
- User training: warehouse managers and procurement team

### Oracle Modules
- Oracle Inventory Management Cloud
- Oracle Purchasing Cloud
- Oracle Approvals Management

### Deliverables
- [ ] Inventory Management configuration document
- [ ] Reorder point rules configured for top 500 SKUs
- [ ] PO approval workflow live (3-level: Requestor → Manager → Finance)
- [ ] Training completed for 45 warehouse and procurement users
- [ ] UAT sign-off for Phase 1

### Success Criteria
- Real-time inventory dashboard operational across all 3 locations
- Zero manual POs raised via email
- Reorder automation active and tested

---

## Phase 2 — Procurement (Months 3–4)

**Objective:** Centralize supplier management and automate invoice processing via 3-way match.

### Scope
- Launch Oracle Supplier Portal — onboard all active vendors
- Deduplicate supplier master (currently 34 duplicate records identified)
- Configure automated 3-way match: PO + Goods Receipt Note + Supplier Invoice
- Automate AP payment runs with exception-only manual review
- Integrate GRN creation with warehouse goods receiving process

### Oracle Modules
- Oracle Supplier Portal Cloud
- Oracle Payables Cloud
- Oracle AP Automation

### Deliverables
- [ ] Supplier portal live — all active suppliers onboarded
- [ ] Supplier master cleansed (zero duplicates)
- [ ] 3-way match configured and tested
- [ ] Payment automation active
- [ ] UAT sign-off for Phase 2

### Success Criteria
- All suppliers transacting via portal
- 3-way match auto-processing >90% of invoices
- Payment error rate reduced to <2%

---

## Phase 3 — Analytics & Optimization (Months 5–6)

**Objective:** Deploy management dashboards and complete full system optimization and sign-off.

### Scope
- Deploy Oracle Analytics Cloud (OAC) procurement dashboards
- Build KPI reports: inventory fill rate, PO cycle time, supplier on-time delivery
- Create executive-level monthly procurement spend report
- Conduct post-go-live performance review against baseline KPIs
- Final UAT sign-off and project closure

### Oracle Modules
- Oracle Analytics Cloud (OAC)
- Oracle SCM Reporting
- Oracle BI Publisher

### Deliverables
- [ ] Executive procurement dashboard live in OAC
- [ ] All 6 KPIs tracked and baselined (see KPI Tracker tab in gap analysis)
- [ ] Monthly reporting template finalized
- [ ] Post-implementation review document
- [ ] Full project UAT sign-off

### Success Criteria
- Executive dashboard available to leadership team
- All KPIs meeting or exceeding targets
- Procurement cost reduction of 18–24% evidenced

---

## Risk Register

| Risk | Likelihood | Impact | Mitigation |
|------|-----------|--------|-----------|
| Data migration quality issues (item master, suppliers) | High | High | Conduct data cleanse in Month 1 before go-live |
| User adoption resistance | Medium | High | Early training, change management plan, super-user champions |
| Supplier portal low adoption | Medium | Medium | Dedicated supplier onboarding team in Phase 2 |
| Integration delays with 3PL warehouse systems | Low | High | Early technical discovery in Month 1 |
| Scope creep into Finance module | Low | Medium | Strict change control process, Phase 1–3 boundaries enforced |

---

## Team Structure

| Role | Responsibility |
|------|---------------|
| ERP Project Manager | Overall delivery, stakeholder management, timeline |
| Oracle SCM Functional Consultant | Module configuration, business process design |
| Data Migration Lead | Item master, supplier, and inventory data cleanse & migration |
| Technical Consultant | Integrations, Oracle environment setup |
| Business Analyst | Requirements gathering, UAT coordination, documentation |
| Change Manager | Training, user adoption, communications |

---

## Key Milestones

| Milestone | Target Date |
|-----------|------------|
| Project kickoff & discovery complete | End of Month 1 |
| Phase 1 UAT sign-off | End of Month 2 |
| Phase 2 UAT sign-off | End of Month 4 |
| Phase 3 UAT sign-off | End of Month 6 |
| Full go-live & project closure | Month 6 |

---

*Prepared as part of Oracle Fusion SCM Portfolio Project — ShopNest Inc. case study.*
