---
name: data-explorer
description: Explore available Windsor.ai connectors, fields, and data sources. Use to discover what data is accessible before building queries.
---

# Data explorer

## When to use

- First time connecting to Windsor.ai
- Discovering which platforms and accounts are available
- Understanding what metrics and dimensions can be queried
- Checking field types and table structures before analysis

## Instructions

1. Call get_connectors to list all available connectors and their connected accounts.
2. For each connector the user is interested in, call get_options to show available fields, date filters, and query options.
3. Use get_fields to retrieve detailed information: field descriptions, data types, and table membership.
4. Categorize fields into metrics (NUMERIC/PERCENT) and dimensions (all others).
5. Present a clear summary of what data is available, organized by connector.
6. Suggest example queries the user could run based on the available data.
