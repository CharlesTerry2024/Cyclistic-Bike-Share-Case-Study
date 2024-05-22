# Cyclistic Bike-Share Analysis Case Study

## Overview
This case study analyzes how casual riders and annual members use Cyclistic bikes differently. The goal is to derive insights that inform marketing strategies to convert casual riders into annual members, thereby maximizing profitability and future growth.

## Business Task
Understand the usage patterns of casual riders and annual members, and design targeted marketing strategies to convert casual riders into annual members.

## Data Sources
- **Historical Trip Data**: The previous 12 months of Cyclistic trip data.
  - Datasets: Divvy2019Q1 and Divvy2020Q1 provided by Motivate International Inc.
  - Data Privacy: No personally identifiable information (PII) included.

## Data Cleaning and Preparation
1. **Data Loading**: Downloaded and unzipped the data files.
2. **Organization**: Structured the data in folders, with subfolders for CSV and processed files.
3. **Transformation**:
   - Created columns for `ride_length` (difference between `ended_at` and `started_at`) and `day_of_week` (using the WEEKDAY function).
4. **Cleaning**:
   - Removed duplicates and ensured no missing values in critical columns.
   - Standardized date and time formats.

## Data Analysis
1. **Ride Duration**:
   - Casual riders: ~30 minutes average ride length.
   - Annual members: ~15 minutes average ride length.
2. **Day of the Week Usage**:
   - Casual riders: Higher usage on weekends, peaking on Saturdays.
   - Annual members: Consistent usage throughout the week, slightly higher on weekdays.
3. **Monthly Patterns**:
   - Both user types show increased usage during summer months.
   - Casual riders’ usage spikes in summer and decreases in winter.
   - Annual members maintain steadier usage across seasons.

## Visualizations
### 1. Average Ride Length by User Type
- Bar chart showing the comparison of average ride lengths between casual riders and annual members.

### 2. Rides by Day of the Week
- Column chart illustrating the number of rides per day of the week for both user types.

### 3. Monthly Ride Patterns
- Line chart depicting the monthly ride counts, showing seasonal trends and differences between user types.

## Key Findings
- Casual riders have longer average ride lengths and prefer weekends.
- Annual members use bikes more consistently, with a focus on weekdays.
- Both groups increase their usage in the summer, but casual riders show a more significant spike.

## Recommendations
1. **Targeted Weekend Promotions**:
   - Launch weekend promotions to convert casual riders to annual memberships.
2. **Commuter Incentives**:
   - Develop marketing campaigns highlighting the benefits for daily commuters.
3. **Seasonal Campaigns**:
   - Implement membership drives during peak usage times (late spring and summer).

## Conclusion
Understanding the distinct usage patterns of casual riders and annual members allows Cyclistic to create targeted marketing strategies to convert casual riders into annual members. This approach will enhance user retention, increase revenue stability, and support long-term growth.

## Skills Demonstrated
- Data Preparation
- Data Cleaning and Transformation
- Data Analysis and Visualization
- Insights Derivation and Recommendations
- Use of Excel/Google Sheets for Analysis
- Creating Visualizations with Data Visualization Tools
