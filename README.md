📊 Sales Performance Intelligence Dashboard — 2025
Turning raw sales data into decisions, with AI-assisted dashboard development
A business intelligence case study: How can a year of transactional sales data be transformed into an interactive decision-support experience that helps leaders understand revenue, profitability, product performance, geography, and sales execution?

This project turns an Excel sales dataset into a modern, interactive web dashboard developed with the assistance of Claude AI. It combines quantitative analysis with an executive-friendly visual experience: headline KPIs, time trends, category and city comparisons, sales-representative performance, discount analysis, payment mix, and product rankings.

The principle behind the project: a dashboard should do more than display numbers. It should help people ask better questions, find patterns, and decide where to investigate next.

📌 Executive snapshot
The figures below are calculated from the full supplied Excel dataset (Sales_Data_2025.xlsx), before any dashboard filters are applied.
Business metric	Result
Reporting period	1 Jan – 31 Dec 2025
Transaction rows	1,287
Unique order IDs	1,287
Total sales	₹9.33 crore
Total profit	₹1.87 crore
Average order value	₹72,496.65
Units sold	3,889
Overall profit margin	20.00%
Cities represented	5
Product categories	3
Product names	9
Sales representatives	4
Payment methods	4


Metric definitions: Total sales and profit are sums of Total_Sales and Profit; total orders count distinct Order_ID; average order value is total sales divided by distinct orders; profit margin is total profit divided by total sales. Values are rounded for presentation.
Important interpretation note: the video demonstrates interactive filter states. Dashboard KPIs may therefore show a selected subset of the data. The executive snapshot above represents the complete workbook, not a particular filtered view.

🎯 Business questions this dashboard helps investigate
- How much revenue and profit did the business generate?
- How do sales change month by month?
- Which cities and regions contribute the most sales?
- How do product categories compare on sales and profit?
- How does sales performance differ by representative?
- What share of sales comes through each payment method?
- Which five products lead sales, and which five rank lowest?
- How do discounts and profit appear to move together in this dataset?
- How do the answers change when the user filters by date, city, category, or representative?
These are descriptive and diagnostic questions. The dashboard supports investigation; it does not, by itself, establish causation or forecast future performance.

🧭 Dashboard experience
1. Executive KPI cards
- Total Sales — sales value for the current selection.
- Total Profit — profit value for the current selection.
- Total Orders — number of orders in the current selection.
- Average Order Value (AOV) — sales divided by orders for the current selection.
The KPI cards provide a quick performance read before the user explores the underlying charts.
2. Monthly sales trend
A line chart compares monthly sales and profit to help identify stronger and weaker periods and potential seasonality worth investigating.
3. Category performance
A category chart compares Clothing, Electronics, and Furniture. It helps users assess the relative contribution of each category and explore the balance between revenue and profit.
4. City-wise sales
A bar chart compares sales across Bangalore, Pune, Delhi, Mumbai, and Hyderabad, making geographic differences easier to scan.
5. Sales representative performance
A bar chart compares sales across Ajay, Rahul, Sneha, and Pooja. This is a starting point for performance review, not a complete evaluation of individual effectiveness; context such as targets, territory potential, and account mix is not present in the supplied dataset.
6. Profitability: profit vs. sales
A scatter-style comparison helps users inspect the relationship between sales value and profit. It can highlight records or groups that merit a closer look.
7. Discount impact on profit
The dashboard visualizes profit alongside discount levels. This helps frame a useful commercial question: are discounts associated with a different profit outcome? The chart is descriptive; discount decisions should not be based on correlation alone.
8. Payment method distribution
A pie chart shows the mix across Cash, Debit Card, UPI, and Credit Card.
9. Top five and bottom five products
Rankings make it easy to identify the highest- and lowest-sales products within the current filter selection. “Bottom five” means lowest sales among the products in this dataset, not necessarily loss-making products.
10. Order-level detail
The dashboard includes a detailed order view so users can move from high-level patterns toward individual records.

🔎 Findings from the full 2025 workbook
Revenue and profitability
The dataset records ₹9.33 crore in sales and ₹1.87 crore in profit, with an overall profit margin of approximately 20.00%. This gives the business a useful baseline against which filtered periods, categories, cities, and sales representatives can be compared.
Geographic performance
City	Sales	Orders
Bangalore	₹2.14 crore	276
Pune	₹1.87 crore	263
Delhi	₹1.83 crore	249
Mumbai	₹1.77 crore	253
Hyderabad	₹1.72 crore	246

