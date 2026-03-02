# 🌍 Global Airbnb Performance Dashboard – Power BI

📌 Executive Summary

 This end-to-end Business Intelligence project analyzes over:

  250,000+ Airbnb listings
  1,000,000+ customer reviews

 The objective was to uncover revenue drivers, market concentration, pricing strategy gaps, customer behavior patterns, and trust indicators across major global    cities.

The result is a multi-page interactive Power BI dashboard designed to support strategic decisions for marketplace growth and pricing optimization.

🎯 Business Problem

 Airbnb operates in a highly competitive global hospitality market.
 Key strategic questions include:

  Which cities dominate supply and demand?
  What property types drive revenue?
  How concentrated is market share?
  How does seasonality impact engagement?
  Do pricing differences justify performance gaps?
  How important are trust and profile verification signals?

 This dashboard answers these questions using data modeling and advanced DAX measures.

📊 Dashboard Preview

 1️⃣ Global Growth & Supply Evolution

  Insight Focus:
   Peak listing growth occurred around 2015.
   Growth slowed due to regulatory constraints and market maturity.
   COVID-19 caused a sharp decline in new listings.
   
 2️⃣ Market Share & Pricing Strategy

  Key Findings:
   Paris, NYC, and Sydney account for nearly half of listings.
   Paris leads both listings and reviews.
   Hotel rooms are priced nearly 2x higher than Airbnb private rooms.
   Market concentration suggests strong urban dominance. 

 3️⃣ City Ratings & Competitive Positioning

  Key Findings:
   Mexico City and Rio show highest overall satisfaction.
   Hong Kong and Istanbul rank lower in value perception.
   Cleanliness and value-for-money are recurring weak points.

 4️⃣ Customer Behavior & Review Frequency

  Customer Behavior Insights:
   98.8% of customers leave 3 reviews or fewer.
   Majority of users review only once.
   Long-tail reviewers are rare outliers.

  Implication:
   Customer retention engagement is limited — review-based loyalty programs could be explored.

 5️⃣ Data Model Architecture

  Two large-scale datasets were modeled:
   Listings (250K+ rows)
   Reviews (1M+ rows)

  A one-to-many relationship was established:
   Listings.id → Reviews.listing_id

  This enabled accurate aggregation of:
   Revenue estimations
   Review frequency
   Seasonal patterns
   Host-level metrics

📈 Core KPIs Designed

 Total Listings
 Total Reviews
 Average Price by Property Type
 Estimated Revenue
 Market Share %
 Cumulative Growth %
 Review Frequency Distribution
 Host Trust Indicators
 Rating Breakdown by Dimension

🧠 Advanced Analytics & DAX

 Over 20+ DAX measures were developed, including:
 Time intelligence calculations
 Cumulative % distribution
 Market share measures
 Revenue estimations
 Segmented property performance
 Review frequency classification
 Verification impact metrics
 This project demonstrates practical BI modeling beyond basic visualization.

🔍 Strategic Business Insights
 1️⃣ Market Concentration Risk
  Urban markets dominate listings and engagement, exposing Airbnb to geographic dependency risk.

 2️⃣ Pricing Imbalance
  Hotel rooms command significantly higher pricing, yet Airbnb alternatives maintain strong review volume — indicating potential pricing optimization opportunity.

 3️⃣ Seasonal Dependency
  European cities dominate during summer months, confirming seasonal travel behavior.

 4️⃣ Trust as a Competitive Lever
  Over two-thirds of hosts are fully verified, reinforcing trust as a platform advantage.

 5️⃣ Customer Retention Opportunity
  Low repeat review behavior suggests opportunity for loyalty and engagement strategies.

 🛠 Tools & Technologies

 Power BI
 DAX (20+ measures)
 Data Modeling
 Relational Schema Design
 Business Intelligence Framework

📂 Dataset Information

 Listings dataset: 250,000+ rows
 Reviews dataset: 1,000,000+ rows
 Sample datasets are included in this repository due to GitHub file size limitations.
 
 Full datasets available via external link.
 https://mavenanalytics.io/data-playground/airbnb-listings-reviews

📥 Download Full Power BI File
  Due to GitHub’s 100MB limit, the .pbix file is hosted externally.
  https://drive.google.com/file/d/1-QGnabXItbXLqmeU4oXNTqj7EUBP8cvK/view?usp=sharing

💡 What This Project Demonstrates

 End-to-end BI project execution
 Handling million-row datasets
 Relational modeling
 Business-driven insight generation
 Executive storytelling through dashboards
 Real-world analytical thinking

   



