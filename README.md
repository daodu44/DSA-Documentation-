# DSA-DOCUMENTATION
# 🛒 Product & Customer Review Analysis – Excel + Power BI

Welcome! This is a data analytics project where I explore product performance and customer sentiment using **Excel** and **Power BI**. The goal? To uncover **actionable insights** from e-commerce product and review data that can guide **product improvement**, **marketing strategies**, and **customer engagement**.

---

## 📂 Project Context

As a **Junior Data Analyst** at **RetailTech Insights**, I was tasked with analyzing real-world e-commerce data (similar to Amazon) to:
- Understand customer feedback trends.
- Evaluate product performance across categories.
- Explore how discounts affect customer satisfaction.
- Build an **interactive dashboard** for easy decision-making.

---

## 🧠 Tools Used

| Tool         | Purpose                         |
|--------------|----------------------------------|
| **Excel**    | Data cleaning, Pivot Tables, EDA |
| **Power BI** | Interactive dashboard + Visuals  |

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Steps Taken:
- Cleaned and structured data using Excel.
- Created Pivot Tables to analyze:
  - Total number of reviews per product category.
  - Number of products listed per category.
  - Average rating per category.
  - Review sentiment trends and discount impact.
- Grouped discounts into buckets for easy comparison.
- Built a Power BI dashboard to visualize key insights interactively.

### 📈 Key Metrics:
- Total Reviews by Category  
- Average Ratings per Product  
- Products with Highest Review Counts  
- Discount Bucket Analysis  
- Sentiment Distribution  

---

## 🔍 Key Insights

- 🏆 **Beauty and Electronics** categories had the highest average ratings (4.5+).
- ⚠️ Some products with high discounts (>50%) received **lower ratings**, indicating a trade-off between affordability and quality.
- 🔥 A small number of products generated the **most reviews**—ideal for marketing or testimonials.
- 🧠 **Longer reviews** often showed stronger emotional tone—either very positive or very negative.
- 🛍️ Some categories (e.g. Home & Kitchen) had **high review volume** but average ratings, hinting at quality variation within the category.

---

## 📊 Power BI Dashboard Highlights

![Dashboard Preview](visuals/dashboard_preview.png)

Features:
- Dynamic filtering by Category, Rating, Discount Bucket.
- Bar charts for top reviewed and top rated products.
- Heatmaps for category performance.
- Review count vs. rating correlation.

---

## 📁 File Structure


## 📊 Exploratory Data Analysis (EDA)

The project involved a deep-dive analysis of product and customer review data from an e-commerce platform (Amazon-like), using **Excel** and **Power BI** to extract insights and build a dynamic dashboard.

### Data Source:
- Cleaned and preprocessed product and review datasets provided in `.xlsx` format.
- Fields included: product ID, name, category, price, discount %, number of reviews, rating, and review sentiment (text).

### EDA Steps (Excel + Power BI):
- ✅ Checked for missing values and duplicates (cleaned in Excel).
- ✅ Created pivot tables to:
  - Count reviews per product category.
  - Calculate average ratings by category.
  - Analyze discount impact on product ratings.
- ✅ Created new columns:
  - Discount buckets (0–13%, 14–30%, etc.)
  - Rating groupings
- ✅ Built charts in Power BI:
  - Review trends
  - Category-wise performance
  - Top-rated vs. most-reviewed products

### Key Metrics Calculated:
- Average rating per category
- Total reviews per category
- Number of products per category
- % discount impact on product perception

## 🔍 Key Insights & Visualizations

### 📌 Insights:
- **High-rated categories**: Beauty and Electronics consistently scored 4.5+ average ratings.
- **Low-performing products**: Some items had 50+ reviews but low ratings (<3), suggesting major quality issues.
- **Discount ≠ Satisfaction**: Heavily discounted products (over 50%) showed mixed ratings—some customers felt they got value, others flagged poor quality.
- **Engagement Hotspots**: Few products had a *disproportionate number of reviews*, ideal for targeted campaigns or testimonials.
- **Review Length = Emotion**: Longer reviews tended to reflect strong sentiments—either highly satisfied or frustrated users.

### 📊 Visualizations:
- **Excel**:
  - Pivot table summary by category
  - Discount bucket chart
  - Category review heatmap
- **Power BI Dashboard**:
  - Interactive slicers (Category, Rating Bucket, Discount Range)
  - Review sentiment overview
  - Top 10 reviewed products (bar chart)
  - Rating distribution histogram

📁 product-review-analysis/
│
├── 📄 README.md
├── 📁 data/
│   ├── cleaned_reviews.xlsx
│   └── product_data_raw.xlsx
│
├── 📁 excel_analysis/
│   └── pivot_dashboard.xlsx
│
├── 📁 powerbi_dashboard/
│   └── ProductInsights.pbix
│
├── 📁 visuals/
│   ├── rating_distribution.png
│   ├── top_products_chart.png
│   └── category_analysis.png


---

## 🚀 How to Explore the Project

1. **Excel Users**: Open `excel_analysis/product_pivot_summary.xlsx` to view the pivot tables and discount bucket analysis.
2. **Power BI Users**: Open `powerbi_dashboard/ProductInsights.pbix` in Power BI Desktop to interact with the dashboard.
3. **Notebooks & Scripts**: This project focused on low-code tools, but scripts can be added later for automation.

---

## 🙋🏽‍♀️ About Me

Hi, I’m **Modupe Daodu** – a data analyst who’s passionate about using numbers to tell real stories. I love transforming messy data into meaningful visuals and making insights *make sense*. 📊✨

- 💼 Role: Junior Data Analyst
- 📍 Based in Lagos, Nigeria
- 💌 Let’s connect: [https://www.linkedin.com/in/modupe-daodu-831075207/](#) | [daodu44@gmail.com](#)

---

## ⭐ Feedback or Collaboration?

Wanna give feedback? Have a similar project in mind? Let’s build together!

