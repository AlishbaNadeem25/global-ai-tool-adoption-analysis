# AI Adoption Insights: Global AI Tool Adoption Analysis (2023–2024)

## Problem Statement
A market research firm wants to understand how AI tool adoption varies across countries, industries, and company sizes, and whether adoption is accelerating year-over-year. This dashboard was built to help stakeholders identify which markets and segments are leading (or lagging) in AI adoption, to inform go-to-market and product strategy.

## Dataset
- ~145,000 rows covering AI tool usage across countries, industries, company sizes, and age groups (2023–2024)
- Key fields: `country`, `industry`, `ai_tool`, `adoption_rate`, `daily_active_users`, `year`, `age_group`, `company_size`

## Business Questions
1. Which AI tools have the highest average adoption rate, and does that differ by industry?
2. How did adoption rate change from 2023 to 2024 — overall, and by country?
3. Which industry–company size combinations show the strongest adoption?
4. Is there a relationship between daily active users and adoption rate?
5. Which age group is driving adoption for each tool?
6. Which countries stand out — are any surprisingly high or low relative to their industry mix?

## Dashboard

![Dashboard for AI](Dashboard%20for%20AI.JPG)

The dashboard includes:
- **Key Insights** panel summarizing the headline finding
- **Adoption rate by age group and AI tool** (clustered bar)
- **Adoption rate by industry and AI tool** (clustered bar)
- **Industry × company size matrix** with conditional formatting
- **Adoption Rate vs. Daily Active Users** scatter plot with trendline
- **Adoption Rate by Country and Year** treemap

## Key Finding

Across every dimension analyzed — country, industry, company size, age group, and year — average adoption rate remains **flat at approximately 49–50%**. No segment shows a statistically meaningful lead or lag, and there is no discernible relationship between daily active users and adoption rate (near-zero trendline slope in the scatter plot).

This is a deliberately honest read of the data: rather than force a narrative onto noise, the dashboard surfaces the flat trend itself as the primary insight, alongside the (mild) segment-level variation visible in the matrix table for readers who want to dig further.

## Tools Used
- Power BI (data modeling, DAX measures, visualization)
- Excel (initial data review)

## Author
Alishba Nadeem 
