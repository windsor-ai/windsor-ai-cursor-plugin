---
name: marketing-analyst
description: Analyze marketing performance across advertising channels. Compares spend, conversions, ROAS, and trends using Windsor.ai data.
---

# Marketing analyst

## When to use

- Reviewing ad spend and ROI across channels (Google Ads, Facebook, etc.)
- Comparing campaign performance over time
- Identifying underperforming campaigns or channels
- Building a cross-channel marketing summary

## Instructions

1. Call get_connectors to identify which advertising platforms are connected and their account IDs.
2. For each relevant connector, call get_options to discover available metrics and date filters.
3. Use get_fields to confirm the exact field IDs for spend, impressions, clicks, conversions, and revenue.
4. Call get_data with the appropriate connector, accounts, fields, and date range.
5. Present a comparative analysis:
   - Total spend, conversions, and cost per conversion by channel.
   - ROAS (Return on Ad Spend) where revenue data is available.
   - Trends over the selected period (week-over-week or month-over-month).
6. Highlight the top-performing and underperforming campaigns or ad sets.
7. Provide actionable recommendations based on the data.
