# Project Background and Overview

An unknown car insurance company has released its annual data, which includes detailed information on policyholder's demographics, vehicle specifications, driving history, and whether a claim was filed. This project leverages a machine learning model to predict whether the policyholder will file a claim based on these attributes. Additionally, the project identifies the key factors influencing claim likelihood, providing insights that can enhance pricing strategies, improve risk assessment, and streamline the insurance application process through automation.

This project will enhance the company's performance in the following key areas:
- **Risk Assessment** 
- **Marketing Strategy**
- **Cost Reduction**

North Star Metrics:

**Claim Counts / Claim Amounts **

# Data Structure

The target feature in the dataset is called **OUTCOME**, which has either a value of 0 or 1; 0 means no claim was made and 1 means a claim was made by the policyholder.

Other than OUTCOME, the dataset consists of 18 features in the following categories:

**Demographic Information:** Age, gender, education, income, etc.

**Vehicle Specifications:** Ownership, vehicle year, annual mileage, etc.

**Driving Record:** History of duis, speeding violations, past accidents

# Executive Summary

### Overview of Findings:

Driving experience consistently proved to be the best indicator of whether a claim is filed, with vehicle year being a strong second, in both model performance and the correlation. Our Gradient Boost Classifier model achieved an accuracy of 85.6%, generalizing well with unseen data and may prove useful in automating the application process if integrated. The ML model can also be used to improve pricing strategies by more accurately determining how risky a policyholder will be in the future and adjusting insurance premiums accordingly. More information should be gathered about the policyholders regarding vehicle brand,  

# Recommendations:
- Work with the marketing team to tailor advertisements and lower rates towards potential customers with more driving experience and newer vehicles
- Consider offering varied rates for driving safety (assessed via telematics) targetted at policyholders with lower driving experience
  - This does two things:
    - Rewards safer drivers with lower premiums, benefiting both the driver and the company by retaining low risk policyholders
    - Leverages overconfidence (a common cognitive bias) in less safe drivers, allowing the company to justify higher premiums for those with lower driving experience, ultimately reducing the risk of taking on high-risk policyholders
- Work with underwriters to implement the model with their work to improve efficiency and reduce labor costs







