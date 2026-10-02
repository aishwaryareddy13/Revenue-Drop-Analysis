# 📊 Revenue Insight Pro: E-Commerce Revenue Drop Analysis

## 🌟 Overview
**Revenue Insight Pro** is an enterprise-grade Business Intelligence (BI) dashboard designed to analyze e-commerce sales performance and pinpoint critical revenue drop drivers. This project transforms raw transactional data into actionable strategic insights, helping stakeholders understand "why" revenue fluctuates and "where" growth opportunities lie.

The core objective is to move beyond simple reporting to provide **diagnostic analytics**—specifically identifying months of significant decline and decomposing the factors (categories, products, delivery issues) contributing to those drops.

## 🚀 Key Features
- **🏢 Executive Insights Summary:** Real-time generation of strategic performance bullets based on filtered data.
- **📈 Revenue Performance & Drop Drivers:** 
    - **Historical Trends:** Visualizing revenue trajectory over time.
    - **MoM Change Analysis:** Identifying months with the largest percentage growth and decline.
    - **Waterfall Analysis:** Decomposing revenue changes between two months to see exactly which categories gained or lost.
- **🌪️ Conversion Pipeline:** Funnel visualization tracking the integrity of orders from processing to delivery and retention.
- **📊 Strategic Segment Performance:**
    - **Heatmaps:** Cross-analyzing Category vs. Payment Method performance.
    - **Correlation Matrix:** Evaluating the relationship between Discounts and Revenue.
    - **Top 5 Matrix:** Instant visibility into top-performing products.
- **📥 Data Export Center:** Capability to export filtered data and summary reports in CSV format.

## 🛠️ Tech Stack
- **Python 3.x**: Core logic and data processing.
- **Pandas & NumPy**: High-performance data manipulation.
- **Plotly Express & Graph Objects**: Premium, interactive visualizations.
- **Streamlit**: Modern web framework for the BI dashboard interface.
- **Excel/OpenPyXL**: Data ingestion from enterprise spreadsheets.

## 📂 Project Structure
```text
revenue-drop-analysis
├── 📂 dashboard
│   └── dashboard.py          # Main Streamlit application
├── 📂 data
│   └── ecommerce_sales.xlsx  # Raw transactional dataset
├── 📂 notebooks
│   └── ecommerce_analysis.ipynb # Exploratory Data Analysis (EDA)
├── 📂 reports                # Generated insights and static reports
├── requirements.txt          # Python dependencies
├── LICENSE                   # Usage license
└── README.md                 # Project documentation
```

## 💻 Local Setup Instructions

Follow these steps to get the dashboard running on your local machine:

### 1. Prerequisites
- Ensure you have **Python 3.8+** installed. You can check your version with:
  ```bash
  python --version
  ```

### 2. Clone the Repository
```bash
git clone https://github.com/your-username/revenue-drop-analysis.git
cd revenue-drop-analysis
```

### 3. Create a Virtual Environment (Recommended)
Creating a virtual environment ensures that dependencies don't conflict with other projects.
- **Windows:**
  ```bash
  python -m venv venv
  .\venv\Scripts\activate
  ```
- **macOS/Linux:**
  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Run the Application
Launch the Streamlit dashboard by running:
```bash
streamlit run dashboard/dashboard.py
```
The application should automatically open in your default browser at `http://localhost:8501`.
