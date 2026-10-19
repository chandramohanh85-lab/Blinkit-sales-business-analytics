# Blinkit Sales & Business Performance Analytics

I created this Power BI dashboard to get a better understanding of Blinkit's business performance. I wanted to bring sales, product performance, deliveries, customer feedback, marketing, and inventory data together in one place and see what useful insights I could find.

## About the Project

I worked with multiple datasets covering different parts of the business. I used the data to track important KPIs, explore sales trends, compare product performance, understand delivery delays, and analyse customer feedback and marketing campaigns.

While working on the project, I also came across some inconsistencies in the data. I looked into these issues and documented them so that the results could be understood in the right context.

## Tools I Used

- **Power BI Desktop:** To build the dashboard and create visualisations.
- **DAX:** To calculate KPIs and measure business performance.
- **Power Query:** To prepare and transform the data.
- **Python and pandas:** To support data analysis and check data quality.
- **CSV files:** Used as the source data for the project.

## Key Performance Indicators

I focused on six main KPIs to get an overview of business performance:

- Total Sales
- Total Orders
- Average Order Value
- On-Time Delivery Rate
- Average Customer Rating
- Marketing Return on Ad Spend (ROAS)

## What I Explored

- **Sales:** Looked at monthly sales trends, average order value, and payment methods.
- **Products:** Compared sales across categories and identified the top-performing products.
- **Deliveries:** Examined delivery statuses, delivery times, and how distance relates to delivery time.
- **Customer Feedback:** Explored ratings, feedback categories, and customer sentiment.
- **Marketing:** Compared campaign spending and revenue to understand campaign ROAS.
- **Inventory:** Reviewed stock activity and checked for inconsistencies in the inventory data.

## Some Interesting Findings

- **Delivery performance:** 69.40% of deliveries were completed on time, while 30.60% were recorded as not on time.
- **Product categories:** Dairy & Breakfast contributed approximately 12.86% of total item-level sales, making it the highest-selling category in the analysis.
- **Marketing campaigns:** Category Promotion had the lowest recalculated ROAS, at approximately 1.94×.

These findings gave me a clearer picture of the patterns in the data and highlighted areas worth investigating further.

## Data Quality and Limitations

One important part of this project was understanding that the data did not always tell a complete or consistent story.

- **Sales totals:** Order-level sales and item-level sales did not match. I kept them separate rather than treating them as the same measure.
- **Table relationships:** The orders dataset did not contain an `order_id` column, so I could not directly connect it to the items dataset using that field.
- **Inventory data:** Some records showed more damaged stock than stock received. Because of this, I did not treat the overall comparison as a confirmed damage rate.
- **Marketing ROAS:** I recalculated ROAS using total campaign revenue divided by total campaign spend instead of relying only on the existing ROAS column.

Documenting these issues helped me understand the importance of checking data quality before drawing conclusions from an analysis.

## Project Files

The repository includes:

- Power BI dashboard (`.pbix`)
- Dashboard screenshot (`.png`)
- Project report (`.pdf`)
- README documentation (`README.md`)

## What I Learned

This project gave me practical experience in building an interactive Power BI dashboard, writing DAX measures, preparing data with Power Query, and analysing business performance through KPIs and visualisations.

It also taught me that data analysis is not just about creating charts. Understanding the data, checking its quality, and explaining the findings clearly are just as important.
