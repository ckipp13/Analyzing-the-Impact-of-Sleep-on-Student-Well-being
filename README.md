# Analyzing-the-Impact-of-Sleep-on-Student-Well-being--Sleep-Deprived Dreams

**Sleep-Deprived Dreams** is a data-driven research project that explores the relationships between sleep quality, mental health, and academic performance in students. Leveraging R and machine learning-based survey data, the project investigates how chronic sleep deprivation affects emotional and cognitive well-being.

## 📊 Project Overview

Modern students face mounting academic and extracurricular demands, often at the expense of adequate sleep. Our analysis reveals how this tradeoff leads to increased anxiety, depression, and lower academic performance.

### ✨ Objectives
- Examine correlations between sleep quality and mental health factors like depression and anxiety.
- Investigate how self-esteem, academic achievement, and extracurricular load influence sleep.
- Provide actionable insights for promoting student well-being.

## 🛠️ Tools & Role

- **Role:** Colton - Lead Developer & Data Analyst, Taryn - Data Engineer, Faique - Communications, Hayford & Arvin- Graphic Designer
- **Tools:** R, RStudio, `ggplot2`, `tidyverse`, `dplyr`, `corrr`  
- **Core Tasks:**
  - Implemented data import, cleaning, and transformation pipelines.
  - Produced statistical summaries and correlation heatmaps.
  - Created custom plots to visualize the relationships between variables.

## 🧪 Methods

- **Data Source:** Stress Level Dataset from a [Springer case study](https://link.springer.com/article/10.1007/s44163-024-00169-6#data-availability)
- **Key Steps:**
  - Cleaned and normalized diverse mental health metrics (e.g., anxiety, depression, self-esteem).
  - Used `cor()` and `corrr::correlate()` for correlation matrices.
  - Built visualizations to depict statistically significant relationships.

> ⚠️ **Disclaimer**: Some dataset variables lacked scale documentation; results should be interpreted with caution.

## 📉 Notable Correlations

- **Negative:**
  - Depression ⬆ → Sleep Quality ⬇
  - Anxiety ⬆ → Sleep Quality ⬇
  - Extracurricular Activities ⬆ → Sleep Quality ⬇
- **Positive:**
  - Academic Performance ⬆ → Sleep Quality ⬆
  - Self-Esteem ⬆ → Sleep Quality ⬆

These trends highlight sleep deprivation as both a cause and consequence of poor academic and mental outcomes.

## ⚙️ Challenges

- Initial dataset from Kaggle was discarded due to artificial generation.
- Final dataset had vague or missing scaling, requiring manual inspection.
- Time constraints limited deeper modeling and advanced diagnostics.

## 🧠 Conclusion

Students’ pursuit of success should not come at the cost of their sleep and mental health. Our findings support a more balanced approach to student life—one that values sleep as a pillar of academic and emotional well-being.