Observation: Bangalore is the highest-sales city in the supplied data, at approximately ₹2.14 crore. Hyderabad is the lowest of the five by sales, at approximately ₹1.72 crore. This is a prompt for follow-up analysis—not proof that one city is better or worse operationally.
Category performance
Category	Sales	Profit	Orders
Electronics	₹3.16 crore	₹63.62 lakh	428
Furniture	₹3.15 crore	₹63.44 lakh	443
Clothing	₹3.02 crore	₹59.54 lakh	416

Observation: Electronics has the highest sales total, while Furniture has the highest order count. Category-level profit margins are close to one another in this dataset, around 19.7%–20.2%.
Sales representative performance
Sales representative	Sales	Profit	Orders
Ajay	₹2.58 crore	₹50.75 lakh	339
Rahul	₹2.43 crore	₹49.70 lakh	326
Sneha	₹2.17 crore	₹43.08 lakh	306
Pooja	₹2.16 crore	₹43.07 lakh	316

Observation: Ajay leads the four representatives in total sales and order count. Rahul has the highest approximate profit margin among the four, at about 20.5%. A fair performance comparison should also consider quotas, territory, customer mix, and tenure, none of which are supplied here.
Monthly sales pattern
- July is the highest-sales month at approximately ₹94.32 lakh.
- October follows at approximately ₹93.16 lakh.
- May is the lowest-sales month at approximately ₹62.11 lakh.
  
These differences can guide questions about promotions, seasonality, inventory, and sales activity. The workbook alone does not explain why the peaks or trough occurred.
Product rankings
- Highest-sales product: Headphones — approximately ₹1.26 crore.
- The next highest are Sofa (₹1.07 crore), Table (₹1.04 crore), Chair (₹1.04 crore), and T-Shirt (₹1.01 crore).
- Lowest-sales product: Mobile — approximately ₹94.91 lakh, followed by Laptop (₹95.76 lakh), Jacket (₹99.30 lakh), Jeans (₹1.01 crore), and T-Shirt (₹1.01 crore).
  
The differences between products are relatively modest compared with the overall sales total. Low ranking does not automatically imply low profitability, poor customer satisfaction, or a product that should be discontinued.
Payment mix
Cash has the largest sales total at approximately ₹2.47 crore, followed by Debit Card (₹2.37 crore), UPI (₹2.26 crore), and Credit Card (₹2.22 crore). This describes the supplied transactions; it should not be interpreted as a recommendation to prefer one payment method without considering fees, risk, customer preference, and settlement timing.
Discount analysis — an important caveat
The workbook contains discount values of 0%, 5%, 10%, and 15%, with a mean recorded discount of approximately 7.33%. In this dataset, the simple correlation between discount percentage and profit is approximately −0.04, a very weak linear relationship.

That correlation does not prove discounts have no effect. Profit may also depend on product mix, units, price, and other factors. A stronger analysis would compare like-for-like products and periods, calculate profit per unit and margin by discount band, and ideally use a controlled experiment.

🧹 Data and analytical process
1. Source review — inspected the supplied Excel workbook and its column structure.
2. Data validation — checked the reporting dates, missing values, and order-ID uniqueness.
3. Metric definition — defined sales, profit, orders, average order value, and profit margin so KPI interpretation is explicit.
4. Aggregation — summarized the data by month, city, region, category, product, representative, and payment method.
5. Visual design — organized the dashboard around headline KPIs, trend analysis, comparisons, diagnostic views, rankings, and order details.
6. Interactivity — the supplied prompt specifies date-range, city, category, and sales-representative filters; the recording shows filters being changed and KPI/chart values responding.
7. Interpretation — translated the aggregates into observations and follow-up questions while avoiding unsupported causal claims.
Data quality checks performed on the supplied workbook
- 1,287 rows and 14 columns.
- Reporting dates span 1 January through 31 December 2025.
- No missing values were found in the 14 supplied columns.
- No duplicate Order_ID values were found.
- 1,287 distinct order IDs were present.
These checks support the calculations above, but they do not independently verify whether the underlying business records are accurate or complete.

🧰 Technology and approach
- Source data: Microsoft Excel (Sales_Data_2025.xlsx)
- AI-assisted development: Claude AI
- Requested implementation stack in the prompt: HTML, CSS, JavaScript
- Visualization library: the original prompt suggested Chart.js, Recharts, or D3.js; the exact library used by the final dashboard should be confirmed from its source code.
- Experience goals: responsive layout, interactive filters, hover tooltips, KPI cards, chart grids, and a business-intelligence-style interface.
Transparency note: the prompt describes the desired implementation; it is not proof of the exact code or library ultimately used. Add the dashboard source code and confirm the library before publishing technical claims as verified facts.

