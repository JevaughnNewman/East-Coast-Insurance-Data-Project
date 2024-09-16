# Project Background

East Coast Insurance Company is a fictional property and casualty insurance company that underwrites insurance primarily in the United States East Coast.

East Coast Insurance Company has claims data for the first three months of the year and the director of claims has requested that we create a visual dashboard for all the claims data we have received. This dashboard will accessed by multiple stakeholders and users within the company including claims directors, claims managers and unit managers in specific regions. The visual dashboard will be used to replace older static reports.

Insights and recommendations are provided in the following key areas:



  

An interactive PowerBI Dashboard of the First Quarter Claims data can be accessed INSERT LINK

The Command line queries used to create the relational database in Microsoft SQL Server 2022 can be found INSERT LINK


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


# Executive Summary


![East Coast Insurance Dashboard](https://github.com/user-attachments/assets/e0f27bdc-fc51-428a-b7d5-3f12b25afad7)


# Insights and Deep Dive
# Recommendations

