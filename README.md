# 📊 TCJA Expiration Impact Explorer

**An Interactive R Shiny Dashboard Modeling the Economic Fallout of the 2025 TCJA Expiration**

---

## 🧠 Overview

This policy simulation app explores the economic and fiscal effects of the **Tax Cuts and Jobs Act (TCJA)** expiration in 2025. It’s crafted for:
- 📈 **Economists** modeling macro impacts,
- 🧮 **Data analysts** working with political, tax, or employment datasets,
- 🗳️ **Policy researchers** communicating complex tradeoffs to broader audiences.

You’ll find interactive graphs, adjustable assumptions, and explanatory overlays that make the app **both data-driven and user-friendly.**

---

## 🚀 Tech Stack

| Technology | Purpose |
|------------|---------|
| ![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white) | Core analytics engine |
| ![Shiny](https://img.shields.io/badge/Shiny-1E90FF?style=for-the-badge&logo=RStudio&logoColor=white) | Web dashboard framework |
| ![ggplot2](https://img.shields.io/badge/ggplot2-999999?style=for-the-badge&logo=ggplot2&logoColor=white) | Base plotting system |
| ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white) | Interactive plots |
| ![dplyr](https://img.shields.io/badge/dplyr-5C5C5C?style=for-the-badge&logo=r&logoColor=white) | Data wrangling |
| ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) | Custom app styling |
| ![RMarkdown](https://img.shields.io/badge/RMarkdown-2C3E50?style=for-the-badge&logo=rstudio&logoColor=white) | PDF report generator |

---

## 🎯 App Features

- 📊 **Tax Burden Comparison** — Simulate changes by household income bracket
- 📉 **GDP Forecast** — Model national growth under TCJA expiration
- 📉 **Job Losses** — Project employment contraction post-2025
- 🏦 **SBA Lending Trends** — Evaluate small business borrowing pre-expiration
- 🎚 **Adjustable Sliders** — Tweak assumptions for GDP and tax increases
- 🧾 **Downloadable Reports** — Export your scenario as a formatted PDF
- ✨ **Sleek UI** — Gradient blue/white intro styling + narrative toggle mode

---

## ❓ Why This Matters

> In 2025, over 20+ tax provisions from the TCJA will expire. These changes could:
>
> - Increase tax burdens across households and corporations  
> - Slow GDP growth amid global financial tightening  
> - Dampen capital access for small businesses  
> - Exacerbate employment fragility in tech and retail sectors

**This dashboard empowers decision-makers with customizable, data-driven foresight—before real consequences unfold.**

---

## 🖼️ Screenshots

<details>
  <summary>📈 Tax Burden Chart</summary>
  Compares tax liability by income under current vs. post-TCJA conditions.
</details>

<details>
  <summary>📉 GDP Growth Forecast</summary>
  Models alternate GDP paths using adjustable multipliers.
</details>

<details>
  <summary>🏦 SBA Loan Trends</summary>
  Plots lending activity for small business loans (2018–2024).
</details>

---

## 📦 Installation

```r
# Clone the repo
git clone https://github.com/YOUR_USERNAME/tcja-impact-dashboard.git
cd tcja-impact-dashboard

# Launch app
shiny::runApp()
```

#### R Package Requirements:
```r
install.packages(c("shiny", "ggplot2", "plotly", "dplyr", "reshape2", "rmarkdown"))
```

---

## 🗂️ Directory Structure

```
tcja-impact-dashboard/
│
├── app.R                  # Full Shiny app code
├── www/
│   ├── styles.css         # Custom styling with gradient intro
│   └── tcja-logo.png      # Dashboard logo
├── report_template.Rmd    # RMarkdown for PDF export
└── README.md              # This file
```

---

## 📘 Usage Guide

1. Adjust sliders for GDP and income tax increase.
2. Switch between *data only* and *narrative mode* for annotated explanations.
3. Export your scenario to PDF.
4. Discuss outcomes with policy, business, and economic stakeholders.

---

## ✅ Conclusion

Whether you're advising a congressional committee or analyzing policy impacts in academia, this app offers a fact-driven, interactive approach to modeling one of the **most economically consequential tax shifts in U.S. history.**

> ✅ Data-backed  
> ✅ Adjustable  
> ✅ Public-friendly

---

## 🧠 Suggested Repo Name

```
tcja-impact-dashboard
```

---

### 🎨 styles.css (in www/styles.css)
```css
body {
  background: linear-gradient(to bottom, white, #dceeff);
  font-family: 'Helvetica Neue', sans-serif;
}

#logo-container {
  text-align: center;
  margin-bottom: 20px;
}

#logo-container img {
  max-width: 200px;
  height: auto;
}

h2, .tab-pane .plotly {
  text-align: center;
}

.sidebarPanel, .mainPanel {
  background: rgba(255, 255, 255, 0.85);
  padding: 20px;
  border-radius: 12px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}

.downloadButton {
  background-color: #007bff;
  color: white;
  border-radius: 8px;
  border: none;
}
```
