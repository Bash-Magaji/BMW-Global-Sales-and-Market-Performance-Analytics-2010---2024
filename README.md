**1.0 Introduction**

The automotive industry generates large volumes of sales data that can provide valuable insights into customer preferences, product performance, market demand, and revenue generation. This technical report presents an analysis of BMW sales data covering the period from 2010 to 2024, with a focus on understanding sales performance across different vehicle models, regions, colours, fuel types, transmission types, and sales classifications.
The analysis examines a total sales volume of 253.4 million vehicles, generating approximately $19.01 trillion in revenue across six regions. By analyzing both revenue and sales volume, the study seeks to identify the major contributors to BMW's sales performance, assess variations across markets and product categories, and highlight patterns that can support informed business decision-making.

 <img width="1013" height="433" alt="image" src="https://github.com/user-attachments/assets/6563b9f0-1fde-4ef6-89b7-6ccdc87edaff" />

**Aim of the Analysis**

The primary aim of this analysis is to evaluate BMW's sales and revenue performance from 2010 to 2024 and identify key trends, customer preferences, high-performing products, and market opportunities that can support data-driven business decisions.
Objectives of the Analysis

The specific objectives are to:

1.	Analyse sales and revenue trends over the period to identify growth, decline, and significant fluctuations. 

2.	Evaluate model performance based on revenue generated and sales volume to identify leading and underperforming models. 

3.	Assess regional performance and determine the markets contributing most significantly to BMW's revenue and sales volume. 

4.	Examine customer preferences based on vehicle colour and transmission type. 

5.	Analyse fuel-type performance to understand the contribution of petrol, diesel, hybrid, and electric vehicles. 

6.	Compare sales classifications to understand the distribution of high- and low-volume sales. 

7.	Identify relationships between sales volume and revenue to distinguish volume-driven performance from higher-value sales. 

8.	Generate actionable business recommendations that can support product planning, inventory management, marketing, market expansion, and future sales strategies. 

**Analytical Tool Used**

The analysis was conducted using Microsoft Excel, which was used for data preparation, validation, analysis, calculations, and visualization. Excel's functions, PivotTables, charts, and dashboard capabilities were utilized to summarize large volumes of sales data and present the findings in an accessible format. The use of Excel enabled the analysis to move from raw sales records to meaningful business insights, allowing key performance indicators and patterns to be examined across multiple dimensions, including time, model, region, fuel type, colour, transmission, revenue, and sales volume.

**2.0 Story of Data**

**Data Source:** The dataset used for this analysis was obtained from Kaggle, a widely used platform for data science and analytics datasets. 

**Data Structure:** The dataset contains 50,000 vehicle records covering 11 BMW models: 7 Series, i8, X1, 3 Series, i3, 5 Series, M5, X3, X5, X6, and M3. The data is presented in a structured tabular format, with each row representing an individual vehicle sales record and each column capturing a specific sales or vehicle attribute. Key variables include Model, Year, Region, Color, Fuel Type, Transmission, Engine Size, Mileage, Price, Sales Volume, Total Sales Revenue, and Sales Classification. Collectively, these variables provide a comprehensive basis for analyzing BMW's sales performance, revenue generation, customer preferences, regional market distribution, vehicle characteristics, and overall sales trends.

**Story Data is Telling:** BMW Sales Analytics presents a picture of a globally diversified automotive business, with strong performance across key models and regions, relatively balanced customer preferences, and significant contributions from alternative powertrains, particularly hybrid and electric vehicles. The analysis identifies opportunities to improve product mix, regional inventory planning, pricing strategies, and future investment decisions by aligning business strategies with observed sales and demand patterns.

**3.0 Data Splitting and Preprocessing**

**Data Cleaning:** To ensure data quality and establish a reliable foundation for analysis, the dataset was first validated for empty rows, missing values, and duplicate records. The validation confirmed that the dataset contained no empty rows or duplicate records. To improve readability and ease of navigation, the visibility and formatting of the column headers and cell contents were enhanced. The top row was frozen to keep the column headers visible while scrolling through the dataset. Finally, the dataset was converted into a standard Excel Table, improving its structure, accessibility, and usability for subsequent analysis.

**Data Transformation:** During the data transformation phase, an additional Total Sales Revenue column was appended to the dataset to provide a clear measure of the total revenue generated within the period covered by the analysis. The new column was calculated by multiplying the Price by the corresponding Sales Volume for each record, using the formula:
=Price * Sales Volume
This transformation enabled revenue to be analyzed across key dimensions, including model, year, region, colour, fuel type, transmission, and sales classification, thereby supporting a more comprehensive assessment of BMW's sales and financial performance.

