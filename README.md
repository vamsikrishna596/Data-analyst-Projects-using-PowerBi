# VAMSI_PORTFOLIO
🧠 Power BI Dashboarding Assignment
✨ Project Title: "Dubai Real Estate Intelligence Dashboard"
________________________________________
🎯 Objective:
Design a professional, interactive Power BI dashboard using Dubai housing data to provide actionable insights for investors, agents, and policymakers.
________________________________________
📁 Dataset Summary:
Dataset fields (as previewed):
●	location
●	price
●	bedrooms
●	bathrooms
●	size (sqft)
●	property_type
●	developer
●	year_built (if available)
●	furnishing_status (if available)
________________________________________
🛠️ Task Instructions:
🧼 Part 1: Data Preparation (Using Power Query)
1.	Clean missing or incorrect values.
2.	Remove duplicates.
3.	Convert data types (e.g., numeric for price/size, categorical for type/location).
4.	Create the following calculated columns:
○	price_per_sqft = price / size
○	property_age = 2025 - year_built (if applicable)
○	listing_category = High-End / Mid-Range / Budget (based on price quantiles)
________________________________________
📊 Part 2: Dashboard Requirements
Create at least 1 page of interactive dashboard visuals with the following sections:
________________________________________
📌 Section 1: Key Metrics (KPI Cards)
●	Total Listings
●	Average Price
●	Average Size (sqft)
●	Highest Priced Property
●	Avg. Price per Sqft
________________________________________
📌 Section 2: Visual Analytics
Visual	Description
Map	Show average price per location. Bubble or Filled Map.
Bar Chart	Price by property type
Stacked Column Chart	Count of listings by bedrooms, colored by property_type
Line Chart	Price trend over time (if time data is present or can be simulated)
Tree Map	Listings by developer and property_type
Filter Slicers	Furnishing status, property type, number of bedrooms, price range
________________________________________
🧩 Part 3: Interactivity & Storytelling
●	Add slicers for dynamic filtering (e.g., bedrooms, locations, developers).
●	Use tooltips to enrich visuals (e.g., show price per sqft).
●	Implement drill-through or bookmark for detail views (optional).
●	Include insight cards or callout textboxes (e.g., “Downtown Dubai has highest avg. price”).
________________________________________
📝 Deliverables:
1.	.pbix Power BI file with completed dashboard.
2.	A 1-slide summary (can be in PowerPoint or inside Power BI) explaining:
○	Business questions answered.
○	Key takeaways from the data.
○	Suggested actions for a real estate investor or agent.
________________________________________
✅ Evaluation Criteria:
Criteria	Weight
Data Cleaning & Modeling	20%
Visual Design & Layout	20%
Insightfulness of Visuals	25%
Interactivity (filters, drill-through, bookmarks)	20%
Presentation/Storytelling	15%


SAMPLE

✅ Dataset Summary
Column	Description
SquareFeet	Size of the property (in sqft)
Bedrooms	Number of bedrooms
Bathrooms	Number of bathrooms
Neighborhood	Area type (Rural, Suburb, Urban)
YearBuilt	Year the property was built
Price	Selling price of the property
________________________________________
🧠 Calculated Fields to Add
We'll enrich the dataset with:
1.	Price per Sqft = Price / SquareFeet
2.	Property Age = 2025 - YearBuilt
3.	Listing Category = based on price quantiles (Budget, Mid-Range, High-End)
Let me generate that enriched dataset now. 
Enriched Dubai Housing Data
SquareFeet	Bedrooms	Bathrooms	Neighborhood
2126	4	1	Rural
2459	3	2	Rural
1860	2	1	Suburb
2294	2	1	Urban
2130	5	2	Suburb
2095	2	3	Suburb
The dataset has been successfully enriched with the following new columns:
●	PricePerSqft: Price per square foot
●	PropertyAge: Age of the property as of 2025
●	ListingCategory: Categorized as Budget, Mid-Range, or High-End based on price
________________________________________
🚀 Next Steps for Power BI Dashboard:
You can now import this enriched CSV into Power BI and build the following visuals:
________________________________________
🧩 Recommended Dashboard Layout:
1. KPI Cards
●	Total Listings
●	Average Price
●	Avg. Price per Sqft
●	Oldest Property
●	Most Expensive Property
2. Charts
●	Bar Chart: Count of listings by Neighborhood and ListingCategory
●	Pie Chart: Distribution of ListingCategory
●	Box Plot: Price distribution by Neighborhood
●	Map (optional): Plot if lat/lon is available
●	Histogram: Property Age
●	Scatter Plot: SquareFeet vs Price colored by ListingCategory
3. Slicers for Interactivity
●	Bedrooms
●	Bathrooms
●	Neighborhood
●	ListingCategory
●	Price Range
Here’s a cleaned summary of your dataset (House.xlsx) 👇
📊 Dataset Overview
•	Rows: 50,000
•	Columns: SquareFeet, Bedrooms, Bathrooms, Neighborhood, YearBuilt, Price
•	Missing Values: None ✅
•	Year Range: 1950 – 2021
•	Price Range: -36,588 → 492,195 (⚠️ negative prices may need cleaning)
•	Neighborhoods: Rural, Suburb, Urban
•	Bedrooms Range: 2 – 5
•	Bathrooms Range: 1 – 3
•	Square Feet Range: 1,000 – 2,999
________________________________________
🔑 Insights for Storytelling
You can now build a narrative around:
1.	Market Growth by YearBuilt → How property prices evolved over decades.
2.	Neighborhood Comparison → Rural vs Suburb vs Urban pricing.
3.	Property Size & Bedrooms → Impact of size/bedrooms on pricing.
4.	Top/Bottom Pricing → Spot anomalies (negative or very high prices).
5.	Forecasting Future Prices → Using Power BI what-if scenarios.
s


