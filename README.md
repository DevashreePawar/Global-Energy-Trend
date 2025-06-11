# 🌍 Global Energy Trends — INFO 523 Final Project

This repository presents our final project for INFO 523: Data Mining at the University of Arizona. The project explores long-term trends in global energy consumption using data from [Our World in Data](https://ourworldindata.org/energy), with a particular focus on renewable energy adoption, economic influences, and usage-based clustering of countries.

## 👥 Team Members

- Pamela Angulo Martinez  
- Devashree Pawar  
- Akhila Myaka  
- Santhosh Adavala  

---

## 📌 Project Objectives

1. **Renewable Energy Trends**  
   Analyze how renewable energy shares have evolved globally and by continent since 2000.

2. **Economic Correlation**  
   Explore how economic growth (GDP) influences renewable energy adoption (solar, wind, hydro, biofuels) using Random Forest regression.

3. **Country Clustering**  
   Group countries based on fossil and renewable energy usage using K-Means clustering to identify patterns in energy consumption behavior.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Scikit-learn** (ML models & clustering)
- **pycountry-convert** (for ISO to continent mapping)
- **Jupyter Notebook**

---

## 📁 Directory Structure

📦global-energy-trends/
├── data/ # Cleaned dataset (OWID energy data)
├── notebooks/ # Jupyter notebooks for each research question
│ ├── q1_trends_analysis.ipynb
│ ├── q2_gdp_correlation.ipynb
│ └── q3_country_clustering.ipynb
├── visualizations/ # Exported plots and figures
├── requirements.txt # Project dependencies
└── README.md # Project overview


---

## 📊 Key Insights

- **Renewable Share**: Europe is the front-runner in renewable adoption; Africa lags behind due to infrastructure constraints.
- **GDP Link**: Higher GDP correlates with more solar and wind energy use, but biofuels and hydropower rely on geography and natural resources.
- **Clustering**:
  - *Cluster 0*: Balanced energy use (developing & transitioning economies)
  - *Cluster 1*: Low-energy consumers (developing nations)
  - *Cluster 2*: High-energy consumers (industrialized countries)

---

## 🔍 Data Source

- 📥 **[Our World in Data – Energy Dataset](https://ourworldindata.org/energy)**  
  Historical energy metrics from 1900–2022, including consumption by source, GDP, and per-capita energy usage.

---

## 🚀 Future Enhancements

- Build an interactive **Streamlit dashboard** for real-time visualization.
- Incorporate **CO₂ emissions** and energy policy indicators.
- Explore **time-series forecasting** for renewable energy adoption.

---

## ⚙️ Installation

1. Clone the repository  
   ```bash git clone https://github.com/<your-username>/global-energy-trends.git cd global-energy-trends

2. Create a virtual environment and activate it

python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install dependencies
   
pip install -r requirements.txt

4. Launch Jupyter Notebook

jupyter notebook

📬 Contact
For questions or collaboration inquiries, feel free to reach out to Devashree Pawar at devashreepawar@arizona.edu.
