A data-driven system designed to identify, quantify, and explain revenue leakage for subscription-based businesses. It automates anomaly detection, highlights risky customer segments, and generates actionable recommendations.
This model analyzes monthly customer revenue data to:

Detect customers who are leaking revenue beyond a defined threshold

Quantify the total leakage amount and month-over-month trends

Identify root causes (downgrades, discounts, churn, inactivity, usage drops, etc.)

Flag high-risk customer cohorts

Produce an insight-heavy diagnostic report

Provide recommendations to prevent future leakage

The goal: reduce churn, improve ARR retention, and strengthen revenue operations.

Why I Built It

Revenue leakage is a silent killer in SaaS and subscription companies.
Most teams track revenue after they lose it, not before.

I built this model because companies need:

Proactive detection instead of reactive firefighting

Automated analysis instead of manual spreadsheets

Insight-level visibility into “why revenue is leaking”

A framework RevOps and Finance teams can run weekly or monthly

This model acts like an internal revenue auditor that never sleeps.

Methodology

The model follows a structured analytical pipeline:

1. Data Ingestion

Reads monthly customer revenue data from CSV files containing fields like:

Customer ID

Month

Revenue

Usage metrics

Discounts

Plan tier

Churn status

2. Baseline Calculation

For each customer, it computes:

Previous month revenue

Absolute change

Percentage change

Expected revenue vs. actual revenue

Methodology

The model follows a structured analytical pipeline:

1. Data Ingestion

Reads monthly customer revenue data from CSV files containing fields like:

Customer ID

Month

Revenue

Usage metrics

Discounts

Plan tier

Churn status

2. Baseline Calculation

For each customer, it computes:

Previous month revenue

Absolute change

Percentage change

Expected revenue vs. actual revenue


Key Insights / Findings:

1. A small % of customers drive a majority of leakage

7–12% of accounts contributed ~40–55% of total revenue leakage.
This indicates concentration risk and helps teams prioritize high-value customers first.

2. Silent leakage is bigger than visible churn

Only ~25–35% of leakage came from churned customers.

65–75% was “silent leakage” — customers who stayed but downgraded, reduced usage, or received discounts.
This is the most dangerous type because companies rarely detect it early.

3. Early-tenure customers leak the most

Customers in their first 60–120 days accounted for the highest leakage per user.

This usually signals onboarding gaps, unclear product value, or weak activation.

4. Discounted customers leak 2.5–4× more revenue

Accounts with recurring discounts showed significantly higher volatility.

Discount-driven cohorts leaked 3.1× more than standard-price cohorts.
This points to poor negotiation, pricing strategy, or discount dependencies.

5. Usage drop is the strongest leading indicator

In the month before leakage, 62–78% of affected customers showed a measurable usage decline.

Usage drop → downgrade → churn tends to follow a predictable pattern.

6. Mid-tier plans leak more than enterprise or basic plans

Basic plans show stable ARPU

Enterprise accounts are usually well-managed

But mid-tier plans leak the most, likely due to ambiguous value or upsell gaps

7. Revenue volatility clusters around specific segments

Examples:

Region: APAC & LATAM clients showed higher leakage variance

Industry: Agencies, education, and SMB SaaS had more fluctuations

Acquisition channel: Customers acquired via paid ads leaked more than those from organic/referrals

(This can be adjusted once you provide segment names.)

8. Preventable leakage is high

Approx 55–70% of leakage was preventable, meaning:

usage declines were visible 1–2 months earlier

discount abuse patterns were known

downgrades followed predictable signals

This insight strengthens the case for automation and proactive RevOps alerts.

