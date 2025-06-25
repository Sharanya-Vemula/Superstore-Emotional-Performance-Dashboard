# 💼 Superstore Emotional Performance Dashboard

This project transforms the traditional Superstore sales dataset into a **human-centered, emotionally intelligent analytics dashboard** using **Power BI**. By simulating and incorporating emotional and behavioral factors—such as customer satisfaction, employee stress indicators, and product sentiment—this dashboard delivers deeper, **purpose-driven business insights** that align with organizations like **Aaruchudar**.

---

## 🎯 Project Objective

The primary objective is to augment standard retail KPIs (sales, profit, quantity) with **emotional performance indicators**, such as:
- Simulated customer sentiment
- Employee wellness influence
- Behavioral trends in sales performance

This emotional overlay turns a traditional business dashboard into a **Human Intelligence (HI)** tool—enabling strategy, culture, and clarity in decision-making.

---

## 📦 Dataset

Based on the publicly available **Superstore Sales dataset**:

🔗 [Download the Dataset from Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Fields Used:
| Column             | Description                             |
|--------------------|-----------------------------------------|
| Order ID           | Unique order identifier                 |
| Customer Name      | Name of the customer                    |
| Product Category   | Product category (e.g., Furniture)      |
| Sales              | Sale amount                             |
| Profit             | Profit earned                           |
| Quantity           | Number of items                         |
| Region             | Region of delivery                      |
| Order Date         | Date of order                           |
| Ship Mode          | Shipping type                           |

### Simulated Additions:
| Field                 | Description                                 |
|------------------------|---------------------------------------------|
| Customer Sentiment     | Simulated sentiment from feedback (Positive/Neutral/Negative) |
| Employee Stress Level  | Randomly assigned stress levels for each region |
| Feedback Score         | Numerical representation of emotional satisfaction (1–10) |

---

## 🔍 Key Features

### 1. **Emotional Intelligence Layer**
- **Customer Sentiment Analysis** (simulated): Understand satisfaction per product/region.
- **Employee Stress Visualization**: Compare high-performance vs. high-stress areas.
- **Feedback Score Mapping**: Identify emotional patterns across segments.

### 2. **Standard Business Insights**
- Top-selling and most profitable categories
- Sales vs. Profit across regions
- Time-based sales performance

### 3. **Power BI Visualizations**
- Sentiment distribution by product or region
- Stress Level vs. Performance heatmap
- Feedback score timeline
- KPI cards and trendlines for sales, profit, quantity, and emotional indicators
- Dynamic filters by category, sentiment, region, or date

---

## 📊 Tools & Technologies

- **Visualization**: Power BI Desktop  
- **Data Source**: Superstore dataset (CSV)  
- **Data Preparation**: Power Query (with manual sentiment simulation)

---

## 📂 Project Structure

├── data/
│ ├── superstore_with_sentiment.csv
├── dashboard/
│ ├── Superstore Emotional Dashboard.pbix
│ ├── Superstore Emotional Dashboard.pdf
├── README.md


---

## 🚀 How to Use

### 1. Download or clone the repository
```bash
git clone https://github.com/Sharanya-Vemula/superstore-emotional-dashboard.git

2. Open the Power BI Dashboard
Launch Superstore Emotional Dashboard.pbix using Power BI Desktop

3. Explore insights
Filter by region, category, or sentiment

Drill into customer behavior or emotional patterns

Interpret employee stress vs. performance visuals


