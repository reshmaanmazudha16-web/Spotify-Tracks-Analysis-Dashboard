## Objective

The main objective of this project is to:

* Analyze Netflix content trends over the years  
* Understand content distribution by type (Movies vs TV Shows)  
* Identify top contributing countries  
* Examine content classification by ratings  
* Provide an interactive dashboard for data-driven insights  

## Tools Used

* Microsoft Excel  
* Power Query (Data Cleaning & Transformation)  
* Pivot Tables  
* Pivot Charts  
* Slicers  
* Data Modeling  
* Conditional Formatting  
* Dashboard UI Design (Dark Theme)  

## Key Performance Indicators (KPIs)

The dashboard highlights the following key metrics:

* **Total Content:** 8,803 Titles  
* **Total Directors:** 4,526  
* **Total Genres:** 515  
* **Total Rating Categories:** 8,808  

These KPIs provide a quick summary of Netflix’s content library scale.

## Dashboard Features

### Content Released Per Year
* Displays yearly content growth  
* Shows increase/decrease trends  
* Identifies peak production years  

### Content Type Distribution
* Pie chart comparing:
  - Movies (≈69%)
  - TV Shows (≈31%)

### Content Distribution by Rating
* Bar chart showing ratings such as:
  - TV-MA  
  - TV-14  
  - TV-PG  
  - R  
  - PG-13  

Helps understand maturity-level classification trends.

### Content Released Over the Years (Movie vs TV Show)
* Trend comparison between Movies and TV Shows  
* Shows rapid growth post-2015  

### Content Distribution by Country
* Highlights top content-producing countries  
* United States leads production  
* Followed by India, United Kingdom, Japan, and others  

### Genre Distribution Filter
* Interactive slicer to filter by genre  
* Allows dynamic content exploration  

### Type of Content Filter
* Toggle between:
  - Movie  
  - TV Show  

## Configuration & Data Processing

### Data Cleaning (Power Query)

* Removed null values  
* Standardized country names  
* Split multiple genres into structured format  
* Converted release year into numeric format  
* Cleaned rating inconsistencies  

### Data Modeling

* Created relationships between:
  - Content Table  
  - Country  
  - Genre  
  - Ratings  
* Built Pivot Tables for aggregation  

### Dashboard Design

* Dark theme layout for professional appearance  
* Red highlight theme inspired by Netflix branding  
* KPI cards with bold numeric display  
* Interactive slicers connected to all visual elements  

## Dataset Information

The dataset includes:

* Title  
* Director  
* Country  
* Release Year  
* Rating  
* Genre  
* Type (Movie / TV Show)  
* Duration  

## Business Insights Derived

* Significant content growth observed after 2015  
* Movies dominate the platform compared to TV Shows  
* TV-MA and TV-14 are the most common ratings  
* United States contributes the highest number of titles  
* Global expansion visible through multi-country production  

## Conclusion

The Netflix Content Analysis Dashboard provides a clear and interactive view of Netflix’s content strategy and growth trends.

By leveraging Excel’s data modeling and visualization capabilities, this project demonstrates how raw data can be transformed into meaningful insights for strategic decision-making.
