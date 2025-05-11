# ANALYSIS OF GOOGLE PLAYSTORE DATA

## TABLE OF CONTENTS
- [Executive Summary](#executive-summary)
- [Tools](#tools)
- [Data cleaning process](#data-cleaning-process)
- [Key findings](key-findings)
- [Methodology](#methodology)
- [Results](results)
- [Observations and Limitations](#observations-and-limitations)
- [Conclusion](#conclusion)


## Executive Summary

This report presents a comprehensive analysis of mobile application trends on the Google Play Store, utilizing SQL queries to examine app distribution, user ratings, review sentiment, and engagement metrics. The dataset provided insights into distinct app categories, performance metrics, and user feedback, enabling a structured evaluation of market trends.

## Tools
- EXCEL
- MY SQL

##  Data cleaning process
- Handling Missing Values
- Removing Duplicates
- Formatting & Standardization
- Data Type Corrections
- Handling Outliers
- Integrating Multiple Tables

## Key findings include:
•	App Category Distribution: The dataset contains six unique app categories and 265 individual apps.
•	User Ratings: The Books & Reference category recorded the highest average rating (4.37), while Beauty and Auto & Vehicles demonstrated relatively lower rating trends.
•	Top-Rated Free Applications: Leading applications with a 4.9-star rating include Tickets SDA 2018, CDL Practice Test, and Uber Driver.
•	Sentiment Analysis: The Business category displayed the highest average sentiment polarity (0.2560), indicating predominantly positive user feedback.
•	Application Review Trends: Wattpad – Free Books received the highest number of reviews, surpassing 2.9 million, demonstrating extensive user engagement.
These findings provide valuable insights for app developers, product managers, and digital strategists seeking to understand user behaviour and optimize application offerings.



## Methodology
### Dataset Overview
The dataset utilized for this study consists of structured tables encompassing:
•	Application Table: Contains key attributes such as app name, category, rating, and number of user reviews.
•	Review Sentiment Table: Captures user-generated feedback with sentiment polarity scores.
SQL Query Techniques
To extract meaningful insights, a range of SQL functions were employed, including:
•	COUNT (DISTINCT ...) for determining unique app categories and application distribution.
•	AVG(RATING) to calculate the average ratings across different categories.
•	Filtering & Sorting using WHERE and ORDER BY clauses to identify the highest-rated free applications.
•	JOIN Operations for merging review sentiment data with category attributes, enhancing analytical precision.
•	COUNT(APP) to evaluate app distribution across the various categories.

## Results
1. App Category Distribution
A SQL query was executed to retrieve distinct app categories and total applications within each category:
•	Total Categories Identified: 6
•	Total Applications Present: 265
2. Average Ratings Across Categories
The average ratings for each category, derived from SQL computations, are as follows:
•	Books & Reference: 4.37 (highest-rated category)
•	Art & Design: 4.31
•	Auto & Vehicles: 4.29
•	Beauty: 4.33
•	Business: 4.24
•	Comics: 4.28
3. Top-Rated Free Applications
A filtered SQL query identified apps rated 4.9 stars that are classified as free:
1.	Tickets SDA 2018
2.	CDL Practice Test 2018
3.	DMV Permit Practice Test 2018
4.	Uber Driver
5.	ipsy: Makeup, Beauty, and Tips
6.	eBoox: Reader for fb2 epub books
4. Sentiment Analysis of App Reviews
Leveraging a SQL join operation, the sentiment polarity of user reviews across different categories was analyzed:
•	Business: 0.2560 (highest positive sentiment)
•	Books & Reference: 0.1521
•	Auto & Vehicles: 0.1359
•	Art & Design: 0.1701
•	Beauty: 0.0143
5. Application Review Trends
A SQL query identified the apps with the highest review count:
•	Wattpad – Free Books: 2,914,724 reviews (most reviewed app)
•	Google Play Books: 1,433,233 reviews
•	Facebook Pages Manager: 1,279,184 reviews
•	Uber Driver: 1,254,730 reviews
•	LINE WEBTOON - Free Comics: 1,013,635 reviews
•	Office Suite: Free Office + PDF Editor: 1,002,861 reviews

## Observations and Limitations

### Key Observations
•	The Books & Reference category recorded the highest average user rating, suggesting strong user satisfaction within educational and literary applications.
•	The Business category exhibited the most positive sentiment, indicating favorable user reception of productivity and enterprise apps.
•	High-rated free applications are predominantly educational and utility-based, implying strong demand for informative and service-oriented apps.
•	Wattpad and Google Play Books dominate review count statistics, highlighting the widespread adoption of mobile reading applications.

## Limitations
•	The dataset analyzed is synthetic and was generated for educational purposes rather than real-world application trends.
•	SQL queries used represent fundamental analytical techniques; further statistical model,xling could enhance predictive insights.

## Conclusion
This SQL-driven analysis presents a structured overview of mobile app trends, providing actionable insights for stakeholders in digital application development. Understanding user ratings, sentiment dynamics, and engagement metrics is critical for optimizing app performance and meeting consumer expectations.
This version ensures professionalism, clarity, and structured analysis while maintaining a formal tone. Let me know if you'd like any modifications or further refinements!

