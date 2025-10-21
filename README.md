# 🚀 Space Race 2.0: Who's Winning the Geopolitical Battle for Space?

**An in-depth geopolitical analysis of 65 years of space exploration (1957-2022)**

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Plotly](https://img.shields.io/badge/Plotly-Interactive-green.svg)](https://plotly.com/)
[![Data](https://img.shields.io/badge/Data-4630_Missions-orange.svg)](data/)

---

## 🎯 The Question

**Who is winning the new space race, and what does the data reveal about shifting global power dynamics?**

After the Cold War space race between the USSR and USA, a new chapter has begun. China, India, and private companies like SpaceX have emerged as major players. This project uses data-driven analysis to determine who truly dominates space exploration today.

---

## 🔍 Key Findings

### **The Three-Era Evolution:**

**1️⃣ Cold War Dominance (1957-1991)**
- USSR reached peak Space Power Index of 97.6 in the 1970s
- USA maintained steady performance (80-85 SPI range)
- Only 2 major players, government-controlled

**2️⃣ Transition Period (1991-2015)**
- Russia's SPI collapsed from 97 → 45 after USSR dissolution
- USA became sole superpower (SPI ~98)
- Commercial space began emerging

**3️⃣ The New Space Race (2016-2022)**
- **China emerged as #2** with SPI of 93.8 (from 23 in 1960s)
- **USA leads** with SPI of 96.7
- Launch frequency DOUBLED: 46 → 111 launches/year
- Costs dropped 89%: $450M → $48M median

### **💥 The Shocking Discoveries:**

**China's Rise:**
- 208 launches (2016-2022) vs. 59 launches (2010-2015) = **252% growth**
- 97.4% success rate (HIGHEST among major powers)
- $29.75M median launch cost (cheaper than SpaceX)

**Russia's Decline:**
- From #1 space power (1960s-1980s) to #3 today
- SPI dropped from 97.6 → 56.7
- Lost technological edge to both USA and China

**The 2030 Projection:**
- If current trends continue, China could launch **~180 missions/year** by 2030
- USA projected at **~140 missions/year**
- Space activity could triple in the next decade

---

## 📊 Visualizations

### **1. Current Space Power Rankings**
![Space Power Index](visualizations/viz1_preview.png)

The Space Power Index (SPI) is a composite metric combining:
- Launch Volume (25%)
- Success Rate (30%)
- Technology Diversity (20%)
- Recent Momentum (25%)

**Top 5 Nations (2016-2022):**
1. 🇺🇸 USA: 96.7
2. 🇨🇳 China: 93.8
3. 🇷🇺 Russia: 56.7
4. 🇪🇺 Europe (ESA): 44.7
5. 🇮🇳 India: 35.0

---

### **2. Historical Evolution: The Rise and Fall of Space Powers**
![Evolution Timeline](visualizations/viz3_preview.png)

Watch how space dominance shifted over 6 decades:
- **1960s-1980s:** USSR peak
- **1990s:** USSR collapse
- **2000s-2010s:** USA dominance
- **2020s:** China rises to challenge USA

---

### **3. USA vs China: The New Space Race**
![USA vs China](visualizations/viz4_preview.png)

Head-to-head comparison shows:
- **2021:** China launched 57 missions vs USA's 45
- Both maintain 90%+ success rates
- USA leads in diversity (commercial sector)
- China leads in frequency (state-directed focus)

---

### **4. Global Launch Activity Map**
![Global Map](visualizations/viz5_preview.png)

Geographic distribution reveals:
- USA: 1,425 total launches (dominant in Western hemisphere)
- China: 368 launches (all post-2000)
- Russia: 308 launches (down from USSR's 1,777)

---

### **5. 2030 Predictions**
![2030 Projections](visualizations/viz7_preview.png)

Based on 2016-2022 trends:
- China projected to reach **~180 launches/year** (8% annual growth)
- USA projected at **~140 launches/year** (5% annual growth)
- Gap could narrow significantly by 2030

---

## 🛠️ Methodology

### **Data Source**
- **Dataset:** Historical space missions (Maven Analytics)
- **Time Period:** 1957-2022 (65 years)
- **Records:** 4,630 missions
- **Variables:** Company, location, date, rocket type, mission status, cost

### **Analysis Pipeline**

**1. Data Enhancement:**
- Mapped 62 organizations to 15 countries
- Classified missions into 6 geopolitical eras
- Added regional groupings (East/West/Middle East)

**2. Space Power Index Creation:**
```
SPI = (Launch_Volume × 0.25) + 
      (Success_Rate × 0.30) + 
      (Tech_Diversity × 0.20) + 
      (Recent_Momentum × 0.25)
```

All components normalized to 0-100 scale.

**3. Temporal Analysis:**
- Calculated SPI for each decade (1960s-2020s)
- Identified inflection points (USSR collapse, China rise)
- Projected trends to 2030 using linear growth models

**4. Comparative Analysis:**
- USA vs China detailed comparison
- Emerging powers growth rate analysis
- Geographic distribution mapping

### **Tools & Technologies**
- **Language:** Python 3.8+
- **Analysis:** Pandas, NumPy
- **Visualization:** Plotly (interactive charts)
- **Platform:** Google Colab
- **Version Control:** Git/GitHub

---

## 📂 Repository Structure
```
space-race-2-geopolitical-analysis/
│
├── README.md                                    # This file
├── space_race_geopolitical_power_analysis.ipynb # Main analysis notebook
│
├── data/
│   ├── space_missions.csv                       # Original dataset
│   ├── space_missions_enhanced.csv              # With country/region features
│   ├── space_power_index_2016_2022.csv         # Current era rankings
│   └── space_power_index_historical.csv        # Historical rankings by decade
│
├── visualizations/
│   ├── viz1_current_space_power_rankings.html
│   ├── viz2_component_breakdown_radar.html
│   ├── viz3_historical_evolution_timeline.html
│   ├── viz4_usa_vs_china_comparison.html
│   ├── viz5_global_launch_map.html
│   ├── viz6_emerging_powers_growth.html
│   └── viz7_2030_projections.html
│
└── requirements.txt                             # Python dependencies
```

---

## 🚀 How to Use This Project

### **View Interactive Visualizations**
Click any HTML file in the `visualizations/` folder to explore the interactive charts.

### **Run the Analysis**
1. Open the notebook in Google Colab
2. Upload the CSV files from `data/`
3. Run all cells to reproduce the analysis

### **Explore the Data**
All processed datasets are available in the `data/` folder with clear documentation.

---

## 💡 Key Insights for Different Audiences

### **For Investors:**
- Private space companies (SpaceX, Rocket Lab) drove 50% cost reduction
- Launch frequency doubled in 7 years, indicating market growth
- China's state-backed approach shows 8% annual growth vs USA's 5%

### **For Policymakers:**
- China's space program is accelerating faster than USA's
- Success rates plateaued at ~93% across all powers (reliability ceiling reached)
- Geographic advantage: Coastal launch sites correlate with higher activity

### **For Students/Researchers:**
- Complete methodology documented in notebook
- All code open source and reproducible
- Demonstrates end-to-end data science workflow

---

## 🎓 What I Learned

This project taught me:
- **Geopolitical data storytelling:** How to transform raw data into compelling narratives
- **Custom metric design:** Creating composite indices (Space Power Index)
- **Interactive visualization:** Building engaging Plotly dashboards
- **Temporal analysis:** Identifying trends and inflection points across decades

---

## 📈 Future Enhancements

Potential extensions of this analysis:
- Add launch cost prediction model (machine learning)
- Include satellite deployment success tracking
- Analyze specific mission types (communication, military, scientific)
- Compare private vs. government success rates
- Add real-time data pipeline for continuous updates

---

## 🤝 Contributing

Found an error? Have suggestions? Open an issue or submit a pull request!

---

## 📜 License

This project is open source under the MIT License.

---

## 👤 About Me

**Ekkarit Gaewprapun**  
Strategic Foresight Leader | AI-Powered Financial Analytics | Futurist Bridging Finance & Data Science | DBA, CMA, FMVA® | Transforming Uncertainty into Competitive Advantage

- 💼 LinkedIn: https://www.linkedin.com/in/ekkarit-gaewprapun-dba-cma-fmva%C2%AE-3153a0151/
- 🌐 Portfolio: Will be up and running soon.
- 📧 Email: ekkarit.g@outlook.com

---

## 🙏 Acknowledgments

- **Data Source:** Maven Analytics - Historical Space Missions Dataset
- **Inspiration:** The ongoing geopolitical competition in space exploration
- **Tools:** Google Colab, Plotly, Python community

---

**⭐ If you found this analysis insightful, please star this repository!**

---

*Last Updated: [Current Date]*
