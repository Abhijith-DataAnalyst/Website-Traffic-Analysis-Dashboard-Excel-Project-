# Website-Traffic-Analysis-Dashboard-Excel-Project-
This project analyzes website traffic data from multiple sources to uncover insights about visitor behavior, engagement, and conversion performance across 2022–2023. The dashboard was designed and built in Microsoft Excel, using PivotTables, charts, and KPI cards for interactive analysis.
📁 Dataset Details
File: Data File.xlsx  
Sheets:

Data — raw website traffic data

Pivot — aggregated metrics for visualization

Dashboard — Excel dashboard layout and charts

Key Columns
<img width="922" height="572" alt="image" src="https://github.com/user-attachments/assets/96bf8f9a-1f35-4b8a-9f95-526e4fd9cee8" />


🧹 Data Cleaning & Preparation (Excel)

Performed using Excel formulas, filters, and PivotTable preprocessing:

1.Removed Nulls & Duplicates

Used Filter and Remove Duplicates to clean missing or repeated entries.

2.Data Type Correction

Converted Visitor Date to Excel Date format.

Ensured numeric columns were formatted as percentages or decimals.

3.Standardization

Unified inconsistent naming (e.g., “Paid Search” → “Paid”).

Rounded metrics to two decimal places for clarity.

4.Outlier Handling

Filtered unrealistic bounce rates (>95%) and session durations (<1 sec).

5.Calculated Columns

Added formulas for KPIs:
=SUM(Visitor Count)
=AVERAGE(Session Duration)
=AVERAGE(Pages Per Visit)
=AVERAGE(Bounce Rate %)
=AVERAGE(Goal Conversion Rate %)


6.PivotTable Setup

Created PivotTables for monthly visits, bounce rate, and conversion by channel, campaign, and page.


📈 Dashboard Design (Excel)
🎨 Theme
Color Palette: Indigo, slate grey, white, coral accents

Layout: KPI cards on top, charts below in a 3‑column grid

Font: Georgia (headings) and Verdana (body text)

🧮 KPIs

<img width="922" height="377" alt="image" src="https://github.com/user-attachments/assets/915b47b4-0845-432a-a226-516b31a1c801" />


📊 Charts & Visuals


<img width="927" height="485" alt="image" src="https://github.com/user-attachments/assets/5850ab0b-4b36-4192-a3ef-812e4965af87" />


🔍 Insights
Organic and Direct channels drive the highest conversions (~45%).

Returning visitors contribute ~42% of total traffic, showing strong retention.

Bounce rate peaks early in the year and stabilizes mid‑year.

Campaign 2 performs best with ~50% conversion.

Page 1 consistently ranks top for engagement and conversion.



⚙️ Technical Workflow
Data Import: Raw data entered or imported into Excel.

Data Cleaning: Using filters, formulas, and conditional formatting.

PivotTables: Aggregated by Month, Channel, Campaign, and Page.

Charts: Inserted from PivotTables (Pie, Bar, Line).

Dashboard Assembly: Combined KPIs and charts using cell references and shapes.

Interactivity: Added slicers for Year and Month filters.

🧠 Learning Outcomes
Advanced Excel data cleaning and transformation

PivotTable and chart integration for dashboards

KPI design and layout formatting

Dashboard storytelling and GitHub documentation


🏷️ Author
Abhijith  
Data Analytics Enthusiast | Excel Dashboard Developer