**Data Splitting:** The dataset was divided into two main analytical categories to facilitate a more focused assessment and provide clearer insights into distinct aspects of BMW's sales performance.

**A. Category One** — Independent value

Model

Region

Color

Fuel Type

Transmission

Sales Classification

**B. Category Two** — Dependent value

Year

Engine Size

Mileage

Price

Total Sales Revenue 

Sales Volume

**Industry Context:** The dataset relates to the Automotive Industry, with specific relevance to vehicle manufacturing and sales, automobile retail, and vehicle distribution. It provides insights into sales performance, revenue generation, customer preferences, and market distribution within the automotive sector.

**Stakeholders:** The stakeholders of this project include the Sales Managers, Regional/Market Managers, Marketing Managers, Product Managers, Automotive Dealers, Business Development Managers, Supply Chain & Inventory Managers, Finance Managers, Senior Management/Executives, Data Analysts & Business Intelligence Teams

**Success to the Industry:** Success in the automotive industry means achieving sustainable sales and revenue growth while meeting customer demand, maintaining profitability, and adapting to changing automotive technologies and market preferences.

**4.0 Potential-Analysis**

Areas identified for potential analysis during the pre-analysis phase are outlined below.

•	Sales trend report 

•	Model by Revenue Generated

•	Regional sales by Revenue

•	Preferred Color by Revenue

•	Fuel Type by Revenue

•	Sales Classification by Revenue

•	Transmission by Revenue

•	Sales trend report by Volume 

•	Model by Volume Sold

•	Regional sales by Volume Sold

•	Preferred Color by Volume Sold

•	Fuel Type by Volume Sold

•	Sales Classification by Volume Sold

•	Transmission by Volume Sold

**Initial Insights**

•	Identify how BMW revenue changes over time, highlighting periods of revenue growth, decline, peaks, and possible seasonal patterns.

•	Determine which BMW models generate the highest and lowest revenue and assess whether premium models contribute disproportionately to total revenue.

•	Compare revenue contribution across regions to identify the strongest and weakest markets and potential regional revenue concentration.

•	Determine which vehicle colors generate the most revenue and whether customer color preferences are associated with higher-value vehicle purchases.

•	Compare revenue generated by petrol, diesel, hybrid, and electric vehicles to identify the most financially significant powertrain category.

•	Examine revenue across sales classifications/categories to identify which category contributes most to overall revenue and which requires improvement.

•	Compare automatic, manual, and other transmission types by revenue to determine customer preference and the financial impact of each category.

•	8.Analyze the number of BMW vehicles sold over time to identify sales growth, declining periods, demand fluctuations, and seasonal trends.

•	Identify the most and least popular BMW models based on units sold, revealing models driving market demand.

•	Determine which regions purchase the most BMW vehicles and compare sales volumes to identify high- and low-demand markets.

•	Identify the most popular vehicle colors based on units sold and assess customer preferences across the BMW portfolio.

•	Determine which fuel types account for the highest sales volume and assess consumer adoption of alternative powertrains.

•	Compare sales volume across classifications to determine which categories dominate unit sales and which have weaker demand.

•	Identify the most popular transmission type based on units sold and determine whether customer demand is concentrated around automatic or manual vehicles.

**5.0 In-Analysis**

**•	Analysis** - Sales Trend Report 

**Observation**

BMW revenue remained relatively stable between 2010 and 2024, fluctuating around the $1.2T–$1.3T range. Revenue declined gradually from $1.2616T in 2010 to $1.2551T in 2015, before reaching $1.2846T in 2016. After another decline through 2018, revenue peaked at $1.2893T in 2019. Revenue fell to its lowest level of $1.2243T in 2023, following a strong peak of $1.3444T in 2022, the highest revenue recorded during the period. However, revenue recovered significantly in 2024 to $1.3128T

**Insights**

•	investigate why 2022 recorded the highest revenue at $1.3444T, representing the strongest year in the period. 

•	Probe what caused the sharp decline in 2023 with revenue falling to $1.2243T, the lowest point in the 15-year period.

•	Explore why 2024 showed a strong recovery, reaching $1.3128T, an increase of approximately 7.2% from 2023. 

•	Revenue also showed notable peaks in 2019 ($1.2893T) and 2016 ($1.2846T), indicating periods of stronger sales performance. 