🤖 AI development prompt
The dashboard was generated with an AI prompt asking Claude to act as a professional data analyst and full-stack dashboard developer. The prompt specified:
- A modern web-based sales dashboard built from an uploaded Excel/CSV file.
- KPI cards for Total Sales, Total Profit, Total Orders, and Average Order Value.
- City, category, sales-representative, and monthly trend visualizations.
- Profitability analysis, discount analysis, payment distribution, and top/bottom five products.
- Date, city, category, and representative filters.
- Dynamic chart updates and detailed hover tooltips.
- A responsive desktop/mobile interface.
- HTML, CSS, and JavaScript, with a modern chart library and browser-ready output.
The full original prompt is preserved in the project file Dahsboard Prompt.docx. Keep it in the repository if you want others to reproduce or extend the workflow.

💡 Business implications and next questions
The current analysis points to several useful follow-ups:
1. Investigate city opportunity: understand what drives the gap between Bangalore and Hyderabad—customer count, average order value, product mix, or sales coverage.
2. Study product economics: compare margin, units sold, and discount by product before changing inventory or promotion strategy.
3. Review the July and October peaks: check campaigns, seasonality, stock availability, and sales activity.
4. Build a target-aware sales scorecard: add quota attainment, territory potential, and customer mix for a fairer view of representative performance.
5. Improve discount measurement: test discounts against comparable products and periods; track incremental sales and incremental profit.
6. Add targets and comparisons: include budget/target, prior-year results, and variance-to-target when reliable historical or planning data becomes available.
7. 
⚠️ Scope and limitations
- This is a descriptive analysis of the supplied 2025 workbook, not an audited financial statement.
- The data covers one calendar year, so year-over-year comparisons are not available from this file alone.
- The workbook does not include targets, cost breakdowns, customer acquisition costs, returns, inventory, marketing campaigns, or territory potential.
- The discount analysis is observational and does not establish causality.
- Dashboard screenshots may reflect active filters and therefore differ from full-dataset totals.
- The final implementation's exact chart library and deployment setup should be confirmed from the dashboard source code.
  
📁 Suggested repository structure
sales-performance-dashboard/
├── README.md
├── index.html                  # Dashboard app (if delivered as a single file)
├── Sales_Data_2025.xlsx        # Source dataset (share only if permitted)
├── Dahsboard Prompt.docx       # Original AI prompt
├── assets/
│   └── dashboard-preview.png   # Add a clear dashboard screenshot
└── demo/
    └── dashboard-recording.mp4 # Optional; consider Git LFS for large videos
Do not commit confidential customer-level data or files you do not have permission to publish. If the workbook is only a demonstration dataset, say so clearly.

🚀 How to explore or reproduce the project
1. Open the dashboard in a modern browser using the instructions supplied with its source code.
2. Start with the KPI cards to understand the currently selected data.
3. Apply one filter at a time—date, city, category, or sales representative—and observe how the charts and KPIs respond.
4. Compare monthly trends, category performance, city sales, and representative results.
5. Inspect discount and profitability charts as diagnostic views, not as standalone causal evidence.
6. Use product rankings to identify follow-up questions, then validate them against order-level details.
If the final dashboard reads the Excel file directly in the browser, follow the actual app's upload/load instructions; do not assume every browser will automatically load a local workbook.

🌟 What this project demonstrates
- Translating a business question into measurable KPIs.
- Validating and aggregating structured Excel data.
- Designing an executive-friendly analytics experience.
- Using AI as a development accelerator while retaining responsibility for data validation and interpretation.
- Communicating findings with both quantitative evidence and business context.
- Recognizing the difference between a visible pattern and a proven cause.
The takeaway: AI can accelerate dashboard creation. Analytical discipline is what turns the dashboard into a tool leaders can trust.
Project assets
- Dataset: Sales_Data_2025.xlsx
- Original dashboard prompt: Dahsboard Prompt.docx
- Demo recording: Recording 2026-10-19 124911.mp4
- 
Author
Kanika Jain
https://www.linkedin.com/in/kanika-jain-a46816228/?isSelfProfile=true
Data Analytics | Excel | Power BI | SQL | Business Intelligence

If you found this project useful, consider starring the repository or sharing feedback on which additional KPI or analysis would make it more decision-ready.
