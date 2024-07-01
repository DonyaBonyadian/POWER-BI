# Power BI Project: Auto Insurance Analysis
## Project Description: Auto insurance provides financial protection to customers against physical damage, resulting from traffic collisions and theft of vehicles. In addition, it covers the cost associated with injuries, death, or property damage caused by the insured owner of the vehicle to another driver, vehicle, or property such as a fence, building, or utility pole. Although auto insurance requirements vary from state to state, bodily injury liability and property damage liability coverage has been mandated in many jurisdictions before using or keeping a vehicle on public roads. The auto insurance market exhibits high growth potential, as the number of road accidents is increasing in most countries across the globe.
The purpose of this project is to understand the main factors that drive customer tenure within the auto insurance industry for one or more years. The analysis is based on 12 months of United state Auto Insurance survey data. 
Dataset Information: United States Auto Insurance survey data is collected from kaggle.com.
https://www.kaggle.com/code/madhushreesannigrahi/jenks-natural-breaks-and-k-means-clustering/data 
The project involves creating a dashboard (report page) based on the supplied data set, the objective of the report is-
1. Loading the datasets in the Power BI desktop.
2.	Perform data cleaning and data transformation if required.
3.	Creating the required table Using Power BI DAX.
4.	Building the data model and creating the relationship based on the key attribute.
6.	Creating multiple report pages (Dashboard) based on the KPIs.
7.	Apply different types of formatting options if required.
8.	Publish the report into Power BI services.
9.	Configure for auto refresh.
10. Create a dashboard based on the published report in Power BI services.
## Data transformation and classification: Load the provided datasets into the Power BI desktop and perform the following activities-
1.	Make sure all the columns from the table have been imported into the Power BI Desktop.
2.	Perform data cleaning and transformation, and make sure the table contains valid data (remove the redundant data from the tables).
3.	Rename the table or columns, if required.
4.	Change the column data type, if required.
5.	Create a Date table with the following columns using the DAX formula-
-	Date (Date datatype, ex- 01-Jan-2020)
-	Month (String datatype, ex-Jan, Feb, Mar, etc.)
-	Year (Int datatype, ex- 2020)
-	Quarter (String datatype, ex- Q1, Q2, etc.)
6.	Day (Int datatype, ex- 1, 2, 3, etc.)
7.	Create the relationship based on the Key attributes-
-	Date (Date)  AutoInsurance (Effective To Date)
8.	Create a calculated field “Customer Gender” from Gender (if Gender=” M” then “Male” else “Female”).
## Report Page Information: Create multiple report page information based on the following requirements-
1.	Landing page: Create a landing page, when anyone browses this report landing page is the default page that will be displayed. The landing page consists of the following objects-
2.	Buttons contain a hyperlink to navigate to the different report pages.
3.	Background image which is related to Vehicle Insurance.
4.	Also, provide the project group name with individual information.
5.	Insurance by Coverage: Create a report page that contains the following information-
6.	Place the slicer for Date, Coverage Type, State, Policy Type, Vehicle Class, Sales Channel, Vehicle Size 
7.	Report Title (Insurance by Coverage)
8.	Button top navigate to the home page or Next page
9.	Card visual, which displays the total based on the KPIs
10.	The bar chart visually displays the data based on the KPIs
11.	Pie Chart visual based on the KPI’s
12.	Line chart visual which displays the trend based on the KPIs
13.	Insurance by Customer type: Create a report page that contains the following information-
14.	Place the slicer for Date, Coverage Type, State, Policy Type, Vehicle Class, Sales Channel, Vehicle Size 
15.	Report Title (Insurance by Coverage)
16.	Button top navigate to the Previous page or Next page
17.	Card visual, which displays the total based on the KPIs
18.	The bar chart visually displays the data based on the KPIs
19.	Pie Chart visual based on the KPI’s
20.	Line chart visual which displays the trend based on the KPIs
21.	Insurance by Policy type: Create a report page that contains the following information-
22.	Place the slicer for Date, Coverage Type, State, Policy Type, Vehicle Class, Sales Channel, Vehicle Size 
23.	Report Title (Insurance by Coverage)
24.	Button top navigate to the Previous page or Next page
25.	Card visual, which displays the total based on the KPIs
26.	The bar chart visually displays the data based on the KPIs
27.	Pie Chart visual based on the KPI’s
28.	Line chart visual which displays the trend based on the KPIs
29.	Insurance by Sales Channel: Create a report page that contains the following information-
30.	Place the slicer for Date, Coverage Type, State, Policy Type, Vehicle Class, Sales Channel, Vehicle Size 
31.	Report Title (Insurance by Coverage)
32.	Button top navigate to the Previous page or Next page
33.	Card visual, which displays the total based on the KPIs
34.	The bar chart visually displays the data based on the KPIs
35.	Pie Chart visual based on the KPI’s
36.	Line chart visual which displays the trend based on the KPIs
37	Insurance by Vehicle: Create a report page that contains the following information-
38	Place the slicer for Date, Coverage Type, State, Policy Type, Vehicle Class, Sales Channel, Vehicle Size 
39.	Report Title (Insurance by Coverage)
40.	Button top navigate to the Previous page or Next page
41.	Card visual, which displays the total based on the KPIs
42.	The bar chart visually displays the data based on the KPIs
43.	Pie Chart visual based on the KPI’s
44.	Line chart visual which displays the trend based on the KPIs
##KPI’s Information: Calculate the KPI’s value using the DAX formula based on the following information-
1.	Total Number of Customers: Count of Customers from AutoInsurance table.
2.	Total Number of Policy Sold: Sum of “Number of Policies” from AutoInsurance table.
3.	Total Amount Covered: Sum of “Customer Lifetime Value” from AutoInsurance table.
4.	Average Amount Covered: Average of “Customer Lifetime Value” from AutoInsurance table.
5.	Average Policy Sold: Average of “Number of Policies” from AutoInsurance table.
6.	Total Number of Open Complaints: Sum of “Number of Open Complaints” from AutoInsurance table.
7.	Total Claim Amounts: Sum of “Total Claim Amount” from AutoInsurance table.
8.	Average Claim Amount: Average “Total Claim Amount” from AutoInsurance table.
9.	Average Monthly Premium: Average “Monthly Premium Auto” from AutoInsurance table.
10.	Average Customer Income: Average of "Income" from AutoInsurance table.
11.	Total Basic Coverage: Count of Customers where Coverage = “Basic”.
12.	Total Extended Coverage: Count of Customer where Coverage = “Extended”.
13.	Total Premium Coverage: Count of Customers where Coverage = “Premium”.
14.	Total Suburban Customers: Count of Customers where Location Code= “Suburban”.
15.	Total Rural Customers: Count of Customers where Location Code= “Rural”.
16.	Total Urban Customers: Count of Customers where Location Code= “Urban”.
17.	Total Corporate Policy Sold: Count of Customer where Policy Type= “Personal Auto”.
18.	Total Personal Policy Sold: Count of Customer where Policy Type= “Personal Auto”.
19.	Total Special Policy Sold: Count of Customer where Policy Type= “Personal Auto”.
20.	Total Policy Sold by Agent: Count of Customer where Sales Channel= “Agent”.
21.	Total Policy Sold from Call Center: Count of Customer where Sales Channel= “Call Center”.
22.	Total Policy Sold from Web: Count of Customer where Sales Channel= “Web”.
23.	Total Policy Sold from Branch: Count of Customer where Sales Channel= “Branch”.
24.	Total Midsize Vehicle Insurance: Count of Customers where Vehicle Size= “Medsize”.
25.	Total Large Vehicle Insurance: Count of Customers where Vehicle Size= “Large”.
26.	Total Small Vehicle Insurance: Count of Customers where Vehicle Size= “Small”.
27.	Pie chart: Total Number of Customers by Coverage Type.
28.	Donut chart: Total Number of Customers by Customer Gender.
29.	Pie Chart: Total Number of Customers by Coverage Type.
30.	Donut Chart: Total Revenue Generated by Coverage Type.
31.	Line Chart: Total Policy Sold by Coverage Type across each Month.
32.	Area Chart: Average Claim Amount by Coverage Type across each Month-Year.
33.	Pie Chart: Total Number of Customers by Customer Type.
34.	Bar Chart: Total Revenue Generated by Customer Type.
35.	Tree Map: Average Policy Sold by Customer Type across each Month.
36.	Line Chart: Total Claim Amount by Customer Type across each Date (Year/Qtr/Month/Day).
37.	Pie Chart: Total Number of Customers by Policy Type.
38.	Donut Chart: Total Revenue Generated by Policy Type.
39.	Line Chart: Total Policy Sold by Policy Type across each Quarter.
40.	Area Chart: Average Claim Amount by Policy type across each Month-Year.
41.	Bar Chart: Total Number of Customers by Sales Channel.
42.	Pie Chart: Total Revenue Generated by Sales Channel.
43.	Area Chart: Total Policy Sold by Sales Channel across each Quarter.
44.	Line Chart: Average Claim Amount by Sales Channel across each Month-Year.
45.	Bar Chart: Total Policy Sold by Vehicle Type.
46.	Line Chart: Total Revenue Generated by Vehicle Type across each Date.
47.	Map Visual: Display State-wise the Total Number of Customers, Total Revenue generated, Total Number of policies sold, and Total Amount Covered.
48.	Table Visual: Display the granular level information.
49.	Also, you can add some more KPIs based on your analysis.

