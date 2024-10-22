# File Title: TITLE HERE
This is a project I worked on in the TripleTen Business Intelligence Analytics Programs. It was an independent project designed to showcase what I have learned about data visualization utilizing Tableau. This project is about analyzing the data from SuperStore to review it's operations and increase its profitablity to avoid bankruptcy. 

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Superstore Analysis](https://public.tableau.com/views/Sprint4Project_17247990150750/Sheet1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) | Link to the project in Tableau Public |
| 2 | [Superstore Raw Data](https://docs.google.com/spreadsheets/d/1t26BxZ9qWmXGEJjJPxfMR2AjE_xD-iGKRhE1dethLlQ/edit?usp=sharing) | Link to the raw data given by TripleTen |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [Requirements.txt](https://github.com/jethnacino/data_projects_TripleTen/blob/main/Superstore%20Analysis/Requirements.txt) | A simple .txt file with the provided project requirements as provided by TripleTen. |

### Table of Contents for README
| Section Title | Description |
| ----------- |----------- |
| Description | Describes the final product's purpose, software, format, and included visuals. |
| Process | Describes the process, including tools or tech used. |
| Data | Describes the data source, including files, tables, and fields. |
| Assumptions | Describes assumptions to include given by TripleTen and assumptions made based on the data and task. |
| Findings | Insights learned from the data analysis. |
| Recommendations | Recommended direction for the stakeholders based on final analysis. |

#### Description:
- Tableau Public, 7 sheets
- Includes several types of charts (bar, composite, map, histogram) with insights from them 

#### Process:
**Profit & Loss Analysis:** Identify which products and product subcategories are the greatest profit centers and loss makers using bar charts
**Advertising Analysis:** Identify the 3 best combinations of states and month of the year to advertise in using a map visualization and create an argument for how much SuperStore should be willing to pay for advertising for those states in those months
**Returned Items Analysis:** Make the Returned field into a calculated field where the null values are 0 and the Yes values are 1.
Use this new field to make a visualization for each of the following questions: 1. Which products have the highest return rate? 2. Which customers have the highest return rate?
In a separate sheet, make a visualization of the average profit against the average return rate on a dimension of your choice (state, shipping mode, product type, etc.). Present a visual argument why the superstore should do away with or keep doing business on the basis of this dimension.

#### Data
The data was provided by TripleTen on a Google spreadsheet file:
- `'Orders'`: Each row is a unique order that shows when, what, and where the order was placed
- `'People'`: Lists the manager for each region
- `'Returns'`: Each row is a unique order that was returned

#### Assumptions
For this project, we were told that we should be willing to spend 1/5 of profits on advertising via TripleTen.

#### Findings:
- SuperStore's profit centers were copiers and binders in the west region
- SuperStore's loss makers were binders in the central region and tables in the east region
- The best states to do advertising in were Washington in March, Indiana in October, and Vermont in November
- The products with the highest return rates were: Zebra GK420t, Okidata B401, Hewlett-Packard Deskjet, Cisco SPA 501G, Canon Color ImageCLASS, Bush Saratoga, and Avery 500
- The customers with the highest return rates were Roland Murray and Hilary Holden

#### Recommendations/Results:
- Stop Selling CBG DocuBind P400 Electric Binding System & Cubify CubeX 3D Printer Double Head Print
- Focus on pushing these sub-categories: Copiers, Phones, and Accessories
- Stop selling these sub-categories: Tables, Bookcases, and Supplies
- Do away with business in Oregon and Tennessee


