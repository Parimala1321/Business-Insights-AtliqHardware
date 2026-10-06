# 📊 AtliQ Business Insights 360 — Power BI Dashboard

## 📖 Project Overview

This Power BI project is a consolidated business intelligence tool for AtliQ Hardware. It brings Finance, Sales, Marketing, Supply Chain and Executive views into one report, so decision makers can track net sales, gross margin, net profit and forecast accuracy by customer, product and market.

## 🎯 Business Problem

AtliQ Hardware sells computer hardware and peripherals to retailers, distributors and direct customers across several regions. Its performance data was spread across separate reports, which made it slow to answer basic questions about profitability, customers, products and forecasting.

**Objective**

Build one interactive dashboard that gives each team the metrics it needs and lets users filter by region, market, customer, segment, category and time period.

The analysis focuses on five broad questions:

1. How are net sales, gross margin and net profit performing against the benchmark?
2. Which customers and products drive the most revenue and margin?
3. Which markets and regions are strongest, and where are the risks?
4. How accurate is the demand forecast, and where is there a risk of out-of-stock or excess inventory?
5. What actions would improve profitability?

## 🗃️ Data Model

The project uses a star schema with fact tables for sales, forecasts and cost items, connected to shared dimension tables.

**📈 Fact tables**
- `fact_sales_monthly`
- `fact_forecast_monthly`
- `fact_gross_price`
- `fact_manufacturing_cost`
- `fact_pre_invoice_deductions`
- `fact_post_invoice_deductions`
- `fact_freight_cost`

**📐 Dimension tables**
- `dim_customer`
- `dim_product`
- `dim_market`
- `dim_date`

## 🛠️ Tools

- 📊 Power BI
- 🧮 DAX
- 🔄 Power Query
- 🗂️ Data modelling
- 🎚️ Slicers and buttons
- 🧭 Page navigation and bookmarks

## 📋 Dashboard Analysis

Every page can be filtered by region and market, customer, segment and category, fiscal year and quarter, with YTD, YTG and comparison against last year or target.

### 1. ℹ️ Info

The landing page, "Business Insights 360". It links to the Finance, Sales, Marketing, Supply Chain and Executive views, and to a support page.

### 2. 💰 Finance View

**🔍 Key findings**
- FY 2022 estimate net sales are $3.74bn, against a benchmark of $823.85M.
- Gross margin is 38.08%, up 1.59 points on the benchmark.
- Net profit is -$522.42M (-13.98%) because operational expense is $1,945.30M.
- About half of gross sales ($7.37bn) is lost to pre-invoice and post-invoice deductions.

**💡 Business implication:** Margins are healthy, but deductions and operating costs are pushing the business into a net loss.

### 3. 🤝 Sales View

**🔍 Key findings**
- Amazon is the largest customer with $496.88M net sales and a 36.8% gross margin.
- Atliq Exclusive ($361.12M) and Atliq e Store ($304.10M) follow, with Atliq Exclusive earning a 46.0% margin.
- Neptune (46.7%) and Flipkart (42.1%) have strong margins, while Sage (31.5%) and Leader (30.7%) are weaker.

**💡 Business implication:** Customer size and customer margin do not always move together, so the mix of customers matters.

### 4. 📣 Marketing View

**🔍 Key findings**
- Notebook is the largest product segment at $1,580.43M, followed by Peripherals ($897.54M) and Desktop ($711.08M).
- Gross margin is almost the same across segments (about 38%), and every segment has a net profit margin of about -14%.
- APAC leads on net sales ($1,923.77M), while NA has the best margin (45.0%).

**💡 Business implication:** The loss is business-wide rather than caused by one product, so cost control matters more than changing the product mix.

### 5. 🚚 Supply Chain View

**🔍 Key findings**
- Forecast accuracy is 81.17%, up 1.2 points on last year.
- Net error is -3,472.69K, which means demand was under-forecast overall (-9.5%, flagged as out of stock).
- Peripherals (68.17%) and Storage (71.50%) have the weakest forecast accuracy and an out-of-stock risk.
- Networking has the best accuracy (93.06%).

**💡 Business implication:** Forecasts are improving, but under-forecasting in Peripherals and Storage puts sales at risk.

### 6. 🏁 Executive View

**🔍 Key findings**
- Net sales of $3.74bn, gross margin of 38.1%, net profit of -13.98% and forecast accuracy of 81.17% are shown together.
- NA ($1,022.09M, 45.0%) and India ($945.34M, 35.8%) are the largest sub-zones by net sales.
- Net profit is negative in every sub-zone, and India is the weakest at -22.99%.
- Amazon (13.30%) and Atliq Exclusive (9.67%) contribute the most revenue.

**💡 Business implication:** The executive team gets the full picture on one page, with risk flags for each market.

## 📌 Executive Findings

| Area | Key Finding |
|---|---|
| 💰 Net Sales | $3.74bn in FY 2022 (estimate), against a benchmark of $823.85M. |
| 📈 Gross Margin | 38.1%, up 4.37% on the benchmark. |
| 📉 Net Profit | -13.98%, driven by operational expense of $1,945.30M. |
| 🧾 Deductions | Pre-invoice and post-invoice deductions take about half of gross sales. |
| 🤝 Customers | Amazon ($496.88M) is the largest, and Atliq Exclusive has the best margin among the top customers (46.0%). |
| 🖥️ Products | Notebook ($1,580.43M) is the largest segment, and margins are about 38% across all segments. |
| 🌍 Regions | APAC has the highest net sales ($1,923.77M), and NA the best margin (45.0%). |
| 🚚 Forecasting | Accuracy is 81.17%, with the biggest risk in Peripherals and Storage. |

## ✅ Recommendations

1. 💸 **Control operating costs.** Operational expense is the main reason for the net loss.
2. 🧾 **Reduce deductions.** Review pre-invoice and post-invoice discounts, which take about half of gross sales.
3. 🤝 **Grow high-margin customers.** Prioritise customers such as Atliq Exclusive, Neptune and Flipkart, and renegotiate terms with low-margin ones such as Sage and Leader.
4. 🌍 **Fix India.** It has the weakest net profit margin among the sub-zones.
5. 🚚 **Improve forecasting.** Focus on Peripherals and Storage to avoid stock-outs, and watch excess inventory in segments flagged EI.

## 🏆 Final Business Conclusion

AtliQ's sales and gross margin are strong, but the business is not yet profitable at the net level.

The data points to a connected chain:

Heavy deductions and high operating costs -> lower net sales and net profit -> a net loss in every market, even with a 38% gross margin.

The improvement plan should work in the opposite direction:

Reduce deductions -> control operating costs -> focus on high-margin customers and markets -> improve forecasting to protect sales.

The main lesson from the analysis is that margin alone is not enough. Profit depends on controlling the costs and deductions that sit below gross margin.

## 🔗 Live Dashboard

### [📊 View the Interactive Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNWI3YzBhYTItNmE3MS00M2I3LWJhZDAtZTZjYzExNzg5MGExIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)