•	Scrutinize the period between 2010 and 2015 which showed a relatively gradual decline, before revenue began fluctuating more significantly from 2016 onward.

**•	Analysis** - Model by Revenue Generated

**Observation**

The 7 Series generated the highest revenue at $1.7901T, followed by the 3 Series ($1.7685T) and i8 ($1.7647T). The X1 ($1.7530T) and 5 Series ($1.7357T) also recorded strong revenue contributions. Among the remaining models, the i3 generated $1.7242T, while the X5 and X3 generated $1.7087T and $1.7080T, respectively. The M5, X6, and M3 recorded comparatively lower revenues of $1.6985T, $1.6934T, and $1.6675T.

**Insights**

•	7 Series generated the highest revenue at $1.7901T, making it the leading revenue contributor among the models analyzed. 

•	3 Series ($1.7685T) and i8 ($1.7647T) followed closely, indicating strong revenue contributions from both luxury and performance-oriented models. 

•	X1 ($1.7530T) and 5 Series ($1.7357T) also performed strongly, showing that both SUV and executive sedan segments contribute significantly to revenue. 

•	The i3 generated $1.7242T, suggesting a strong revenue contribution from BMW's electric vehicle segment. 

•	X5 ($1.7087T) and X3 ($1.7080T) recorded almost identical revenue, indicating comparable financial contributions from these SUV models. 

•	M3 recorded the lowest revenue at $1.6675T, although the difference from the top-performing 7 Series is relatively small

**•	Analysis** - Regional sales by Revenue

**Observation**

Asia generated the highest revenue at $3.2506T, followed by Europe ($3.1881T) and North America ($3.1829T). The Middle East contributed $3.1678T, while South America ($3.1138T) and Africa ($3.1090T) recorded the lowest revenues among the regions analyzed.

**Insights**

•	Asia is the highest revenue-generating region, contributing $3.2506T, indicating strong BMW revenue performance in the Asian market. 

•	Europe ($3.1881T) and North America ($3.1829T) are the next strongest markets, with very similar revenue contributions. 

•	Middle East generated $3.1678T, placing it fourth among the six regions. 

•	South America ($3.1138T) and Africa ($3.1090T) recorded the lowest revenues.

•	Is Asia the strongest BMW market because of higher sales volume, higher-value vehicles, or a combination of both?

**•	Analysis** - Fuel Type by Revenue

**Observations**

Hybrid vehicles sold the highest of 64.5321M units, followed by Petrol 63.3242M units and Electric sold 63.1577M units. Diesel vehicles recorded the lowest sales volume at 62.3618M units.

**Insights**

•	Hybrid vehicles leading the sales volume, suggest that hybrid models may be achieving a strong balance between performance, efficiency, and customer demand. 

•	Petrol engine remains highly competitive despite the growing presence of alternative powertrains. 

•	3.Electric vehicles sold 63.1577M units, indicates that EVs are already contributing almost the same level of volume as conventional petrol vehicles in the market. 

•	Diesel engine recorded the lowest unit sold may indicate relatively weaker demand or a smaller contribution from diesel models.

•	6. Does Hybrid and Electric vehicles also generate? 

**•	Analysis** - Preferred Color by Revenue

**Observations**

Gold recorded the highest sales volume, with 42,750,183 units, making it the most preferred color in the dataset. Silver ranked second with 42,674,022 units followed by White with 42,272,954 units. Grey 41,995,141 and Blue 41,972,741 recorded very similar sales volumes, suggesting comparable levels of customer demand. Black recorded the lowest sales volume at 41,710,693 units

**Insights**

•	investigate why Gold sold higher units than the rest-colored type and if it also leads in revenue generated. 

•	Investigate if Black recorded the lowest sales volume in all region and implement strategies to increase the sales volume. 

**•	Analysis** - Sales Classification by Revenue

**Observations**

69.51% is the total sales is classified as Low while only 30.49% is classified High 

**Insights**

• This indicates that Low sales classification is the dominant revenue category, contributing more than twice the revenue generated by High-classified sales. 

• However, 39.02 percentage-point gap suggests a substantial imbalance in the revenue contribution between the two classifications and warrants further investigation. 

**•	Analysis** - Transmission by Sales Volume

**Observations**

Manual transmission accounts for 50.27% of sales volume while Automatic accounts for 49.73% 

**Insights**

Manual transmission sold slightly more units does not necessarily mean more revenue generated. The difference could be influenced by the average selling price of vehicles within each transmission category.


