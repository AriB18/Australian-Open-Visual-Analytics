# Australian-Open-Visual-Analytics
Visual analytics of 120 years of Australian Open Tennis Championship data. Explores champion win ratios, player evolution, and global participation using tree maps, geo maps, parallel coordinates, and scatter plots in Tableau.


# 🎾 Australian Open Visual Analytics

> **Data Visualization and Visual Analytics of 120 Years of Australian Open Tennis Championship (1905-2024)**
---

## 📊 Dataset Overview

| Metric | Value |
|--------|-------|
| **Time Span** | 1905 - 2024 |
| **Total Finals Analyzed** | 210 |
| **Men's Finals** | 112 |
| **Women's Finals** | 98 |
| **Unique Champions** | 110 |
| **Countries Represented** | 22 |

> ⚠️ **Note:** Data for 2020 and 2021 is excluded due to COVID-19 pandemic disruptions.

---

## 🏆 Key Statistics

### Top 10 Champions by Titles

| Rank | Player | Titles | Country |
|------|--------|--------|---------|
| 1 | Novak Djokovic | 10 | 🇷🇸 Serbia |
| 2 | Serena Williams | 7 | 🇺🇸 United States |
| 2 | Margaret Smith | 7 | 🇦🇺 Australia |
| 4 | Roy Emerson | 6 | 🇦🇺 Australia |
| 4 | Nancye Wynne Bolton | 6 | 🇦🇺 Australia |
| 4 | Roger Federer | 6 | 🇨🇭 Switzerland |
| 7 | Daphne Akhurst | 5 | 🇦🇺 Australia |
| 8 | Ken Rosewall | 4 | 🇦🇺 Australia |
| 8 | Monica Seles | 4 | 🇺🇸 United States |
| 8 | Steffi Graf | 4 | 🇩🇪 Germany |

### Top Countries by Titles

| Rank | Country | Titles |
|------|---------|--------|
| 1 | 🇦🇺 Australia | 94 |
| 2 | 🇺🇸 United States | 43 |
| 3 | 🇨🇭 Switzerland | 10 |
| 3 | 🇷🇸 Serbia | 10 |
| 5 | 🇬🇧 United Kingdom | 8 |
| 6 | 🇩🇪 Germany | 7 |
| 7 | 🇸🇪 Sweden | 6 |
| 8 | 🇧🇾 Belarus | 4 |
| 8 | 🇨🇿 Czechoslovakia | 4 |
| 10 | 🇷🇺 Russia | 3 |

---

## 📈 Visualizations

This project includes four main visualization types:

### 1. Tree Map
Hierarchical visualization of player win ratios organized by country and gender. Rectangle sizes represent win ratios, enabling quick identification of top performers within each category.
<img width="1920" height="1080" alt="Screenshot 2024-05-01 161658" src="https://github.com/user-attachments/assets/dd0bf156-e375-4577-bc88-dfbf903553b3" />


### 2. Geographic Map (Geo Map)
Dual-axis map combining symbol maps and choropleth visualization to show:
- **Symbol Map:** Champion countries with wins represented by bubble size
- **Geo Map:** Runner-up countries with games lost shown through color intensity

### 3. Parallel Coordinates
Multi-dimensional visualization tracking player performance across all five sets, color-coded by gender (blue for men, orange for women). Reveals patterns in match progression and set dynamics.

### 4. Scatter Plot
Analysis of top players (5+ titles) showing win ratios by country with gender differentiation. Enables comparison of elite player performance metrics.

---

## 🗂️ Repository Structure

```
australian-open-visual-analytics/
│
├── 📄 README.md                    # This file
├── 📊 25015126_A2.twbx             # Tableau workbook with all visualizations
├── 📑 25015126_A2.xlsm             # Excel data with calculations and macros
├── 📝 25015126_A2.pdf              # Detailed analysis report
│
└── 📁 docs/
    └── 📁 images/                  # Visualization screenshots
```

---

## 🛠️ Tools & Technologies

- **Tableau Desktop** - Primary visualization tool
- **Microsoft Excel** - Data preprocessing and calculations
- **VBA Macros** - Automated data transformations

---

## 📋 Data Attributes

| Attribute Type | Examples |
|---------------|----------|
| **Nominal** | Champion, Nationality, Country, Runner-up |
| **Ordinal** | Year |
| **Categorical** | Gender (Men's/Women's) |
| **Text** | Match Scores |
| **Ratio** | Win Ratios (per set and total) |

---

## 🔍 Key Insights

1. **Dominance of Australian Players:** Australia leads with 94 titles, largely due to home advantage and historical tennis culture.

2. **Novak Djokovic's Record:** With 10 titles, Djokovic holds the record for most Australian Open men's singles titles.

3. **Global Participation:** 22 countries have produced Australian Open champions, with Europe showing the highest regional participation.

4. **Set Patterns:** The parallel coordinates reveal that 5-set matches (men's) often show distinct patterns of momentum shifts.

5. **Win Ratio vs. Titles:** Interestingly, the highest title winners don't always have the highest average win ratios, suggesting consistency matters more than dominance in individual matches.

---

## 🚀 Getting Started

### Prerequisites
- Tableau Desktop or Tableau Reader (for .twbx file)
- Microsoft Excel (for .xlsm file)

### Viewing the Visualizations
1. Clone this repository
2. Open `25015126_A2.twbx` in Tableau
3. Navigate through the dashboard tabs to explore different visualizations

---

## 📖 Documentation

For detailed analysis methodology and findings, refer to the [Analysis Report (PDF)](25015126_A2.pdf).

---

## 👤 Author

**Aryan Bansal**  
Program: Master of Business Analytics (Extension)  
University of Technology Sydney

---


## 🙏 Acknowledgments

- University of Technology Sydney - DATA VISUALISATION AND VISUAL ANALYTICS course
- Australian Open for historical tournament data
- Tableau community for visualization best practices

---

<p align="center">
  <i>Made with ❤️ for Data Visualization</i>
</p>
