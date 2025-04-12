# 📊 Amazon Sales Data - Exploratory Data Analysis

This project is an exploratory data analysis (EDA) on a dataset of Amazon products and customer reviews. It focuses on uncovering trends in product pricing, discount patterns, customer ratings, and category-wise sales performance. The goal is to derive actionable insights that could support decision-making in e-commerce or retail analytics.

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud

---

## 📁 Dataset Features

The dataset includes the following fields:

- `product_id`  
- `product_name`  
- `category`  
- `discounted_price`, `actual_price`, `discount_percentage`  
- `rating`, `rating_count`  
- `about_product`  
- `user_id`, `user_name`  
- `review_id`, `review_title`, `review_content`  
- `img_link`, `product_link`  

---

## 📈 Key Visualizations

- Top product categories by total sales
- Distribution of discount percentages
- Highest-rated products (with sufficient review count)
- Correlation heatmap of price, rating, and discount
- Word cloud of customer review titles

---

## 🧠 Insights Extracted

- Certain categories dominate in total revenue
- Heavy discounting correlates with higher customer engagement
- Product ratings tend to follow a positively skewed distribution
- Strong correlation between `actual_price` and `discounted_price`
- Review content and titles reveal product quality perceptions

---

## ▶️ How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/amazon-sales-eda.git
   cd amazon-sales-eda
