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

Secondary Analysis:-

1.) Who are the major competitors in the Indian air purifier market, and what are their key differentiators (e.g., price, filtration stages, smart features)?

Ans:-

The major competitors in the Indian air purifier market are:

	 Brand 	       Price Range	     Filtration Stages	   Smart Features	             Special/Technology
0	 Dyson	        Premium	          Multi-stage	        Voice control, app	        Advanced HEPA + carbon filters
1	 Philips  	    Mid-range	        Multi-stage	        Basic app control	          True HEPA, low noise
2	 Xiaomi	        Budget-friendly	  3–4 stages	        Smart connectivity, app	    Efficient CADR, compact design
3	 Coway	        Mid-high	        Multi-stage	        Limited app features	      High CADR, long-lasting filters
4	 Eureka Forbes	Mid-range	        3–4 stages	        Limited smart features	    Plasma ionizer for allergens
5	 Honeywell	    Mid-high	        Multi-stage	        Minimal app features	      Energy-efficient, high CADR
6	 Sharp	        Mid-range	        Multi-stage	        Basic smart features	      Plasmacluster technology
7  Panasonic	    Mid-range	        Multi-stage	        Limited smart features	    Energy-saving features
8	 Samsung	      Mid-range	        Multi-stage	        App connectivity	          Modern design, smart sensors
9	 LG	            Mid-range	        Multi-stage	        App connectivity	          Stylish design, efficient filters

2.) How aware are Indian citizens of what AQI (Air Quality Index) means — and do they understand its health implications?

Ans:-

Awareness of the Air Quality Index (AQI) and its health implications among Indian citizens varies significantly across regions and demographics.

Key Insights:

. General Awareness: A perception study across 17 Indian cities found that approximately 55% of respondents were aware of the term "Air Quality Index" (AQI). Awareness was notably higher among men (52.9%) compared to women (55.5%). "Bengaluru Sustainability Forum"

. Health Understanding: While many are aware of AQI, understanding its health implications is less widespread. For instance, a study highlighted that individuals with limited literacy proficiency had little or no understanding of AQI and its associated health risks. "CCAC Coalition"

. Regional Variations: In urban areas like Delhi, awareness is higher, especially among students, teachers, and professionals. However, in rural regions such as Najafgarh, awareness is lower, with many residents unaware of AQI and its health impacts. "CCAC Coalition"

3.) Which pollution control policies introduced by the Indian government in the past 5 years have had the most measurable impact on improving air quality — and how have these impacts varied across regions or cities?

Ans:-

Over the past five years, the Indian government has implemented several air pollution control policies that have had varying degrees of success across different regions.

Key Policies and Their Impacts:

National Clean Air Programme (NCAP): Launched to reduce particulate matter (PM2.5 and PM10) levels by 40% by 2026 compared to 2017 levels. This program has led to improvements in air quality in several cities, though results have been mixed. For instance, Indore and Jabalpur in Madhya Pradesh have shownsignificant improvements, while Bengaluru's air quality has worsened due to increasing vehicular emissions and road dust. "The Times of India"

Swachh Vayu Survekshan: An annual air quality assessment that ranks cities based on their air quality improvements. Cities like Agra, Kanpur, and Prayagraj have made notable progress, while others like Ghaziabad have also improved their rankings due to measures like dust control and green initiatives. "The Times of India"

Stubble Burning Control Measures: In states like Punjab, Haryana, and Uttar Pradesh, efforts to reduce stubble burning have been ongoing. While some progress has been made, challenges remain due to the practice's prevalence and its contribution to seasonal air pollution. "Wikipedia"

Regional Variations:

. North India: Cities like Delhi continue to face severe air quality issues, with PM2.5 levels often exceeding safe limits. Despite various policies, the region struggles with high pollution levels due to factors like vehicular emissions and crop residue burning. Climate Growth Institute

. South India: States like Karnataka have shown mixed results. While some cities have improved air quality, others like Bengaluru have seen a decline due to rising vehicular emissions and road dust. The Times of India

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
