# Consumer Healthcare Project: Comprehensive eCommerce Analytics Report

![image](https://github.com/TetianaShchudla/CHC-data-PowerBI/blob/main/assets/CHC-Dashboard.png)

# Consumer Healthcare eCommerce Analytics Report

This project focuses on building a comprehensive **eCommerce Analytics report** that evaluates sales performance across various regions, utilizing data from both online and offline sources. The report is designed to deliver insights on product performance, sales trends, and growth opportunities across multiple sales channels.

## Table of Contents
- [Project Overview](#project-overview)
- [Objective](#objective)
- [Data Structure](#data-structure)
- [Project Workflow](#project-workflow)

## Project Overview

The **Consumer Healthcare eCommerce Analytics report** aims to consolidate and analyze sales data across different regions and channels. This analysis helps in understanding product performance in various markets, comparing sales across eCommerce and physical stores, and identifying trends over time.

## Objective
- **Develop a Comprehensive eCommerce Report**: Create a detailed report analyzing sales data across both eCommerce and offline channels for a complete view of performance.
- **Integrate Additional Data from New Markets**: Expand data coverage by adding sales data from additional countries to enhance the scope of the analysis, capturing regional trends.

## Data Structure
The dataset is structured to provide multiple levels of segmentation:

- **Region**: High-level geographical segments (e.g., `AMEA`, `CHINA`, `EULA`).
- **Zone**: More localized regions within each larger region (e.g., `AUSTRALIA/NZ`, `BRAZIL`).
- **Cluster**: Market/product clusters (e.g., `CHC`).
- **Country**: Specific countries (e.g., `AUSTRALIA`, `GERMANY`).
- **Channel**: Sales channels like `E-COMMERCE`, `MASS MARKET`, and `PHARMACY`.
- **Category Hierarchies**: Categories from broad to specific:
  - **Category5** (Strategic segments): `OTHERS`, `STRONGHOLDS`, etc.
  - **Category4** (Brand affiliation): `SANOFI-CHC`, `NON SANOFI-CHC`.
  - **Category3** (Therapeutic areas): `COUGH & COLD`, `DIGESTIVE HEALTH`.
  - **Category2** (Sub-categories): `DIGESTIVE WELLNESS`, `MENTAL WELLNESS`.
  - **Category1** (Treatment-specific segments): `IMMUNITY`, `SLEEP`.
- **Corporation Groups**: Major corporations (e.g., `SANOFI`, `GSK+PFZ`).
- **Product Group**: Product classifications, from `ProductGroup1` to `ProductGroup3`.
- **Sales Metrics**: Key metrics like `PeriodSales` (monthly sales) and `PACK` (units sold).
- **Reference Products and Markets**: Comparative fields for competitive analysis.
- **Time Periods**: Fields like `EndDate` and `LaunchDate` to track performance over time.

## Project Workflow
1. **Data Integration**: Combining existing data with new country-level data across sales channels, structured to support detailed analysis by region, channel, and product segment.
2. **Report Building**: Creating a Power BI report that delivers insights on product performance segmented by region, channel, and other key metrics.

---
