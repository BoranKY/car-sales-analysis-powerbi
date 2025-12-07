# Car Sales Analysis – Power BI Dashboard

![Car Sales Dashboard](images/Car%20Sales.png)

This repository contains a Power BI dashboard for analyzing **car sales performance** by time, region, brand and salesperson.  
The report is designed as a portfolio project to showcase interactive reporting, DAX measures and visual design skills in Power BI.

---

## Dataset & Main Columns

The model is built on a single sales table plus simple lookup tables (regions, products, salespeople).  
Key columns used in the dashboard are:

- **Date / Year–Month (`Tarih`, `YIL-AY`)**  
  Used to track trends over time and compare different periods.

- **Region (`Bölge Adı`)**  
  Geographical area where the sale happened (e.g. Marmara, İç Anadolu).  
  Used for regional comparison and map visuals.

- **Sales Center (`Satış Merkezi`)**  
  Specific branch / store where the sale was recorded.

- **Product / Brand (`Urun Adi`)**  
  Car brand or product group (Audi, BMW, Jeep, Mercedes, Mini, Porsche, Ford, etc.).  
  Used for product mix and brand performance analysis.

- **Salesperson (`Satici Adi`)**  
  Person responsible for the sale; used for ranking and performance evaluation.

- **Sales Quantity (`Satis Adedi`)**  
  Number of units sold.

- **Sales Amount (`Satış Fiyatı`)**  
  Revenue generated from the sale.

- **Cost (`Ürün Maliyeti`)**  
  Cost of the sold units.

From these columns, standard measures such as **Total Sales Quantity**, **Total Sales Amount**, **Total Cost** and **Profit (Sales – Cost)** are calculated with DAX.

> All data is sample / demo data and does not represent any real company.

---

## What the Dashboard Shows

The report includes several views built on top of these columns:

- **Summary KPIs**  
  Cards showing total quantity, total sales amount, total cost and overall profit.

- **Monthly Sales Trend**  
  Column chart displaying how sales evolve over months.

- **Product / Brand Distribution**  
  Donut chart that highlights the share of each brand in total sales.

- **Regional Performance**  
  Map visuals to compare sales volume by region and see which brands are strong in which areas.

- **Salesperson Performance**  
  Table summarizing total quantity, revenue and cost per salesperson.

These visuals are fully interactive and can be filtered by **year–month**, **region** and **product/brand**.

---

## How to Use

1. Download the Power BI file (`.pbit` or `.pbix`) from this repository.  
2. Open it with **Power BI Desktop**.  
3. If you want to plug in your own data, update the data source in **Transform Data (Power Query)** and keep the same column structure.  
4. Refresh the report and explore the visuals using the slicers and filters.

