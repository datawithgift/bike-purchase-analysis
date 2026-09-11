# Bike-Purchase-Analysis (with an Interactive Excel Dashboard)

## Business Objective 
To understand customer purchasing behavior and identify customer characteristics associated with bike purchases to support customer segmentation and targeted marketing.

## Dataset Used
- <a href="https://github.com/datawithgift/bike-purchase-analysis/blob/main/Bike-Purchase-Analysis.xlsx">Dataset</a>

## Raw Data Used
- <a href="https://github.com/datawithgift/bike-purchase-analysis/blob/main/Bike_Buyers_Raw_Data.xlsx">Raw Data</a>

## Questions
-	Which customer demographics are most associated with bike purchases?
-	Which age group has the highest bike purchase rate?
-	Which income group is most likely to purchase a bike?
-	Does commute distance influence bike purchasing behavior? 
-	Is bike purchasing behavior associated with gender?
-	Which occupations have the highest number of bike buyers?
-	Which region has the highest bike purchase rate?
-	Dashboard interaction <a href="https://github.com/datawithgift/bike-purchase-analysis/blob/main/Bike%20Purchase%20Dashboard.PNG">View</a>

## Data Cleaning & Analysis Process 

1. Data Understanding
- Reviewed all columns and understood what each variable represents.
- Identified the objective of the analysis.
- Defined the key questions the dataset could answer.

2. Data Cleaning
- Checked the dataset for duplicate records.
- Removed unnecessary leading and trailing spaces from the data using text-cleaning techniques.
- Standardized Gender values by replacing F with Female and M with Male.
- Standardized Marital Status values by replacing M with Married and S with Single to make the data easier to interpret.
- Standardized text entries and capitalization across categorical columns (e.g., ensuring values such as Bachelor etc were consistently formatted).
- Converted the Income column to currency format for easier interpretation.
- Standardized Commute Distance values by changing 10+ Miles to 10 Miles+ to make the category clearer for analysis.

3. Data Transformation
- Created an Income Group column to categorize customers based on income into:
Low Income
Middle Income
High Income
Used the IFs function to assign customers to the appropriate income group.
- Created an Age Group column to categorize customers into:
Young (<=34)
Middle-aged (<=54)
Old (>54)
Used the IFs function to create the age-group categories.

4. Analysis
- Used the cleaned and transformed dataset to explore relationships between customer demographics and bike purchasing behavior.
- Analyzed bike purchases across factors such as gender, age group, income group, commute distance, and other demographic characteristics.
- Identified patterns and trends that could help explain differences in bike purchasing behavior.


## Dashboard 
<img width="1277" height="432" alt="Bike Purchase Dashboard" src="https://github.com/user-attachments/assets/444cb658-ba9b-4f1c-aaa0-28233d73d617" />
 

## Key Insights & Findings
- Bike purchases where more common among male, middle-aged and lower-income customers, with purchasing patterns also varying by region and occupation.
- The low-income group recorded the highest number of bike purchases.
- Customers with shorter commute distances showed higher purchase volume, while the 10 miles + group had fewer purchases.
- Middle-aged customers recorded the highest number of bike purchases among the age groups analyzed, indicating that this segment showed a stronger tendency to purchase bikes.
- Male customers recorded a higher number of bike purchases than female customers.
- Professionals recorded the highest number of bike purchases among the occupations analyzed
- North America recorded the highest number of bike buyers.
- 
## Recommendation 
- Focus marketing efforts on customer groups with higher bike purchase activity.
- Offer affordable bikes, discounts, or flexible payment options to attract more customers in this group.
- Use commute distance to help identify and prioritize customers who are more likely to purchase bikes in future marketing campaigns.
- Focus marketing efforts on middle-aged customers and highlight benefits relevant to this group.
- Continue targeting the male customer segment while developing strategies to increase engagement and purchases among female customers.
- Prioritize professionals as a potential target segment and conduct further research to understand what drives their higher purchase activity.
- Prioritize North America as a strong market while investigating the lower-performing regions to identify opportunities to improve bike purchases. 
