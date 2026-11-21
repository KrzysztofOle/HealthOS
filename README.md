# HealthOS — personal health data platform (concept)

**Status: documentation-only concept.** The current `main` branch contains this README but no application source code, build configuration, database schema or tests. Listed functionality is a roadmap, **not** an available product.

## Objective
Plan a privacy-focused health data platform covering personal weight history, nutrition, physical activity, trends and AI-assisted data entry. No data integration or medical decision-support feature has been implemented here.

## Proposed roadmap (not implemented)
1. Weight, food and activity diary, summaries and charts.
2. Nutrition reference data, recipes and food catalog.
3. Optional health measurements, laboratory values, medication and sleep.
4. AI-assisted capture and summaries subject to data validation.
5. Optional device and health-platform integrations.

## Technology ideas — not committed dependencies
Earlier plans considered Python, TypeScript and Google Sheets, but the repository has **no dependency manifest**. The architecture and storage should be selected only when implementing a bounded MVP.

## Local setup
No installation or run command exists. The first implementation milestone should define a minimal data model, privacy protections, one local end-to-end use case and tests.

This repository is not a deployed service and does not hold health records.
