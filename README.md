# Kent District Library — Digital Collection Forecasting

**Team project** with Elliot Carlson, Mallory Price, and Eli VanderMeulen (April 2025)

## The Problem

Kent District Library (20 branches, ~140,000 cardholders in Kent County, MI) asked us to
assess eBook costs, circulation, and trends to help reexamine their collection budget
allocations across three platforms: Overdrive (Libby/Kanopy), Hoopla, and their physical
collection.

## What We Did

- Cleaned and organized four years (2021–2024) of checkout, spending, and budget data
  across all three platforms
- Analyzed checkout and spending trends by platform, genre, and age group
- Identified seasonal patterns using time series decomposition in Python
- Built a Holt-Winters additive forecasting model to project 2025–2027 checkouts and
  spending for each platform

## Key Findings

- **Digital usage is outpacing physical**: Overdrive checkouts grew 63% from 2021–2024
  and Hoopla grew 22%, while physical checkouts grew just 2%
- **Spending doesn't track usage 1:1**: Hoopla's per-checkout pricing model meant its
  spending grew faster (46%) than its usage, while Overdrive's fixed-license model kept
  spending and usage more proportional
- **Clear seasonality**: All three platforms spike between March and July, tied to reading
  month, spring break, and summer vacation, visible both in checkout volume and in
  Hoopla's daily budget cap blocks
- **Genre mix is stable**: despite rising volume, the breakdown of checkouts by genre
  stayed consistent. No single genre is driving the growth

## Tools

Python (pandas, statsmodels for time series decomposition and Holt-Winters forecasting),
Google Sheets/Excel for initial data organization and charting

## Report

[Full report (PDF)](Final_Report.pdf)
