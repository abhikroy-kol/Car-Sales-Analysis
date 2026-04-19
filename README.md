# 🚗 Car Sales Dashboard

> An interactive Power BI dashboard for analyzing and visualizing car sales performance — built for data-driven decision-making in the automotive retail sector.

![Dashboard Preview](screenshots/overview.png)

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Dashboard Features](#-dashboard-features)
- [Key Insights](#-key-insights)
- [Tools & Technologies Used](#-tools--technologies-used)
- [Dataset Description](#-dataset-description)
- [Screenshots](#-screenshots)
- [How to Use / Navigate the Dashboard](#-how-to-use--navigate-the-dashboard)
- [Future Improvements](#-future-improvements)
- [Conclusion](#-conclusion)

---

## 🔍 Project Overview

The **Car Sales Dashboard** is a comprehensive business intelligence solution built using **Power BI**, designed to track, analyze, and visualize car sales performance across multiple dimensions — including time, geography, vehicle type, color, and dealership. The dashboard presents both high-level KPIs and granular transactional data, enabling stakeholders to make informed, data-driven business decisions.

This project covers **Year-to-Date (YTD)** and **Month-to-Date (MTD)** sales metrics from **2022 car sales records**, providing a clear picture of performance trends, pricing behavior, and market distribution.

---

## 🎯 Objectives

- **Monitor** overall car sales performance using real-time KPI tracking (YTD & MTD).
- **Identify** sales trends over time to understand seasonality and peak sales periods.
- **Analyze** how different vehicle attributes — body style, color, company — influence sales volume and revenue.
- **Compare** dealership and company-level performance to surface top and underperforming segments.
- **Visualize** regional distribution of sales to uncover geographic demand patterns.
- **Empower** sales managers and business analysts with interactive filtering for self-serve exploration.

---

## 📊 Dashboard Features

The dashboard is structured across two main views: **Overview** and **Details**.

---

### 🟡 Overview Page

#### 1. KPI Cards — YTD & MTD Performance

Three primary KPI cards sit prominently at the top of the dashboard, each displaying:
- **YTD Total Sales**: Cumulative revenue generated for the year ($371.2M), with YoY growth indicator (+23.6%) and MTD value ($54.28M).
- **YTD Average Price**: The average selling price across all transactions ($28.0K), with a slight MTD price dip ($223.48 / -0.79%) flagged in red.
- **YTD Cars Sold**: Total number of vehicles sold year-to-date (13,261), with period-over-period growth (+24.6%) and MTD count (1,921).

Color-coded indicators (green for positive, red for negative) provide instant performance signals.

---

#### 2. YTD Sales Weekly Trend — Line Chart

A time-series line chart plots **weekly sales totals** across all 52 weeks of the year, allowing users to:
- Spot **seasonal peaks and troughs** in sales activity.
- Identify the **best-performing week** (Week ~36 peaked at $14.9M).
- Observe a notable **dip at the year's end**, suggesting potential seasonal slowdown or data recency effects.

---

#### 3. YTD Total Sales by Body Style — Donut Chart

A donut chart breaks down total sales revenue by vehicle body type:

| Body Style   | YTD Sales |
|--------------|-----------|
| SUV          | $99.9M    |
| Hatchback    | $82.8M    |
| Sedan        | $73.7M    |
| Passenger    | $63.4M    |
| Hardtop      | $51.4M    |

SUVs dominate the sales mix, reflecting contemporary consumer preferences for larger vehicles.

---

#### 4. YTD Total Sales by Color — Donut Chart

A companion donut chart visualizes sales distribution by car color:

| Color       | Share    |
|-------------|----------|
| Pale White  | 47.02%   |
| Black       | 33.74%   |
| Red         | 19.24%   |

Pale White is the runaway leader, accounting for nearly half of all sales — a key insight for inventory planning.

---

#### 5. YTD Car Sold by Region — Map Visual

A **Bing Maps-powered geographic visual** plots total cars sold across US dealer regions, with bubble sizes proportional to volume. Highlighted regions include:
- **Austin, TX** — Large sales hub (largest bubble)
- **Scottsdale, AZ**
- **Greenville, SC**
- **Aurora, CO**
- **Pasco, WA**, **Janesville, WI**, **Middletown**, and others

This enables regional managers to benchmark performance and identify underserved markets.

---

#### 6. Company-wise Sales Trend — Matrix Table

A detailed performance table lists all car manufacturers with four key metrics:

| Column              | Description                                         |
|---------------------|-----------------------------------------------------|
| YTD Avg Price       | Average price per unit sold by the company          |
| YTD Car Sold        | Total number of units sold                          |
| YTD Total Sales     | Gross revenue generated                             |
| %GT YTD Total Sales | Company's percentage contribution to total revenue  |

Inline data bars provide quick visual comparison across companies. **Chevrolet** leads all brands in volume (1,043 units, 7.30% of total).

---

#### 7. Interactive Slicers / Filters

Four dropdown filters allow users to dynamically slice all visuals simultaneously:

- **Body Style** — Filter by SUV, Sedan, Hatchback, Passenger, or Hardtop
- **Dealer** — Drill into individual dealership performance
- **Transmission** — Compare Automatic vs. Manual sales trends
- **Engine** — Filter by engine type (e.g., Overhead Camshaft, Double Overhead Camshaft)

---

### 🔵 Details Page

The **Details** tab displays a comprehensive **row-level transaction table**, including:
- Car ID, Date, Customer Name
- Dealer Name, Company, Model
- Color, Price

This view enables auditors and analysts to validate summary metrics and perform ad-hoc deep dives into individual transactions.

---

## 💡 Key Insights

### 1. 📈 Strong Year-over-Year Growth
YTD Total Sales of **$371.2M** reflect a **+23.6% YoY increase**, and cars sold are up **+24.6%**, signaling robust market demand. This growth outpaces typical industry benchmarks and suggests effective sales strategies and inventory management.

### 2. 💰 Slight Pricing Pressure
Despite volume growth, the **YTD Average Price of $28.0K** reflects a marginal MTD dip of **-0.79% ($223.48)**. This could indicate increased promotional activity, a shift toward lower-priced models in the current month, or heightened competitive pricing pressure.

### 3. 🚙 SUVs Rule the Roost
With **$99.9M in YTD sales**, SUVs account for the **largest revenue share** among body styles (~27% of total), far outpacing Hardtops ($51.4M). This mirrors broader industry trends toward utility vehicles and suggests dealers should prioritize SUV inventory stocking.

### 4. 🎨 White Cars Dominate Demand
**Pale White** captures **47%** of all color-based sales — nearly one in every two cars sold is white. Combined with **Black (33.74%)**, neutral tones account for over **80%** of total sales. Red vehicles, while visually distinctive, account for only ~19%, suggesting a conservative color preference in this market.

### 5. 🏆 Chevrolet is the Volume Leader
With **1,043 units sold (7.30% of total YTD sales)**, **Chevrolet** is the top-selling brand by volume. **Dodge (618 units)** and **Ford (886 units)** follow, confirming American domestic brands' dominance. Meanwhile, **Audi** lags behind with only 259 units — though at a **$22.2K average price**, it may serve a different buyer segment.

### 6. 🗺️ Austin Leads Regional Sales
The geographic map reveals **Austin, TX** as the highest-volume dealership region in the US. This warrants further investment in inventory, staffing, and marketing in and around the Austin market.

### 7. 📆 Peak Sales Around Week 36
The weekly trend chart shows a **notable spike around Week 36 (~early September)**, likely driven by end-of-summer promotions or model-year clearance events. Recognizing this pattern can help teams pre-plan inventory and campaigns.

---

## 🛠️ Tools & Technologies Used

| Tool / Technology | Purpose |
|---|---|
| **Microsoft Power BI Desktop** | Dashboard creation, data modeling, and visualization |
| **Power Query (M Language)** | Data transformation and cleaning |
| **DAX (Data Analysis Expressions)** | Custom KPI measures (YTD, MTD, YoY comparisons) |
| **Microsoft Bing Maps** | Geographic sales map visualization |
| **Microsoft Excel / CSV** | Source data format for car sales records |
| **GitHub** | Version control and project hosting |

---

## 📁 Dataset Description

The dataset contains **individual car sales transaction records** from **2022**, with the following fields:

| Column        | Description                                      |
|---------------|--------------------------------------------------|
| `Car_Id`      | Unique transaction/vehicle identifier            |
| `Date`        | Date of sale                                     |
| `Customer Name` | Name of the buyer                             |
| `Gender`      | Customer gender                                  |
| `Annual Income` | Customer's reported annual income             |
| `Dealer_Name` | Name of the dealership                           |
| `Company`     | Car manufacturer / brand                         |
| `Model`       | Specific car model                               |
| `Engine`      | Engine type (e.g., Overhead Camshaft, DOHC)      |
| `Transmission`| Transmission type (Auto / Manual)                |
| `Color`       | Exterior color of the vehicle                    |
| `Price ($)`   | Sale price in USD                                |
| `Dealer_No`   | Dealer identification number                     |
| `Body Style`  | Vehicle body category (SUV, Sedan, Hatchback, etc.) |
| `Phone`       | Customer contact number                          |
| `Dealer_Region` | Geographic region of the dealership           |

> **Note:** The dataset is transactional in nature — each row represents a single car sale. A **Calendar Table** was separately created in Power BI to enable proper time-intelligence calculations (YTD, MTD, YoY).

---

## 📸 Screenshots

### Overview Dashboard
![Overview Dashboard](screenshots/overview.png)
> *The main overview page showing KPIs, weekly trend, body style and color distribution, regional map, and company performance table.*

---

### Details View
![Details View](screenshots/details.png)
> *The detailed transaction-level table displaying individual car sale records.*

---

### Raw Dataset (Excel)
![Raw Dataset](screenshots/dataset.png)
> *A preview of the underlying car sales dataset used to build this dashboard.*

---

## 🧭 How to Use / Navigate the Dashboard

### Prerequisites
- Install **[Microsoft Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (free).

### Steps

1. **Clone or download** this repository:
   ```bash
   git clone https://github.com/your-username/car-sales-dashboard.git
   ```

2. **Open the file** `Car_Sales.pbix` in Power BI Desktop.

3. **Explore the Overview page** — the default landing view — to review top-level KPIs and visual summaries.

4. **Use the Slicer Filters** on the left panel to dynamically filter the entire dashboard:
   - Select a **Body Style** (e.g., SUV) to see only SUV-related metrics.
   - Filter by **Dealer** to evaluate individual dealership performance.
   - Toggle **Transmission** or **Engine** to compare segment performance.

5. **Hover over chart elements** for detailed tooltips showing exact values.

6. **Click on a chart segment** (e.g., a donut slice or map bubble) to cross-filter all other visuals on the page — this is Power BI's native cross-filtering feature.

7. **Switch to the Details tab** (bottom navigation) to access the full transaction-level table for deeper inspection.

8. **Reset filters** at any time using the "Clear Filters" icon or by re-selecting "All" in each slicer.

---

## 🚀 Future Improvements

- [ ] **Profit & Margin Analysis** — Incorporate cost data to calculate gross profit per unit and by company.
- [ ] **Customer Segmentation** — Leverage gender and annual income fields to build buyer persona analyses.
- [ ] **Forecasting** — Add Power BI's built-in forecasting to project future YTD sales based on historical trends.
- [ ] **Dealer Leaderboard** — Build a ranked view of top-performing dealers with drill-through capability.
- [ ] **Mobile Layout** — Optimize the dashboard layout for Power BI mobile app consumption.
- [ ] **Row-Level Security (RLS)** — Implement RLS so regional managers only see their own region's data.
- [ ] **Live Data Connection** — Connect to a live SQL database or cloud data source for real-time updates.
- [ ] **What-If Parameters** — Allow users to simulate the effect of price changes on total revenue.
- [ ] **Bookmarks & Story Slides** — Create guided analytical narratives using Power BI bookmarks.

---

## ✅ Conclusion

The **Car Sales Dashboard** demonstrates the power of visual analytics in transforming raw transactional data into actionable business intelligence. By combining KPI tracking, time-series analysis, geographic mapping, and multi-dimensional filtering in a clean, dark-themed interface, this dashboard equips stakeholders at all levels — from dealership managers to executive leadership — with the insights they need to drive smarter sales strategies.

The dashboard's **23.6% YoY revenue growth** and **24.6% increase in units sold** point to a thriving sales operation, while nuances like slight average price pressure and dominant color/body-style preferences offer clear direction for inventory optimization and targeted marketing.

This project reflects the real-world value of Power BI as a business intelligence tool, and serves as a strong foundation for further analytical enhancements as outlined in the future improvements roadmap.

---

## 📬 Contact

For questions, feedback, or collaboration, feel free to reach out:

- **GitHub**: [@your-username](https://github.com/your-username)
- **LinkedIn**: [Your Name](https://linkedin.com/in/your-profile)
- **Email**: your.email@example.com

---

<p align="center">
  Made with ❤️ using Power BI &nbsp;|&nbsp; ⭐ Star this repo if you found it helpful!
</p>
