# **Marketing Campaign Performance Customer Segmentation Dashboard**

## Introduction / Background:
Businesses invest in marketing campaigns across multiple channels and customer segments. A precise dashboard is required to evaluate campaign effectiveness, profile best‐responding customers, optimize channel spend, and tailor future campaigns.

## Problem Statement:
The marketing team lacks an integrated dashboard to monitor which customer segments and channels produce the best response or ROI. Without such analytics, campaign spend may be misallocated, and customer targeting inefficient.

## Aim / Project Objective:
To build an Excel‐based interactive dashboard that tracks campaign performance, segments customers by response behaviour and demographics, and supports data‐driven decisions on channel allocation and customer marketing strategy.

## Key Guiding Questions (10–15):
1. What is the overall response rate to campaigns across all customers and channels?
2. Which campaign channel (e.g., email, direct mail, social media) yields the highest response rate and highest spend per response?
3. Which customer segments (age groups, income brackets, education levels, marital status) demonstrate the highest response rates?
4. What is the average amount spent by responders vs non‐responders?
5. Are there demographics (e.g., high income + education) that correlate strongly with higher spend or response?
6. How does response behaviour differ by previous purchase history (number of past purchases) or customer loyalty?
7. Which month/quarter or time period had higher campaign success, and is there seasonality?
8. What is the cost-per-response (if cost is available or proxy) by channel and segment?
9. Which combinations of channel + demographic produce the highest ROI (response rate × spend)?
10. Are there under-served segments (low response but high potential spend) that could be targeted differently?
11. How is non-response distributed across segments, and what are the characteristics of non‐responders?
12. Can we cluster customer segments (e.g., via pivot tables) into “high-value responders”, “low-value responders”, “non‐responders” and profile them?
13. How does amount spent vary by respondent channel and demographic?
14. What recommendations can be made to reallocate budget or adjust channel mix based on performance data?
15. Can we forecast (or at least trend) expected response-rate improvements from optimized targeting?

## Approach / Methodology:
* Data cleaning: Import into Excel/Power Query; handle missing demographic values; ensure campaign dates are correctly formatted; standardise channel names; flag responders vs non-responders.
* Data preparation: Create calculated fields: ResponseFlag (1/0), AmountSpent, ResponseRate per segment, ChannelCategory, AgeGroup, IncomeBracket, PastPurchaseCategory. Possibly derive a “ValueSegment” field (e.g., high spend vs low spend).
* Analysis: Use pivot tables to summarise response counts and rates by channel, demographic segment, past purchases. Use cross‐tabs to show channel × segment performance. Compute average spend by channel and segment. Use charts to show top performing segments.
* Visualization: Build dashboard sheet(s) with KPI cards (total campaign spend, total responses, response rate), slicers (channel, age group, income bracket), bar/column charts for top channels and segments, heatmap table for channel vs demographic response rate, bubble chart perhaps for spend vs response rate vs segment size. Conditional formatting to highlight strong vs weak segments.

## Expected Deliverables:
* Excel workbook with cleaned dataset, calculated fields, pivot tables and dashboard sheets.
* Interactive dashboard enabling filtering by channel, demographic and time period.
* Executive summary report (Word/PDF) with key findings, segment profiles, channel recommendations, and actionable next steps for marketing strategy.

## Anticipated Outcomes / Insights:
* Clear understanding of which channels and customer segments deliver the highest return, enabling better budget allocation.
* Profiling of high‐value responders and identification of underperforming segments for remediation.
* Data‐driven recommendations on campaign targeting, channel mix, customer segmentation and likely improvements in response rates and spend efficiency.
* Foundations for ongoing monitoring of campaign performance and evolving the customer segmentation model.
