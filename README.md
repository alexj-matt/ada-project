# 🍺 Brew to Success  
*A data analysis project from the Applied Data Analysis (ADA) course at EPFL*  

A collaborative project exploring what makes a **beer popular**, using data from **BeerAdvocate** and **RateBeer**.  
We present the results of our course project in an **interactive storytelling website** that reveals insights about beer characteristics, seasonality and consumer preferences.  

🔗 **Live Demo:** [Brew to Success Website](https://ajkunas.github.io/ada-template-website/)

---

## 🌟 Motivation

Brewing the perfect beer is a craft of endless possibilities.  
Our mission was to cut through the flood of reviews and extract meaningful insights to ultimately recommend the **best combination of beer characteristics for each month of the year**.  

---

## 🛠️ Approach

We combined **time series analysis, statistical testing, and keyword analysis** to uncover trends in beer ratings.  
Key dimensions explored:

- **Seasonality:** examined how beer popularity fluctuates across months.  
- **Attributes studied:**  
  - Beer Styles (Oktoberfest, American Pale Ale, etc)
  - Alcohol by Volume (ABV)  
  - Geographic location of breweries  
  - Review keywords (aroma, taste, appearance, palate)

---

## 📊 Key Insights

- **Popularity definition**: A beer is “popular” if it gathers a good average (overall) rating with a substantial number of excellent ratings.
- **Consumer focus**: To avoid seasonal mismatches across hemispheres, we narrowed analysis to the **United States**, the largest and most consistent user base.
- **Seasonality**: Beers show clear popularity peaks, like **Oktoberfest** in October, fruity beers in summer and strong dark ales in winter.  
- **Alcohol by Volume (ABV)**: Lower ABVs are favored in summer, while higher ABVs dominate the colder months.  
- **Location**: U.S. breweries, especially California, overwhelmingly dominate monthly top beers.  
- **Keywords analysis**: Seasonal descriptors like *pumpkin* (fall), *citrus* (summer) and *honey* (winter) emerged as strong indicators of popular beers.  

---

## 🍻 The Perfect Beer by Month

| Month      | ABV  | Location | Aroma   | Taste   | Appearance | Palate  |
|------------|------|----------|---------|---------|------------|---------|
| January    | 8.0% | US       | Honey   | Sweet   | Orange     | Light   |
| February   | 8.0% | US       | Honey   | Sweet   | Orange     | Light   |
| March      | 8.0% | US       | Citrus  | Sweet   | Amber      | Medium  |
| April      | 8.0% | US       | Bourbon | Stout   | Dark       | Thick   |
| May        | 8.0% | US       | Bourbon | Stout   | Dark       | Thick   |
| June       | 5.0% | US       | Citrus  | Fresh   | Caramel    | Medium  |
| July       | 5.0% | US       | Pine    | Bitter  | Orange     | Medium  |
| August     | 5.0% | US       | Pine    | IPA     | Orange     | Light   |
| September  | 6.0% | US       | Pumpkin | Spice   | Brown      | Light   |
| October    | 6.0% | US       | Pumpkin | Spice   | Brown      | Light   |
| November   | 8.0% | US       | IPA     | IPA     | Amber      | Medium  |
| December   | 8.0% | US       | IPA     | IPA     | Amber      | Medium  |

---

## 🛠️ Methods & Tools

- **Python (pandas, NumPy, matplotlib)** for data cleaning, statistical analysis, visualization and keyword extraction.
- **Data Sources**: BeerAdvocate & RateBeer reviews
- **Hosting**: GitHub Pages ([Ajkunas/ada-template-website](https://github.com/Ajkunas/ada-template-website))

---

## 📂 Explore the Analysis

The full data analysis behind the storytelling website is available in this repository:

- [`notebooks/`](notebooks/) — Jupyter notebooks with the complete analysis pipeline  
- [`plots/`](plots/) — generated visualizations used in the data story  
- [`analysis/README.md`](analysis/README.md) — the original, detailed project README with methodology, preprocessing steps, and team organization  

⚠️ *Note: Datasets are too large to host on GitHub, but the notebooks and graphs remain available for inspection.*  

---

## 🙌 Team

This project was completed by **Tim Brunner, Dana Kalaaji, Cyril Golaz, Ajkuna Seipi & Alexander Odermatt**  
as part of the **Applied Data Analysis (ADA)** course at **EPFL**.  

---

✨ *Say goodbye to the same-old beer in your fridge, and let the data guide you to the brew that matches the mood of the month!* 🍻  
