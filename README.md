# 🌍 Exploratory Data Analysis — World Development Indicators

An Exploratory Data Analysis (EDA) project analyzing key global development indicators across 8 countries from 2000 to 2022, using the World Bank's World Development Indicators (WDI) dataset.

## 📊 Project Overview

This project investigates how countries differ across major socioeconomic and health indicators, identifying trends, correlations, and patterns over a 22-year period.

## 🌐 Countries Analyzed
| Code | Country |
|------|---------|
| USA | United States |
| CAN | Canada |
| DEU | Germany |
| IND | India |
| CHN | China |
| BRA | Brazil |
| ZAF | South Africa |
| JPN | Japan |

## 📈 Indicators Studied
| Indicator | Code |
|-----------|------|
| Life Expectancy at Birth | SP.DYN.LE00.IN |
| GDP per Capita (current US$) | NY.GDP.PCAP.CD |
| Urban Population (% of total) | SP.URB.TOTL.IN.ZS |
| Health Expenditure per Capita (US$) | SH.XPD.CHEX.PC.CD |
| Access to Electricity (% of population) | EG.ELC.ACCS.ZS |

## 🔍 Analysis Performed
- **Data Cleaning** — Handling missing values, filtering by country and indicator, reshaping from wide to long (tidy) format
- **Descriptive Statistics** — Summary stats grouped by country and indicator
- **Missing Value Analysis** — Identifying and handling NaN values across years
- **Trend Analysis** — Life expectancy trends over 2000–2022 using line charts
- **Correlation Analysis** — Life expectancy vs GDP per capita, life expectancy vs health expenditure
- **Latest Year Snapshot (2022)** — Country rankings across all indicators

## 📉 Key Visualizations
- Line chart: Life expectancy trends per country (2000–2022)
- Scatter plot: Life expectancy vs GDP per capita (2022)
- Scatter plot: Life expectancy vs Health expenditure per capita (2022)

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib
- **Environment:** Google Colab
- **Dataset:** World Bank — World Development Indicators (WDI)

## 📁 Files
| File | Description |
|------|-------------|
| `EDA_World_Development_Indicators.ipynb` | Main Jupyter notebook with full analysis |
| `Presentation.pptx` | Project presentation slides |

> **Note:** The dataset (`WDICSV.csv`, ~198MB) is not included in this repo due to GitHub's file size limits.
> You can download it from the [World Bank Open Data portal](https://databank.worldbank.org/source/world-development-indicators).

## ▶️ How to Run
1. Download the WDI dataset from the World Bank link above
2. Upload it to your Google Drive
3. Open `EDA_World_Development_Indicators.ipynb` in Google Colab
4. Update the CSV file path in Cell 1 to match your Drive location
5. Run all cells

## 📚 Course
Exploratory Data Analysis — Master's in Data Science, Montclair State University
