# Table of Contents

- [Project Background](#project-background)
- [Executive Summary](#executive-summary)
- [Insights and Deep-Dive](#insights-and-deep-dive)
- [Recommendations](#recommendations)
  

# Project Background

East Coast Insurance Company is a fictional property and casualty insurance company that underwrites insurance primarily in the United States East Coast.

East Coast Insurance Company has claims data for the first three months of the year and the director of claims has requested that we create a visual dashboard for all the claims data we have received. This dashboard will accessed by multiple stakeholders and users within the company including claims directors, claims managers and unit managers in specific regions. The visual dashboard will be used to replace older static reports.

Insights and recommendations are provided in the following key areas:


  - **Claims trends for the first quarter of the year**: Claims data for the first quarter of the year for Multi-vehicle, single-vehicle, vehicle theft and parked car claims.
  
  - **Total claim amounts**: Breakdown of the median vehicle claim amount, median injury claim amount and total claims amount for January, February and March.
  
  - **Visualization of claimant profiles**: Claimants are visualized by their average age, sex, and education levels.

  ① An interactive PowerBI Dashboard of the First Quarter Claims data can be accessed [HERE](https://app.powerbi.com/view?r=eyJrIjoiNGY2Y2Y4NDItYzBjNC00NWU3LWEyNjgtYjYyYmIyOWQwYzNkIiwidCI6IjVhMmY2ZmQxLTU3MzctNGY3Ny04MmNkLWQ4MGNhMGNkZjZiYSJ9)

  ② The Command line queries used to create the relational database in Microsoft SQL Server 2022 can be found [HERE](https://docs.google.com/document/d/1zbn_qlT9KoIrOmZKwxY815IANsueGfNZLKpobNBBSJ0/edit?usp=sharing)


# Data Structure & Initial Checks

East Coast Insurance Company database structure consists of five tables claims_fact, policy_dim, insured_dim, incident_dim and vehicle_dim with a total row count of approximately 1000 records.


<img width="844" alt="Star Schema" src="https://github.com/user-attachments/assets/4df24c28-dc26-4740-8f54-cc43624d7292">


  Fact Table: claims_fact
      Measures related to claims, including amounts and fraud reporting.
  
  Dimension Tables:
      policy_dim: Policy details.
      insured_dim: Information about the insured individual.
      incident_dim: Details about the incident.
      vehicle_dim: Information about the vehicle involved in the claim.

The Command line queries used to create the relational database in Microsoft SQL Server 2022 can be found here [LINK](https://docs.google.com/document/d/1zbn_qlT9KoIrOmZKwxY815IANsueGfNZLKpobNBBSJ0/edit?usp=sharing)


# Executive Summary


![East Coast Insurance Dashboard](https://github.com/JevaughnNewman/East-Coast-Insurance-Data-Project/blob/936f2d2c9559cc9b704f25111e9be676884a144a/East%20Coast%20Insurance%20Dashboard%202025.png)


# Insights and Deep Dive

  The total number of single and multi-vehicle accidents decreased monthly from January to March. This may be attributable to overall improvements in weather conditions.
  
  The average total claim amount for female drivers involved in an accident categorized as "Major Damage" in Q1 was approximately $64,070.00. However, in March total median claim amount for female drivers involved in an accident categorized as "Major" increased to $72.8K, which is $8.7K above the median.

  The average age of the female drivers involved in these accidents was also lower than the median age of our female customers. The median age of all female drivers is 38.9 years old. The median age for a female driver involved in an accident considered "major" in March was 31.67, with the most common education levels completed being high school and JD.
  
 # Recommendations

 1) Policy Pricing Adjustments:
    - Given the observed trends in younger female driver claims, revisiting underwriting policies and risk models might help to capture risk profiles that may be evolving.
      
    - Management could assess whether pricing adjustment or loyalty programs for safe drivers could help encourage safer driving behaviours
      
    - **Offering telematics-based discount programs**: Offering a voluntary program where high-risk claimants, such as younger drivers or those involved in repeated accidents, can reduce premiums by agreeing to use telematics or mobile insurance applications to track driving behaviours, such as breaking, speed and acceleration.

 2) Targeted Driver Risk Mitigation for Younger Female Drives:
    - The median age for female drivers involved in major accidents in March (31.67) is significantly lower than the median age of female drivers (38.9)
      
    - It may be beneficial to develop targeted education or engagement initiatives for younger female drivers, focusing on defensive driving strategies and insurance education.
   
 3) Seasonal Accident Trends Monitoring:
     - Since accident rates increased from January to March, likely due to weather improvements, management can explore offering a seasonal safety campaign. Providing winter-driving tips and enhancing communications around safe driving during           adverse weather conditions
    
