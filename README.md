# 📊 Sales Data Analysis

This project analyzes a sales dataset to uncover insights related to city-wise, product-wise, and month-wise sales performance. The goal is to identify trends, spot opportunities for growth, and provide actionable recommendations based on the data.

---

## 🧭 Project Objective

To analyze sales performance across:
- 🏙️ Different **cities**
- 📅 Various **months**
- 📦 All **products**

And ultimately answer:
- What is selling well?
- Where and when are sales high or low?
- How can we drive more revenue?

---

## 📌 Key Questions (KPIs)

1. Which city has the **highest** and **lowest** sales?
2. Which month is the **best** and **worst** for sales?
3. Which products are **top-selling** and **least-performing**?
4. How can we improve overall **business growth**?
5. Combined analysis: **City + Month + Product** trends.

---

## 🔧 Tools Used

- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **Jupyter Notebook**
- **Visual Studio Code**
- **Git & GitHub**

---

## 🧹 Data Cleaning

- Removed missing and null values
- Dropped irrelevant header rows repeated in data
- Converted `Order Date` to datetime format
- Extracted `Month`, `Hour`, and `City` from date/address columns
- Created new `Sales` column = Quantity × Price

---

## 📊 Visualizations

- 📍 Sales by **City**
- 📆 Sales by **Month**
- 📦 Sales by **Product**
- ⏰ Sales by **Hour**
- 🧠 Combined City + Month + Product patterns

Screenshots of visualizations can be found in the `visuals/` folder _(if added)_.

---

## 📈 Key Insights

- **New York** and **Los Angeles** generated the highest sales.
- **December** had the highest revenue, likely due to holiday shopping.
- **AAA Batteries (4-pack)** sold the most in quantity but low in revenue.
- **Macbooks** contributed significantly to revenue despite low quantity.
- Sales spike during **11 AM** to **7 PM** — ideal for advertising.

---

## 🚀 Business Suggestions

- Increase stock of top-selling products before peak months.
- Promote underperforming products with bundled deals or discounts.
- Run ad campaigns between 11 AM to 6 PM.
- Explore why sales are low in certain cities — delivery issues, competition?

---

## 🗂️ Project Structure

