# 📊 Data Analyst Portfolio

Hi! I’m Parker, and I’m transitioning into a career in data analytics. This portfolio is a snapshot of the skills I’m building and the projects I’m creating using tools like Excel, Google Sheets, SQL, statistics, and data visualization.

Each project is a milestone in my learning journey — with more being added regularly.

---

## 🐟 Project: Animal Crossing Fish Analysis

**Tool:** Google Sheets  
**Status:** In Progress  
**Live Link:** [View the dashboard (Google Sheets)](https://docs.google.com/spreadsheets/d/1A56wv6nq97LsTDuI9FVRqqgEcHkCvpHmizy9gRkLVCg/edit?gid=1131253864#gid=1131253864)

**Summary:**  
This self-driven analysis project uses fishing data from *Animal Crossing: New Horizons*. Over the course of July, I manually tracked every fish I caught and categorized it by:
- Time of day (9am–4pm vs. 4pm–9am)
- Shadow size
- Fish species

Pier fish were included as ocean fish. Trash was excluded (my island was clean!), and I assumed a consistent success rate across shadow sizes.

**Key features:**
- 📈 3 interactive dashboards built in Google Sheets
- 🎯 Probability analysis by shadow size and species frequency
- 💰 Average Bells (in-game currency) earned per cast, by time and location

**Quick Insights:**
- 🌊 **Ocean (Night):** Highest Bells per cast — especially for shadow sizes 4 and 6 (with or without fin)
- 🏞 **River:** Spotting size 5 and 6 shadows (vs. misleading size 4) boosts Bell earnings significantly
- 🟣 **Pond:** Low return overall — not ideal unless targeting specific fish

This project demonstrates skills in:
- Manual data collection & cleaning
- Probability and value-based analysis
- Interactive dashboard design
- Clear, concise insight communication

---

### 📉 Data Quality & Limitations

This project analyzes approximately **3,000 fish** caught in *Animal Crossing: New Horizons* during July (Northern Hemisphere).

- **~1,600 fish** were caught during the **day** (9am–4pm)  
- **~1,400 fish** were caught during the **night** (4pm–9am)  
- Each fish was manually logged with shadow size, time of day, and species

While the data reflects one player’s gameplay, the **large sample size** and **consistent tracking** support meaningful insights.

---

### ⚠️ Limitations

This analysis is based on manually collected data during July gameplay in *Animal Crossing: New Horizons*. While the dataset includes over 3,000 fish and distinguishes between daytime and nighttime fishing, the following limitations apply:

- **Rare fish not encountered**: Some fish (e.g., Mahi-Mahi) were not caught during sampling, which may bias shadow size distributions and Bell averages.
- **Pier fish grouped with ocean fish**: For simplicity, fish caught from the pier were categorized as ocean fish.
- **Rain not accounted for**: Rain, which influences fish behavior, were not recorded.
- **Availability-based sampling**: Every fish encountered was caught, meaning the data reflects availability rather than randomness.

Despite these caveats, the data is reliable for uncovering shadow size trends and Bells-per-cast profitability.

---

### 🔧 Next Steps

There are a few areas I'd like to continue refining in this project:

- **Evening out sample sizes**: I’m actively fishing to increase the nighttime sample size to match the daytime dataset, for more balanced comparisons.
- **Dashboard visibility**: I’m exploring layout and formatting changes to fit both the Daytime and Nighttime Probability tables in the visible frame without scrolling.
- **Formula optimization**: Some calculations could be made more efficient by switching from manual row-based formulas to `SUMIF`, `COUNTIF`, or array-based functions for better scalability and clarity.

These improvements aren’t essential for understanding the core insights, but I look forward to refining the project further over time.

---

## 🧪 Upcoming Projects

- 🗃 SQL analysis of public datasets (via BigQuery)
- 📊 Exploratory analysis in R and Tableau
