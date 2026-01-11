# Data-Analysis-Interactive-Superstore-Tableau-Dashboard
**Project Description**
This project focuses on designing and developing an interactive Tableau dashboard using the Sample Superstore dataset to provide meaningful insights into business performance. The main purpose of the project is to convert raw sales and operational data into a visually engaging and easy-to-understand analytical solution that supports effective decision-making.
The dashboard is built with a two-plane layout, where the left panel contains the company logo, interactive controls, and filters, while the right panel presents multiple dynamic visualizations along with Key Performance Indicator (KPI) cards. These KPIs include Profit Margin, Return Rate, and Number of Orders, which together offer a comprehensive view of financial health, customer activity, and operational efficiency.
A key highlight of this project is the use of a dynamic Metric parameter, allowing users to switch between Sales, Profit, and Number of Orders. Based on the selected metric, all charts, titles, and tooltips update automatically, enabling flexible analysis without navigating between different dashboards. This feature enhances user experience and makes the dashboard more interactive and efficient.
To further improve usability, the dashboard includes filters for Year and Region, along with a show/hide toggle button that helps users control the display of filters and maximize viewing space. The project also ensures consistent insights by implementing a Top 5 Products view using FIXED level-of-detail expressions, so that top-performing products remain visible regardless of filter selections.
Advanced interactivity is achieved through filter actions, where selecting a category dynamically updates all other charts and KPI cards. The inclusion of trend lines and average reference lines helps highlight patterns and benchmarks, enabling users to better understand performance trends over time.
Additionally, the dashboard logo is configured as a clickable element that redirects users to the published version of the dashboard on Tableau Public, improving accessibility and navigation. Overall, this project demonstrates the effective use of data visualization best practices, interactive dashboard design, and analytical storytelling, making it a strong example of how Tableau can be used to deliver impactful business intelligence solutions.

## Dataset Used
-<a href="https://github.com/498M-Pranjal/Data-Analysis-Tableau-Dashboard/blob/main/Assignment%207.twbx">Dataset</a>

## Question (KPIs)

• Dashboard split into two planes (logo + filters on left, visuals + KPIs on right)
• Custom KPIs: Profit Margin, Return Rate, # Orders
• Dynamic Metric Parameter to switch between Sales, Profit & Orders
• Interactive filters for Year & Region with show/hide toggle button
• Top 5 Products display (always visible regardless of filters)
• Filter Actions on Category chart to control other visuals & KPIs
• Trend Lines & Average Lines where applicable
• Clickable Logo redirect to Tableau Public dashboard 

# Process
This project presents an interactive Tableau dashboard built using the Sample Superstore dataset.  
The dashboard is designed with a two-plane layout:
Left Panel: Company logo, interaction controls, and filters  
Right Panel: 6 dynamic visualizations and 3 KPI cards  

The dashboard enables users to analyze business performance dynamically through metric selection, filters, and interactive actions.
Dashboard Layout
Two-plane structure:
    Left: Logo, Metric selector, Year & Region filters  
    Right: Visualizations and KPI cards 
    
* Custom KPIs Formula with calculated feild:
Profit Margin = Total Profit / Total Sales  
Return Rate = Quantity Returned / Quantity Ordered  
Orders = Distinct count of Order ID  

Dynamic Metric Selection:
A parameter Metric allows switching between:
Sales  
Profit  
Orders  

All visualizations, titles, and tooltips update automatically based on the selected metric.

Interactive Filters:
Filters for Year and Region  
Show/Hide toggle button for filters to improve dashboard viewing experience.

Top 5 Products View:
The dashboard consistently displays the Top 5 Products based on the selected metric.
Implemented using FIXED LOD expressions to ensure results remain unchanged even when filters are applied.

Filter Actions:
Clicking on the Category chart dynamically filters all other visualizations and KPI cards.

Trend & Average Lines:
Trend lines and average reference lines are included where required to highlight performance patterns.

Clickable Logo:
Clicking on the dashboard logo redirects users to the published Tableau Public dashboard.

# Dashboard
<img width="1920" height="1080" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/5673f973-08ca-480c-af89-b87a78775a36" />

