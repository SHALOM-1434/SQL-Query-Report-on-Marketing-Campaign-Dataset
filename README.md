# SQL-Query-Report-on-Marketing-Campaign-Dataset
An in-depth SQL analysis of marketing campaign data (200,000+ records). Extracts actionable insights on campaign performance, channel effectiveness, audience engagement, and ROI optimization.

## Project Overview

This repository contains a detailed SQL analysis of a marketing campaign dataset conducted during **HNG Internship Stage 3**. The analysis evaluates key performance metrics and derives actionable insights from a dataset of over 200,000 records.

## Objective

- Use SQL to extract, summarize, and interpret campaign performance.
- Highlight key performance indicators (KPIs) such as impressions, ROI, CTR, engagement, and cost-effectiveness.
- Provide insights and recommendations to optimize marketing strategy.

## Dataset Description

- **Rows:** 200,005  
- **Key Features:**  
  - `campaign_id`, `company`, `campaign_type`, `target_audience`, `location`  
  - `impressions`, `clicks`, `conversion_rate`, `acquisition_cost`, `ROI`  
  - `engagement_score`, `channel_used`
 
  ## SQL Queries & Insights

### 1. Total Impressions for Each Campaign
- Aggregated impressions by `campaign_id`.
- Revealed varying levels of campaign reach, possibly linked to budget and strategy.

### 2. Campaign with Highest ROI
- **Campaign ID 168** by **NexGen Systems** had the highest ROI of **8.00**.
- Indicates exceptional financial performance.

### 3. Top 3 Locations by Impressions
- **New York**, **Miami**, and **Chicago** led in ad visibility.
- Indicates strong audience reach in these areas.

### 4. Average Engagement by Target Audience
- **Men aged 18–24** had the highest engagement (5.51), followed by **Women 25–34**.
- Suggests demographic-specific targeting boosts performance.

### 5. Overall Click-Through Rate (CTR)
- Overall CTR = **9.98%**.
- Healthy performance, but room for creative/content optimization.

### 6. Most Cost-Effective Campaign
- **Campaign ID 101103** by **Alpha Innovations** had the lowest cost per conversion: **$33,346.67**.
- Indicates high efficiency in lead acquisition.

### 7. Campaigns with CTR Above 5%
- Several campaigns exceeded the 5% CTR threshold, with the top campaign reaching **99.2% CTR**.
- Companies like **TechCorp** and **Alpha Innovations** showed consistent success.

  ### 8. Channels Ranked by Total Conversions
- **Email Marketing**, **Google Ads**, and **Websites** topped the list.
- Email and owned media showed the highest effectiveness in conversions.

  ##  Key Insights

1. **Display campaigns** with high ROI should be studied for scalable strategies.
2. **Email and Website** channels consistently outperform social media in conversion.
3. **New York** remains the prime location for impressions.
4. **Foodies** segment has the highest CTR – highly engaged demographic.
5. Top-performing campaigns have CTRs nearing **99%**, offering models for optimization.

## Tools Used

- **SQL**: PostgreSQL (queries written in standard SQL syntax)
- **Report**: PDF summary with query objectives, logic, and business implications
- **Data Source**: Marketing campaign dataset (CSV/database)

