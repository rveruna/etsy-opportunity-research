# Product Opportunity Research

A personal Python project for researching product opportunities on online marketplaces using exported keyword data, listing information and customer feedback.

The goal is to identify promising original products by comparing demand, competition, estimated listing performance and problems buyers experience.

## Research workflow

1. **Import research exports** — keyword ideas, listing research and CSV datasets.
2. **Clean and compare listings** — deduplicate products appearing under multiple keywords and separate digital downloads from physical products.
3. **Analyse competition** — compare listing ages, pricing, estimated sales, product features and market saturation.
4. **Enrich public data** *(planned)* — retrieve permitted listing details and reviews via supported integrations where available.
5. **Identify evidence-backed opportunities** *(planned)* — evaluate recurring customer needs and frustrations against existing products.
6. **Prioritise product concepts** *(planned)* — rank opportunities with source links, limitations and explicit assumptions.

## Current status

**Early development.** This repository currently documents the proposed research workflow. Existing analysis was performed locally using exported research CSV files. Automated data integrations are not yet implemented.

## Data and limitations

- Third-party sales and revenue estimates are **not verified transactions** and should not be represented as actual monthly sales.
- Public data integrations do not grant access to competitors' private transactions.
- Customer feedback should be interpreted in context: isolated complaints are not automatically market-wide problems.
- All data use must respect platform terms, permissions, privacy requirements and rate limits.

## Security

Keep API credentials and access tokens in environment variables or local ignored files. **Never commit secrets to this public repository.**
