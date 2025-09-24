📊 Data Visualization & Storytelling – Internship Task 2
🔹 Objective

To create interactive visualizations using Power BI (or Tableau) and deliver insights from a sales dataset by applying the principles of visual storytelling.

🔹 Dataset

Dataset Used: Superstore Sales Dataset (from Kaggle / Tableau sample).

Key Fields: Order Date, Sales, Profit, Quantity, Discount, Category, Sub-Category, State, Region, Product Name.

🔹 Tools

Power BI Desktop (Microsoft Store – free download)

Dataset Format: CSV

🔹 Process / Steps Followed
1. Data Preparation

Downloaded the dataset (SampleSuperstore.csv).

Imported it into Power BI (Get Data → Text/CSV → Load).

Converted Order Date into proper Date format.

Created a new calculated field:

Profit Margin = DIVIDE(SUM(Superstore[Profit]), SUM(Superstore[Sales]))

2. Visualization Creation

Built 5 main visuals in Power BI:

KPI Cards

Total Sales

Total Profit

Profit Margin %

Line Chart

Order Date vs Sales

Shows monthly/ yearly sales trend

Bar Chart (Top 10 Products)

Product Name vs Sales

Filtered Top 10 only

Map

State as Location

Sales (Size) and Profit (Color)

Scatter Plot

X-axis: Sales

Y-axis: Profit

Legend: Category

Size: Quantity

3. Storytelling & Insights

Sales are growing year-over-year.

Technology drives most profit, Furniture drags margin.

California & New York lead in sales, but Texas shows negative profit.

Discounts reduce profitability in some product lines.

4. Report Creation

Arranged all visuals neatly in a single dashboard.

Added a title and summary text box.

Exported final output as PDF report (File → Export → Export to PDF).