##Report formatting: Format the individual reports based on the following information-
1.	All the slicers must be multi-select options except the Date slicer, The Date slicer must be a slider.
2.	The page background must be in black color for the individual report pages.
3.	Use the following color combination to format the report pages-
-	#0090D4
-	#95C11F
-	#F39200
-	#93AEB9
-	#8B9C22
-	#DA5914
-	#957E5D
-	#C6C6C6
-	#1E4451
-	#286D29
-	#974008
-	#5C4530
-	#878787
-	#E3E3E3
-	#DFD5B4
-	#00abe4
-	#c8d400
4.	Use Different colors on the button action.
5.	Use standard font and colors for the card, slicer, and title visuals.



Deployment and Scheduling: Once this report is created, deploy this into the Power BI Services and perform the following activities-
1.	Deploy the report into the Power BI services.
2.	Configure the Refresh schedule.
3.	Create a Dashboard in the Power BI Services based on the following KPIs
-	Total Number of Customers
-	Total Number of Policy Sold
-	Total Amount Covered
-	Average Amount Covered
-	Average Policy Sold
-	Total Number of Open Complaints
-	Total Claim Amounts
-	Average Claim Amount
-	Average Monthly Premium
-	Average Customer Income
-	Total Basic Coverage
-	Total Extended Coverage
-	Total Premium Coverage
-	Total Suburban Customer's
-	Total Rural Customer's
-	Total Urban Customer's
-	Total Corporate Policy Sold
-	Total Personal Policy Sold
-	Total Special Policy Sold
-	Total Policy Sold by Agent
-	Total Policy Sold from Call Center
-	Total Policy Sold from Web
-	Total Policy Sold from Branch
-	Pie chart
-	Line Chart
-	Bar Chart
-	Table Chart
-	Line Chart
-	Map Visual
-	Table Visual
-	Pie Chart
## Generate the Public Links: Once the report is available in the Power BI services, generate the public link of the report, and shared accordingly.

## References:
-	https://beinsure.com/wp-content/uploads/2022/07/%D0%B8%D0%B7%D0%BE%D0%B1%D1%80%D0%B0%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5-259.png 
-	https://www.kaggle.com/code/madhushreesannigrahi/jenks-natural-breaks-and-k-means-clustering/data 


![image](https://github.com/DonyaBonyadian/POWER-BI/assets/145790346/26ac5a52-195f-4a07-8623-90270d210754)
