# sap-mm-procure-to-pay
SAP MM Procure to Pay process covering Purchase Requisition, Purchase Order, Goods Receipt, Invoice Verification and Material Master.
# SAP MM - Procure to Pay (P2P) Process

## 📌 Project Overview

This project demonstrates my basic understanding of the SAP Materials Management (SAP MM) procurement process.

The project focuses on the Procure to Pay (P2P) cycle, starting from creating a Purchase Requisition and ending with Invoice Verification.

## 🎯 Objective

The objective of this project is to understand and document the basic SAP MM procurement process and commonly used SAP MM transactions.

## 🔄 Procure to Pay Process

Purchase Requisition
        ↓
Purchase Order
        ↓
Goods Receipt
        ↓
Invoice Verification

## 🛠️ SAP MM Transactions Covered

| Transaction | Purpose |
|---|---|
| ME51N | Create Purchase Requisition |
| ME21N | Create Purchase Order |
| MIGO | Goods Receipt / Goods Movement |
| MIRO | Invoice Verification |
| MM01 | Create Material Master |

## 📚 Process Details

### 1. Purchase Requisition - ME51N

A Purchase Requisition is an internal request to procure materials or services.

Basic information includes:

- Material
- Quantity
- Plant
- Delivery date
- Purchasing group

### 2. Purchase Order - ME21N

A Purchase Order is created to formally request materials or services from a vendor.

Basic information includes:

- Vendor
- Material
- Quantity
- Price
- Delivery date
- Plant

### 3. Goods Receipt - MIGO

Goods Receipt is performed when the ordered material is received from the vendor.

The process includes:

- Purchase Order reference
- Material quantity
- Plant
- Storage location
- Movement type

### 4. Invoice Verification - MIRO

Invoice Verification is used to verify the vendor invoice against the purchase order and goods receipt.

This is an important part of the procurement process.

### 5. Material Master - MM01

Material Master contains important information about materials used by an organization.

Examples include:

- Material description
- Material type
- Industry sector
- Plant information
- Storage information
- Purchasing information

## 🔁 Complete P2P Flow

```text
Material Requirement
        ↓
Purchase Requisition
       ME51N
        ↓
Purchase Order
       ME21N
        ↓
Goods Receipt
        MIGO
        ↓
Invoice Verification
        MIRO
        ↓
Payment Process
