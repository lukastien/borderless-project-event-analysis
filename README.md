# Borderless Project — 2025 Event Performance Analysis

An Excel-based analysis of a full year of live events for Borderless Project, a record label running concerts, showcases, and album release events across the Bay Area and Southern California. This project uses synthetic data modeled on the kind of event and attendance data a label's data/business analyst would actually track.

> **Note:** All data in this project is synthetic/sample data generated for portfolio purposes. It is not real Borderless Project business data.

## Dashboard

![Dashboard KPIs and Top Charts](images/dashboard-top.png)
*Replace this with a screenshot of your KPI cards + Monthly Revenue Trend + Revenue by Genre charts*

![Dashboard Bottom Charts](images/dashboard-bottom.png)
*Replace this with a screenshot of your Attendance Rate by Day of Week + Revenue by City charts*

## Overview

The dataset covers 50 events held throughout 2025 across six cities (San Francisco, Oakland, Berkeley, Los Angeles, San Jose, and Sacramento), spanning eight genres. For each event, the data tracks attendance, ticket revenue, merchandise sales, marketing spend, and social media reach.

## What I Did

- Cleaned and structured raw event-level data (date, venue, genre, capacity, attendance, pricing, spend)
- Built calculated fields for attendance rate, ticket revenue, total revenue, and net revenue using live Excel formulas
- Created pivot-style summary tables breaking down performance by month, genre, day of week, and city
- Built a dashboard with KPI cards and four charts to visualize trends at a glance
- Identified underperforming and outperforming segments to inform event planning recommendations

## Key Findings

- **Electronic music is the strongest genre by a wide margin.** Despite only 10 of the 50 events (20%) being Electronic, the genre generated **$266,153 in total revenue** — nearly **2.5x more than R&B**, the next-highest genre ($104,898 across 8 events). On a per-event basis, Electronic events averaged roughly **$26,600 in revenue**, compared to $13,100 for R&B and $19,300 for Hip-Hop — making it the clearest "revenue per event" outperformer in the catalog.
- **April was the weakest month of the year.** With only 3 events and **$37,849 in total revenue**, April was the lowest-revenue month, coming in noticeably behind every other month except December ($46,470).
- **Saturdays and Mondays drove the most total revenue** ($231,573 and $202,300 respectively), while Thursday had both the fewest events (3) and the lowest total revenue ($33,827) of any day of the week.
- **Oakland punched above its weight**, generating $208,296 in revenue from just 7 events — a higher per-event average than most other cities, including Los Angeles.

## Recommendations

1. **Lean further into Electronic events.** Given the outsized revenue per event, increasing the share of Electronic bookings — even modestly — could meaningfully lift overall revenue without a proportional increase in event volume or overhead.
2. **Address the April revenue gap.** With only 3 events and the lowest revenue of the year, April is a clear opportunity area for next year's calendar. Adding 1-2 additional events, or a themed event tied to the season, could help close the gap.
3. **Explore themed events.** Pairing the Electronic-genre insight with the April gap, a themed Electronic showcase or festival-style event in April could address both findings at once and is worth testing next year.
4. **Investigate the Thursday underperformance.** With the fewest events and lowest revenue of any day, it's worth understanding whether Thursday is inherently a weaker night (attendance/scheduling conflicts) or simply under-booked relative to its potential.

## Tools Used

Excel (formulas: `SUMIFS`, `COUNTIFS`, `AVERAGEIFS`, `TEXT`), PivotTable-style summary tables, native Excel charts (line, column)

## Files

- `Borderless_Project_Events.xlsx` — full workbook with raw data, calculated fields, summary tables, and dashboard
