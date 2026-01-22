# Assignment-1
# The Cost of Living Crisis: A Data-Driven Analysis

## 📊 Overview
This project investigates whether the official Consumer Price Index (CPI) accurately reflects the financial reality faced by college students. Using economic data from the Federal Reserve Economic Data (FRED) API, I constructed a custom "Student Price Index" (SPI) to reveal the hidden inflation gap.

## 🎯 The Problem
The official CPI is a national average that weights housing at ~34% of expenses. However, for college students, **tuition and rent can represent up to 70% of their budget**. This project asks: **Does the official CPI hide the true cost of being a student?**

## 🛠️ Methodology
- **Data Source**: Federal Reserve Economic Data (FRED) API
- **Programming**: Python (pandas, matplotlib, fredapi)
- **Economic Theory**: Laspeyres Price Index methodology
- **Time Period**: 2016-2024 (Base Year: 2016 = 100)
- **Custom Weighting**: 
  - Tuition: 40%
  - Rent: 30%
  - Food (Chipotle): 15%
  - Entertainment (Spotify): 15%

## 🔑 Key Findings
My analysis reveals a **[X]% divergence** between Student Costs and National Inflation from 2016-2024:

- **National CPI (2024)**: ~120 (20% increase)
- **Boston CPI (2024)**: ~125 (25% increase)  
- **Student SPI (2024)**: ~140 (40% increase)

**Conclusion**: Students experience inflation rates nearly **double** the official figures, with tuition being the primary driver.

## 📈 Visualizations
![Student Inflation vs Official CPI](link-to-your-chart.png)

### The Scale Fallacy
One critical insight: comparing raw CPI indices with different base years (e.g., Tuition base 1982 vs. Spotify base 2002) is a "data crime" that creates misleading conclusions. Proper normalization is essential.

## 💡 Technical Highlights
- Normalized multiple economic time series to a common baseline
- Constructed weighted composite indices
- Performed regional comparison analysis (Boston vs. National)
- Demonstrated the importance of proper data normalization

## 🚀 Future Work
- Expand analysis to other metropolitan areas
- Include additional student expense categories (textbooks, healthcare)
- Build interactive dashboard for real-time inflation tracking

## 📂 Repository Structure
```
├── data/                  # Raw and processed data
├── notebooks/             # Jupyter notebooks
├── visualizations/        # Generated charts
└── README.md
```

## 🔗 Connect With Me
[LinkedIn](your-link) | [Portfolio](your-link) | [Email](your-email)

---
*This project was completed as part of [Course Name] at [University Name]*
