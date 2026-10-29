# Sandy Foods Pvt. Ltd. | SAP S/4HANA Materials Management (MM)

## Project Overview

A hands-on SAP S/4HANA MM implementation and business-process practice project based on a fictional food manufacturing company, Sandy Foods Pvt. Ltd. The project focuses on enterprise structure, master data, procurement, inventory management, material planning, supplier collaboration, and inter-plant stock movements.

The objective was to understand how SAP MM supports procurement and inventory operations across multiple plants, from purchasing and goods receipt to invoice verification and stock monitoring.

## Business Scenario

Sandy Foods operates manufacturing and distribution activities across Mysuru and Bengaluru. The project models procurement of raw materials and packaging supplies, supplier coordination, inventory replenishment, import purchasing, and stock transfers between plants.

## Key SAP MM Activities

### 1. Enterprise Structure and Organizational Setup
- Configured the company structure for Sandy Foods, including company code, plants, storage locations, and purchasing organization.
- Established purchasing groups to support different procurement categories.
- Set up the controlling area and plant assignments for Material Ledger.

### 2. Material and Supplier Master Data
- Created and maintained material master records for raw materials, packaging materials, and finished products.
- Maintained supplier master data for domestic and international procurement scenarios.
- Worked with purchasing information records and source lists to support procurement source selection.

### 3. Procure-to-Pay (P2P) Process
- Created purchase orders for raw materials and packaging supplies.
- Practiced purchase order pricing, discounts, and purchasing partner determination.
- Posted goods receipts with reference to purchase orders.
- Completed Logistics Invoice Verification (MIRO) for a domestic procurement scenario.

### 4. Inventory Management and Material Planning
- Executed goods movements and reviewed stock using SAP inventory transactions.
- Tested reorder-point planning using MRP type VB.
- Executed an MRP planning run and verified automatic purchase requisition creation when stock fell below the configured reorder point.
- Practiced a stock transport order between the Mysuru and Bengaluru plants, including goods issue and goods receipt.

### 5. Import Procurement and Pricing
- Created an international purchase order using a foreign supplier and EUR currency.
- Practiced freight and additional pricing conditions to understand their impact on the purchase order value.
- Reviewed the resulting pricing calculation in the purchase order.

### 6. Split Valuation
- Configured and practiced split valuation for the relevant material and valuation area.
- Maintained separate valuation types for external procurement and in-house production.
- Tested the external-procurement valuation type, MRBLVL1, and verified the resulting stock in SAP.

### 7. SAP Fiori
- Accessed SAP Fiori Launchpad and displayed material details for a Sandy Foods finished product.

## Project Evidence

The repository contains screenshots captured during hands-on practice in the SAP S/4HANA training environment.

- **Enterprise Structure/** — Organizational structure and plant setup
- **Controlling/** — Controlling area and Material Ledger configuration
- **Master Data/** — Material and supplier data, purchasing, inventory, MRP, invoice verification, import pricing, split valuation, stock transfers, and Fiori material display

## SAP Skills Practiced

- SAP S/4HANA Materials Management (MM)
- Procure-to-Pay (P2P)
- Material Master and Supplier Master
- Purchasing and Source Determination
- Purchase Order Pricing and Conditions
- Goods Receipt and Invoice Verification
- Inventory Management and Stock Transfers
- Reorder-Point Planning (MRP Type VB)
- Split Valuation
- SAP GUI and SAP Fiori Navigation

## Tools and Environment

- SAP S/4HANA training system
- SAP GUI
- SAP Fiori Launchpad
- SAP MM transaction codes relevant to the scenarios documented in this repository

## Disclaimer
## Connect with Me

- **LinkedIn:** https://www.linkedin.com/in/soundarya-mr-962b61374
- **GitHub:** [Sandy Foods SAP S/4HANA MM Project](./)

Sandy Foods Pvt. Ltd. is a fictional company created for learning and portfolio demonstration. All activities documented here were performed in a training environment.
