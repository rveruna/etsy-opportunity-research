# Etsy Opportunity Research

A personal Python project to research **Etsy product opportunities** using exported **eRank** data and, once API access is available, the **Etsy Open API v3**.

The goal is to identify products worth creating by comparing demand, competition, listing performance estimates, customer feedback and opportunities to solve real buyer problems.

## Research workflow

1. **Import eRank exports** — keyword ideas, listing research and other exported CSVs.
2. **Clean and compare listings** — deduplicate products that appear under multiple keywords and distinguish digital downloads from physical goods.
3. **Analyse competition** — compare listing ages, pricing, estimated sales, product features and market saturation.
4. **Enrich with Etsy API data** *(planned)* — retrieve permitted public listing details and reviews where available.
5. **Find evidence-backed gaps** *(planned)* — look for recurring customer needs and frustrations, then compare those findings against existing competitor features.
6. **Prioritise product concepts** *(planned)* — rank opportunities with source links and explicitly stated assumptions.

## Current status

**Early development.** The repository is being set up; the workflow above describes planned capabilities, not a completed application. Existing research has been performed with local eRank CSV exports. Etsy API integration is not yet implemented.

## Data and limitations

- **eRank figures are estimates**, not verified Etsy sales or revenue. Estimated lifetime sales should not be presented as confirmed monthly sales.
- Etsy's API **does not disclose competitors' private transactions**.
- Review analysis should quote or link to the underlying evidence, distinguish individual complaints from recurring patterns, and avoid promising that a product will sell.
- Research should comply with Etsy's API terms, access permissions and applicable rate limits.

## Configuration and security

API keys and OAuth tokens must be kept in local environment variables or an ignored `.env` file — **never committed to this public repository**. No credentials are required to read exported eRank CSVs.

## Independence

This is an independent personal research project. It is not affiliated with, endorsed by or sponsored by Etsy or eRank.
