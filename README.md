# 🛒 Blinkit Grocery Sales Outlet Analysis

## 📌 Project Overview
This project analyzes **Blinkit Grocery Sales** data to uncover patterns in customer preferences, product demand, and outlet performance.  
The insights are presented through an **interactive dashboard** that highlights key KPIs, sales trends, and outlet characteristics.  

The goal is to enable data-driven decision-making for product strategy, outlet expansion, and marketing campaigns.  

---

## 📊 Dataset Description
The dataset contains sales and outlet-related attributes, which were analyzed to build the dashboard.  

| Column Name             | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| `Item_Identifier`        | Unique ID for each product                                                 |
| `Item_Weight`            | Weight of the product                                                      |
| `Item_Fat_Content`       | Fat level of the product (e.g., Low Fat, Regular)                          |
| `Item_Visibility`        | Percentage of product visibility across stores                             |
| `Item_Type`              | Category of the product (e.g., Snacks, Dairy, Fruits & Vegetables)         |
| `Item_MRP`               | Maximum Retail Price of the product                                        |
| `Outlet_Identifier`      | Unique ID for each outlet                                                  |
| `Outlet_Establishment_Year` | Year the outlet was established                                        |
| `Outlet_Size`            | Outlet size (Small / Medium / Large)                                       |
| `Outlet_Location_Type`   | Location tier (Tier 1, Tier 2, Tier 3)                                     |
| `Outlet_Type`            | Type of outlet (Grocery Store, Supermarket Type1/2/3)                      |
| `Item_Outlet_Sales`      | Sales value of the item in the outlet                                      |
| `Outlet_Sales` (derived) | Total sales of the outlet                                                  |
| `Rating` (derived)       | Customer average rating for outlets                                        |

---

## 📈 Dashboard Overview
The Power BI dashboard visualizes the dataset using multiple KPI cards, charts, and filters.

### 🔑 Key Metrics
- **Total Sales** : Overall revenue across outlets  
- **Average Sales per Item** : Typical sales performance  
- **Number of Unique Items** : Total unique products sold  
- **Average Customer Rating** : User satisfaction index  

### 📊 Visual Components
1. **Outlet Establishment Analysis** → Sales vs. Year of establishment  
2. **Item Fat Content Analysis** → Sales contribution of Low Fat vs Regular items  
3. **Item Type Breakdown** → Top-performing categories (e.g., Fruits & Vegetables, Snacks)  
4. **Outlet Size & Location** → Performance comparison across outlet sizes and city tiers  
5. **Outlet Type Comparison** → Supermarkets vs Grocery Stores in terms of sales & visibility  
6. **Interactive Filters** → Filter by outlet type, size, and item category  

---

## 📸 Dashboard Preview
> Upload your dashboard screenshot as `dashboard.png` in the repo root, then the image below will render.  

![Blinkit Dashboard](dashboard.png)

---

## 💡 Business Insights
From the analysis, some key insights are:
- **Low Fat products** generate higher sales than Regular fat products.  
- **Fruits & Vegetables** and **Snacks** dominate item sales.  
- **Medium-sized outlets** in **Tier 3 locations** perform the best.  
- **Supermarkets Type1** show the highest overall sales compared to Grocery Stores.  

---

## 🛠 Tools & Technologies
- **Power BI** → Interactive dashboard creation  
- **Excel/CSV** → Data cleaning & transformation  
- *(Optional)* Python/SQL → Preprocessing & exploratory analysis  

---

## 📂 How to Use
1. Clone the repository:  
   ```bash
   git clone https://github.com/SamyukthaaAnand/Blinkit-Grocery-Sales-Outlet-Analysis.git

2. Open the dashboard.pbix file in Power BI Desktop.
3. Explore the visuals and interact with filters to gain insights.

## 👩‍💻 Author
**Samyuktha Anand**  
🔗 [GitHub Profile](https://github.com/SamyukthaaAnand)

---

## 📜 License
This project is licensed under the **MIT License** – feel free to use and adapt.
