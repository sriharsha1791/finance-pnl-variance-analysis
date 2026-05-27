# Data Generation Plan

## Goal

Generate realistic SaaS ERP transaction dataset.

Target:

100,000 to 150,000+ rows

---

## Dataset Grain

1 row = 1 customer transaction

---

## Generation Steps

1.

Generate Customer Master

Columns:

customer_id

customer_name

region

customer_segment

channel

join_date

subscription_type

---

2.

Generate Transaction Dates

Timeline:

Jan 2025 → Dec 2026

Seasonality:

Q1 weak

Q2 stable

Q3 growth

Q4 strongest

---

3.

Generate Product Transactions

Products:

Basic

Pro

Enterprise

Include:

quantity

price

discount

revenue

---

4.

Generate Budget Metrics

budget_qty

budget_price

budget_revenue

Purpose:

Variance analysis

---

5.

Generate Cost Metrics

cogs

cloud_cost

labor_cost

marketing_cost

support_cost

returns

refund_amount

---

6.

Generate Profitability Metrics

gross_profit

gross_margin_pct

ebitda

net_profit

profit_margin_pct

---

7.

Inject Business Problems

APAC:

Weak profitability

Higher discounts

Enterprise decline

---

Enterprise:

Customer reduction in 2026

Margin erosion

---

Basic:

Higher volume growth

Lower margins

---

8.

Generate Variance Metrics

variance_amount

variance_pct

price_effect

volume_effect

mix_effect

---

9.

Generate Business Flags

is_apac_issue

is_discounted

is_enterprise_customer

is_q4

is_high_margin

is_renewal

---

10.

Export Final CSV

Output:

simulated_transactions.csv

Target Size:

100k to 150k+ rows
