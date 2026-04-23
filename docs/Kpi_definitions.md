# KPI Definitions

This document defines the key performance indicators (KPIs) used
in the End-to-End Payment Analytics Pipeline.

---

## Total Transactions
**Definition:** Total number of payment transactions processed.

**Metric:**

COUNT(transaction_id)

**Business Meaning:**
Represents transaction volume and overall activity level.

---

## Total Amount
**Definition:** Sum of transaction amounts.

**Metric:**

SUM(amount)
**Business Meaning:**
Represents processed payment volume.

---

## Approval Rate
**Definition:** Ratio of approved transactions over total transactions.

**Formula:**

Approved Transactions / Total Transactions

**Business Meaning:**
Measures payment performance and customer friction.
Low values may indicate issuer issues, fraud rules or configuration problems.

---

## Average Ticket Size
**Definition:** Average transaction amount.

**Formula:**

Total Amount / Total Transactions

**Business Meaning:**
Helps understand consumer spending behavior.