**6.0 Post-Analysis and Insights**

Between 2010 and 2024, BMW generated a total revenue of $19.0122T from 253,375,734 vehicles sold across six regions, with an average selling price of $75,034.60 per vehicle. The vehicles recorded an average mileage of 100,307.20 km and an average engine size of 3.2L.

**Model Performance**

The 7 Series recorded the highest sales volume, with 23,786,466 units sold, followed by the i8 (23,423,891), X1 (23,406,060), and 3 Series (23,281,303). The M3 recorded the lowest sales volume at 22,349,694 units among the models analyzed.
In terms of revenue, the 7 Series was the leading revenue-generating model at $1.7901T, followed by the 3 Series ($1.7685T) and i8 ($1.7647T). The X1 generated $1.7530T, while the 5 Series contributed $1.7357T. The i3 generated $1.7242T, while the X5 and X3 generated $1.7087T and $1.7080T, respectively. The M5, X6, and M3 recorded comparatively lower revenues of $1.6985T, $1.6934T, and $1.6675T.
The strong performance of the 7 Series across both sales volume and revenue identifies it as an important commercial driver in the dataset.

**Regional Performance**

Asia generated the highest regional revenue at $3.2506T, followed by Europe ($3.1881T) and North America ($3.1829T). The Middle East contributed $3.1678T, while South America and Africa recorded $3.1138T and $3.1090T, respectively.
Although Asia leads, the relatively narrow difference between the highest- and lowest-performing regions indicates that BMW revenue is well distributed geographically, rather than being heavily dependent on one market.


**Color Performance**

Gold recorded the highest sales volume at 42.7502M units, followed by Silver at 42.6740M and White at 42.2730M. Grey and Blue recorded 41.9951M and 41.9727M units, respectively, while Black recorded the lowest volume at 41.7107M units.
Gold also generated the highest revenue at $3.2052T, while Black generated the lowest at $3.1202T. This consistency between volume and revenue suggests that Gold's leading revenue position is largely associated with its higher sales volume.
However, the relatively small difference between the colors indicates that customer demand is broadly distributed across the color options, with no single color overwhelmingly dominating the market.

**Fuel-Type Performance**

Hybrid vehicles recorded the highest sales volume at 64.5321M units, generating $4.8207T in revenue. Petrol followed with 63.3242M units and $4.7561T, while Electric vehicles recorded 63.1577M units and $4.7507T.
Diesel recorded the lowest performance, with 62.3618M units sold and $4.6847T in revenue.
The strong performance of Hybrid and Electric vehicles is notable because their combined sales volume and revenue slightly exceed the corresponding contribution from conventional petrol and diesel vehicles. This suggests that alternative powertrains represent an important component of the BMW sales portfolio.

**Transmission Performance**

Manual transmission accounted for 50.27% of total unit sales, while Automatic transmission accounted for 49.73%.
The extremely narrow 0.54 percentage-point difference indicates that sales volume is almost evenly split between the two transmission types. Therefore, neither transmission category demonstrates a clear volume advantage in the dataset.
Overall, the findings indicate a relatively diversified BMW sales portfolio, with performance distributed across multiple models, regions, colors, fuel types, and transmission categories.

**7. Charts and Visualizations**

<img width="644" height="336" alt="Screenshot 2026-08-11 155124" src="https://github.com/user-attachments/assets/9bec4dce-9531-4b59-9cb3-87b41c454017" />

This line chart shows the sales trend and revenue generated for each year 2010 – 2024. 

 <img width="401" height="341" alt="Screenshot 2026-08-11 155146" src="https://github.com/user-attachments/assets/9fb75210-eac1-47dc-b8e0-f2d3cd8d1de1" />

This bar-chart the revenue generated by each region within the period reviewed. It indicates that Asia generated the highest revenue at $3.2506T and Africa $3.1090T recorded the lowest revenues among the regions analyzed.
 
 <img width="335" height="341" alt="Screenshot 2026-08-11 155203" src="https://github.com/user-attachments/assets/6b33d415-4de9-464b-903e-f269e7e5007c" />

The doughnut chart shows that Manual transmission accounts for 50.27% of sales volume while Automatic accounts for 49.73% 

<img width="417" height="334" alt="Screenshot 2026-08-11 155225" src="https://github.com/user-attachments/assets/df43a694-705f-4a72-86d1-824679ffa2eb" />

