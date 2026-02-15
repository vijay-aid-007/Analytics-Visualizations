# OTT Media Content Performance & Trend Analysis Dashboard

## 📌 Project Overview

This project presents an **OTT Media Analytics Dashboard for Netflix**, built using **Power BI**, to analyze the global content library and uncover insights related to content type, genres, maturity ratings, countries, and yearly growth trends.

The dashboard is designed for **business users, analysts, and decision-makers** to quickly understand Netflix’s content distribution and growth patterns through interactive and intuitive visuals.

---

## 🎯 Objectives

* Analyze Netflix’s **content portfolio** (Movies vs TV Shows)
* Identify **top-performing genres and ratings**
* Track **year-wise content growth trends**
* Understand **geographical distribution** of titles
* Provide high-level KPIs for quick decision-making

---

## 🛠 Tools & Technologies

* **Power BI Desktop** – Data modeling & visualization
* **Power Query** – Data cleaning and transformation
* **DAX** – KPI and measure calculations
* **Dataset** – Netflix Movies & TV Shows (CSV)

---

## 📊 Dashboard Structure

The dashboard is designed in **2 interactive pages**:

### 🔹 Page 1: Content Overview

Focuses on high-level KPIs and overall content distribution.

**Key KPIs:**

* Total Titles
* Total Movies
* Total TV Shows
* Number of Genres
* Number of Countries

**Visuals Used:**

* KPI Cards – Quick content summary
* Donut Chart – Movies vs TV Shows
* Map Visual – Titles by Country
* Treemap – Titles by Genre

📈 *Purpose:* Provides a snapshot view of Netflix’s global content library.

---

### 🔹 Page 2: Content Insights & Trends

Focuses on deeper analytical insights and patterns.

**Visuals Used:**

* Line Chart – Titles Added by Year
* Heatmap (Matrix) – Genre vs Maturity Rating
* Bar Chart – Top Genres by Title Count
* Slicers – Type, Rating, Country, Year

📈 *Purpose:* Helps understand content evolution, audience targeting, and genre dominance.

---

## 📐 Why These Visuals?

* **KPI Cards** – Enable quick executive-level understanding
* **Donut Chart** – Simple comparison between Movies & TV Shows
* **Map Visual** – Highlights global content reach
* **Line Chart** – Shows growth trend over time
* **Heatmap** – Reveals which maturity ratings dominate specific genres
* **Treemap** – Efficiently displays genre contribution

Each visual is chosen to balance **clarity, insight, and storytelling**.

---

## 📏 Key DAX Measures (Examples)

```DAX
Total Titles = COUNT(Netflix[show_id])

Total Movies = CALCULATE(COUNT(Netflix[show_id]), Netflix[type] = "Movie")

Total TV Shows = CALCULATE(COUNT(Netflix[show_id]), Netflix[type] = "TV Show")

Titles Added = COUNT(Netflix[show_id])
```

---

## 🔍 Insights Generated

* Netflix has a **higher proportion of movies compared to TV shows**
* **Drama and International content** dominate the platform
* Significant growth observed after **2015**, reflecting OTT expansion
* Mature ratings (TV-MA, R) dominate certain genres

---

## 👤 Target Audience

* Business Analysts
* OTT Strategy Teams
* Content Acquisition Teams
* Data & BI Professionals

---

## 🚀 Future Enhancements

* Viewer engagement metrics (if available)
* IMDb / Rotten Tomatoes rating integration
* Subscription growth correlation
* Advanced DAX-based trend forecasting

---

## ✅ Conclusion

This Netflix OTT Media Dashboard demonstrates **end-to-end BI skills**, from data cleaning and modeling to storytelling with visuals. It showcases the ability to translate raw data into **actionable insights**, making it suitable for **portfolio, interviews, and academic submissions**.

---
