# 💎 GoldenMetrics – Advanced EDA for Luxury Retail Sales

**GoldenMetrics** is an advanced Exploratory Data Analysis (EDA) project focused on luxury retail.  
It leverages real-world business logic to extract insights from a simulated dataset inspired by premium fashion brands such as *Golden Goose*.  

The aim is to support strategic decisions in retail by identifying demand patterns, customer segments, product performance, and profitability dynamics.

---

## 🎯 Project Objectives

- Understand key sales dynamics across stores, seasons, and channels.
- Measure profitability per product and customer segment.
- Detect fast-moving vs. underperforming SKUs using BCG analysis.
- Analyze VIP vs Tourist consumer behavior.
- Support inventory planning and commercial strategy with data.

---

## 📦 Dataset Description

The dataset contains **5,000 retail transactions** with the following structure:

| Column Name              | Description                                  |
|--------------------------|----------------------------------------------|
| Fecha                    | Date of transaction                         |
| Tienda                   | Store name/location                         |
| SKU                      | Unique product identifier                   |
| Producto                 | Product name                                |
| Categoría                | Product category (e.g., sneakers, apparel)  |
| Precio (€)               | Final sale price                            |
| Coste_unitario (€)       | Unit cost of the item                       |
| Margen_unitario (€)      | Profit margin per unit                      |
| Unidades_vendidas        | Units sold in this transaction              |
| Tipo_cliente             | VIP, Tourist, or Local                      |
| Canal_venta              | Sales channel (In-store / Online)           |
| Método_pago              | Payment method                              |
| Campaña                  | Associated marketing campaign               |
| Temporada                | Season (Spring/Summer/Fall/Winter)          |
| Stock_inicial            | Initial stock at the time                   |
| Stock_final              | Remaining stock after sale                  |
| Reposición_necesaria     | Boolean for restocking need                 |
| Región                   | Store region (Europe, Asia, etc.)           |

📍 File location: `data/goldenmetrics_dataset_v2.csv`

---

## 🧪 Methodology

The analysis was structured in 7 sections:

1. **Data Import & Preprocessing**
2. **Data Cleaning & Enrichment** (dates, campaign normalization)
3. **Descriptive Statistics**
4. **Advanced EDA:**
   - Sales trends by month, channel, and region
   - Price elasticity and demand curves
   - BCG Matrix: Profitability vs. Rotation
   - Margin and average ticket evolution
   - Customer segmentation analysis
5. **Outlier detection and stock inconsistencies**
6. **Strategic KPI Dashboarding**
7. **Business Conclusions & Recommendations**

---

## 📊 Key Insights (Selected Highlights)

- **Profitability vs. Rotation Matrix** shows that 13 products have low sales velocity but high unit margins → ideal candidates for selective promotions or limited editions.
- **VIP customers** represent only 20% of buyers but generate 47% of total margin.
- **Tourists** tend to prefer premium-priced items and buy more in physical stores.
- **Seasonal campaigns** drive 34% higher average ticket compared to non-campaign periods.
- Certain SKUs with high sales volume are contributing disproportionately low margins → optimization needed.

---

## 📈 Visual Highlights

> Notebooks include dynamic and static visualizations using Seaborn, Matplotlib, and Plotly.

- Monthly sales barplots and line charts
- Demand curve with fitted regression
- BCG scatter plot (rotation vs. profitability)
- Customer behavior heatmaps
- Stock vs. sales ratio diagnostics

---

## ⚙️ Tech Stack

- `Python 3.10`
- `Pandas`, `NumPy` for data wrangling
- `Matplotlib`, `Seaborn`, `Plotly` for visualizations
- `Jupyter Notebook` for analysis and documentation
- `Git` & `GitHub` for version control
- `Virtual Environment`: `luxmetrics`

---

## ⚠️ Limitations

- Simulated dataset (not from actual sales), though designed to reflect realistic luxury retail behavior.
- No real-time inventory updates or transaction timestamps.
- Customer segmentation is simplified (VIP / Tourist / Local).

---

## 🔮 Next Steps

- Predictive modeling: demand forecasting by SKU
- Dynamic pricing simulation with elasticity models
- Deployment via interactive dashboard (Streamlit)
- Recommender system for product bundles based on past behavior

---

## 🚀 How to Reproduce

1. Clone the repository:

```bash
git clone https://github.com/CarlosRomanM/GoldenMetrics-EDA.git
cd GoldenMetrics-EDA

---
👤 Author
Carlos Román Monje
Data Analyst & AI Solutions
📍 Based in Spain
🔗 LinkedIn Profile
🌐 Personal Portfolio



---