The bar chart shows the volume of sales by each colour type indicating that Gold recorded the highest sales volume, with 42,750,183 units, making it the most preferred color while Black recorded the lowest sales volume at 41,710,693 units

 <img width="481" height="295" alt="Screenshot 2026-08-11 155241" src="https://github.com/user-attachments/assets/4cc897be-5cf7-4760-9d33-da0f2994f4b4" />

This column chart shows different fuel types and the volume sold. It indicates that Hybrid vehicles sold the highest of 64.5321M units whiles Diesel vehicles recorded the lowest sales volume at 62.3618M units.

**8. Post Analysis Recommendations**

**•	Prioritize high-performing models**

BMW should continue to prioritize models such as the 7 Series, i8, X1, and 3 Series, which demonstrate strong sales volume and/or revenue generation.
However, the lower-performing models should not automatically be discontinued. Their performance should be assessed against profit margin, production cost, customer segment, and strategic importance before making portfolio decisions.

**•	 Develop a stronger Asia-focused strategy**

Since Asia is the highest revenue-generating region, BMW should investigate the specific markets, models, and customer segments driving this performance.
The company could consider:
Increasing inventory of high-demand models. 
Strengthening dealer networks. 
Targeted digital marketing. 
Regional product customization. 
Expanding EV and hybrid offerings where demand supports it. 
At the same time, BMW should maintain its presence in Europe and North America because their revenue contributions remain strong, while putting strategies in place on how to improve sales in Africa.

**•	 Accelerate Hybrid and Electric vehicle strategy**

The strong performance of Hybrid and Electric vehicles deserves strategic attention.
BMW should:
Expand high-performing hybrid and EV models. 
Identify regions with the strongest EV demand. 
Improve EV charging partnerships and infrastructure. 
Use customer data to understand barriers to EV adoption. 
Evaluate whether EVs generate higher margins or customer lifetime value. 
The dataset suggests that alternative powertrains are already commercially significant rather than being a niche segment.

**•	 Optimize inventory using sales volume**

Inventory planning should be based on actual demand patterns. High-volume combinations such as: Model, Region, Fuel Type, Color, should receive greater inventory priority to reduce stockouts and improve vehicle availability. Conversely, slow-moving combinations should be carefully managed to reduce inventory holding costs.

**•	 Do not over-invest based solely on color preference**

Although Gold leads sales volume and revenue, the difference between colors is relatively small.  Therefore, BMW should maintain a balanced color portfolio rather than significantly increasing production of one color based solely on these results.
Color preferences should instead be analyzed by model and region before making production decisions.

**•	 Investigate the manual vs. automatic balance**

The almost equal split between manual and automatic sales presents an interesting opportunity.
BMW should investigate: Transmission, Model, Region, Fuel Type to determine whether certain markets or models have stronger transmission preferences.
This can support better production allocation and regional inventory planning.

**•	 Investigate the revenue fluctuations over time**

The earlier trend analysis showed significant revenue fluctuations, particularly the 2022 peak, 2023 decline, and 2024 recovery.
Management should investigate what changed during these periods in terms of:
Model mix → Region → Fuel type → Sales volume → Average selling price.
This can help determine whether the fluctuations were caused by changes in demand, pricing, product mix, or regional performance. 

**9.   Conclusion**

This BMW Sales Analytics provides a data-driven view of the company’s sales performance, customer preferences, and market distribution between 2010 and 2024. The analysis shows a diversified sales portfolio, with 253.4 million vehicles generating approximately $19.01T in revenue across six regions. The 7 Series emerged as the leading model by both sales volume and revenue, while Asia recorded the highest regional revenue. Hybrid vehicles also demonstrated strong commercial performance, leading both sales volume and revenue among the fuel types analyzed. Meanwhile, colour and transmission preferences were relatively balanced, indicating that these factors have less influence on overall performance than product, market, and powertrain characteristics.
From a business perspective, the findings highlight opportunities to strengthen high-performing models and markets, optimize inventory based on demand, and increase strategic investment in hybrid and electric vehicles. Management should also examine the relationship between sales volume, pricing, and revenue to identify the most profitable product-market combinations. Overall, the analysis demonstrates that sustainable growth in the automotive industry depends on using sales data to align product strategy, pricing, inventory, regional expansion, and emerging powertrain technologies with customer demand. The findings provide a strong foundation for more advanced forecasting and predictive analytics to support future sales planning and strategic decision-making.

**10. 	References**

Kaggle.com

flaticon.com

https://tristen.ca/hcl-picker/#/hlc/6/1/15534C/E2E062
