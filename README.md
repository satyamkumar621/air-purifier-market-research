# air-purifier-market-research

# 🌍 Air Purifier Market Fit Research – AirPure Innovations  

## 📌 Project Overview  
This project investigates **India’s air quality crisis** and provides **data-driven recommendations** for developing air purifiers.  
It was conducted for **AirPure Innovations**, a startup designing purifiers aligned with local pollution patterns, consumer needs, and health impacts.  

The analysis focuses on answering four critical business questions:  
1. **Pollutant Targeting** – Which pollutants (PM2.5, PM10, NO₂) should the purifier filter?  
2. **Essential Features** – What features (real-time AQI, portability, IoT integration) are most important?  
3. **High-Demand Cities & Market Size** – Which cities show strongest demand and how large is the potential market?  
4. **R&D Alignment** – How can product development align with localized pollution sources and health outcomes?  

---

## 🎯 Objectives  
- Map **severity of AQI** across Indian cities.  
- Correlate **health impacts** (respiratory illness) with pollution.  
- Identify **demand triggers** such as traffic emissions & seasonal smog.  
- Estimate **market potential & product penetration**.  
- Deliver **strategic recommendations** for design & market entry.  

---

## 📊 Datasets Used  
- **AQI Data (`aqi.csv`)** – Daily AQI values, pollutants, city & state details.  
- **Health Data (`idsp.csv`)** – Reported cases & outbreaks (used to link AQI with diseases).  
- **Vehicle Data (`vahan.csv`)** – Vehicle registrations by type & fuel (proxy for emissions).  
- **Population Projections (`population_projection.csv`)** – Demographic forecasts for market sizing.  

---

## 🛠️ Tools & Methods  
- **Python**: Pandas, NumPy, Matplotlib, Seaborn for data processing & visualization.  
- **Exploratory Data Analysis (EDA)**: To detect patterns in AQI, pollutants, health data.  
- **Correlation Studies**: Linking AQI with health burden.  
- **Market Sizing**: Using penetration models × population × AQI severity.  
- **Conceptual Dashboard**: Designed for top management & product teams.  

---

## 📌 Key Insights  
- **Target Pollutants**:  
  - PM2.5 & NO₂ dominate Tier 1 cities (Delhi, Kanpur, Patna).  
  - PM10 prevalent in secondary cities (e.g., Amravati).  
- **Essential Features**: HEPA + Activated Carbon filters, IoT-enabled AQI display, portable design.  
- **High-Demand Cities**:  
  - Delhi (~150k units), Kanpur (~80k), Patna (~60k), Amravati (~75k).  
- **Seasonal Triggers**: Demand spikes during **winter smog (Oct–Feb)**.  
- **R&D Focus**: Localized purifier designs to reduce costs & avoid over-engineering.  

---

## 📈 Deliverables  
- ✅ **Jupyter Notebook** – [`Air_Purifier_Development.ipynb`](./Air_Purifier_Development.ipynb)  
- ✅ **Detailed Report (PDF)** – [`Air.pdf`](./Air.pdf)  
- ✅ **Dashboard (conceptualized)** – AQI, health, and demand mapping for strategy teams.  
- ✅ **Strategic Recommendations** – R&D alignment, market entry, and product design.  

---

## 🚀 Strategic Recommendations  
- Launch pilots in **Delhi & Kanpur** during peak pollution (Oct–Feb).  
- Develop **modular purifier models** (HEPA + Activated Carbon).  
- Position purifiers as a **health necessity**, not just a lifestyle product.  
- Run **targeted marketing campaigns** during seasonal AQI spikes.  

---

## 🏁 Conclusion

India’s worsening air quality represents both a public health emergency and a market opportunity.
This project demonstrates that data-driven insights are essential for building relevant, efficient, and scalable air purifiers.

. Pollutant targeting (PM2.5, PM10, NO₂) ensures that product design directly addresses the most harmful pollutants.

. Consumer-driven features like real-time AQI monitoring, IoT integration, and portability make the purifier both practical and appealing.

. Market prioritization highlights Delhi, Kanpur, and Patna as immediate high-demand cities, with seasonal demand spikes during winter smog.

. R&D alignment reduces costs and risks by focusing only on localized pollution needs instead of over-engineering.

By combining AQI analytics, health data, vehicle emissions, and population projections, AirPure Innovations can strategically position itself as a leader in India’s growing $100M+ air purifier market.
The outcome is a clear roadmap for product development, market entry, and long-term scalability.

---

## 📂 Repository Structure
├── Air_Purifier_Development.ipynb # Python notebook with full analysis
├── Air.pdf # Detailed project report
├── README.md # Project documentation
└── data/ Datasets: aqi.csv, idsp.csv, vahan.csv, population_projection.csv


---

## ⚙️ Setup Instructions  
To run the notebook locally:  

# Clone repository
git clone https://github.com/satyamkumar621/air-purifier-market-research.git
cd air-purifier-market-research

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook

Recommended Python version: 3.9+

📢 Acknowledgements

. Datasets: AQI, Health (IDSP), Vehicle (VAHAN), Population projections.

. Inspiration: Dataful platform, Codebasics challenge, and India’s urgent air quality crisis.
