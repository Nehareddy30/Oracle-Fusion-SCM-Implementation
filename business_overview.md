# Oracle Fusion SCM Implementation - ShopNest INC.

## 🔹 Project 1: ERP System Design for an E-Commerce Company

### Module: Inventory & Procurement

**Our fictional company:** **ShopNest Inc.** — a mid-size e-commerce company (think Amazon scale, smaller)

We'll build this project in **5 Steps:**

| Step | What we'll create |
| --- | --- |
| **Step 1** | Business Overview & Problem Statement |
| **Step 2** | Business Process Flow (Procure-to-Pay) |
| **Step 3** | ERP Module Design (Data + Entities) |
| **Step 4** | Gap Analysis & ERP Recommendations |
| **Step 5** | GitHub README + LinkedIn Post |

---

## 1 Business Overview & Problem Statement

Here's the story of ShopNest Inc. — read and understand this, as it forms the foundation of your entire project.

---

### 🏢 Company: ShopNest Inc.

**Industry:** E-Commerce (B2C)
**Size:** 500 employees, 3 warehouses (New York, Chicago, Los Angeles)
**Annual Revenue:** $120M

**What they sell:** Electronics, Home Appliances, Fashion — across 10,000+ SKUs

---

### ❌ Current Problems (Before ERP)

ShopNest currently manages everything manually or through disconnected spreadsheets:

- **No real-time inventory visibility** — warehouse teams don't know stock levels across all 3 locations
- **Manual Purchase Orders** — procurement team raises POs via email, leading to delays and errors
- **Supplier management is chaotic** — no centralized supplier database, duplicate vendors exist
- **Stockouts & Overstocking** — no reorder point system, leading to lost sales or excess inventory
- **No audit trail** — can't track who approved what purchase, compliance risk

---

### ✅ Goal: Implement Oracle Fusion Cloud SCM

Implement **Oracle Fusion Inventory Management** and **Oracle Fusion Procurement** to:

- Centralize inventory across all 3 warehouses
- Automate the Procure-to-Pay (P2P) process
- Set reorder points and automate purchase requisitions
- Build a supplier portal for streamlined communication
- Enable real-time dashboards for management

## 2. Business Process Flow

ShopNest Inc. follows an 8-step Procure-to-Pay (P2P) process implemented on Oracle Fusion Cloud. The process begins with automated low-stock detection in Oracle Inventory Management and ends with supplier payment via Oracle Fusion Financials AP module. A critical control point is the 3-way match (Step 7), where the system automatically validates the Purchase Order, Goods Receipt Note, and Supplier Invoice before releasing payment.

### 3. ERP Module Design - Data Entities

The ShopNest Inventory & Procurement module is designed around 6 core entities: Supplier, Item, Inventory, Purchase Requisition, Purchase Order, and Goods Receipt. The data model enforces a one-to-many relationship between Suppliers and Purchase Orders, and between Purchase Orders and Goods Receipts to support partial deliveries. The 3-way match control is enforced at the database level by linking PO, GRN, and Invoice records before payment processing.

#### 4. Gap Analysis & Recommendations

A comprehensive gap analysis was conducted comparing ShopNest Inc.'s current manual processes against Oracle Fusion Cloud SCM capabilities. Six key gaps were identified across inventory management, procurement, and finance. The highest priority gaps — real-time inventory visibility, reorder automation, and structured purchase order management — are recommended for Phase 1 implementation. Oracle Fusion Inventory Management, Purchasing, and Payables modules are the core solution components. Estimated procurement cost reduction is 18–24% post-implementation over 12 months.
