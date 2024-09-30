# Project Background and Overview

An unknown car insurance company has released its annual data, which includes detailed information on policyholder's demographics, vehicle specifications, driving history, and whether a claim was filed. This project leverages a machine learning model to predict whether the policyholder will file a claim based on these attributes. Additionally, the project identifies the key factors influencing claim likelihood, providing insights that can enhance pricing strategies, improve risk assessment, and streamline the insurance application process through automation.

This project will enhance the company's performance in the following key areas:
- **Loss Ratio** 
- **Marketing Strategy**
- **Labor Cost Reduction**

# Data Structure

The target feature in the dataset is called **OUTCOME**, which has either a value of 0 or 1; 0 means no claim was made and 1 means a claim was made by the policyholder.

The **OUTCOME** feature has a skewed distribution in the data, with negative claims making up 68.7% of total claims. This is addressed via oversampling during the project, which fixes the class inbalance when training training the model. 

Other than **OUTCOME**, the dataset consists of 18 features in the following categories:

**Demographic Information:** Age, gender, education, etc.

**Vehicle Specifications:** Ownership, vehicle year, annual mileage, etc.

**Driving Record:** History of duis, speeding violations, past accidents

# Executive Summary

### Overview of Findings:

Driving experience consistently proved to be the best indicator of whether a claim is filed, with vehicle year being a strong second. Our Gradient Boost Classifier model achieved an accuracy of 85.6%, generalizing well with unseen data and can be used for increasing efficiency in the insurance application process. The model can also be used to improve pricing strategies by more accurately determining how risky a policyholder will be in the future and adjusting insurance premiums accordingly. Overall, the model will prove useful for improving the company's loss ratio and risk assessment for current and potential policyholders.

PowerBI dashboard can be found [here](https://app.powerbi.com/groups/me/reports/4cfc561a-77f1-4c41-b08f-1100f948a388/ed711182fcaa385c89ec?experience=power-bi) or viewed below:

![Alt text](https://github.com/julianlu03/Car-Insurance-Claims-Classifier/blob/main/car_insurance_dashboard.PNG?raw=true)

# Recommendations:

Based on the insights uncovered during analysis and the results of our model, the following recommendations have been provided:
- Work with the marketing team to tailor advertisements and lower rates towards potential customers with more driving experience and newer vehicles. This will increase customer rentention through lower rates and benefit the company with low risk policholders
- Consider offering varied rates for driving safety (assessed via telematics) targetted at policyholders with lower driving experience
  - This does two things:
    - Rewards safer drivers with lower premiums, benefiting both the driver and the company by retaining low risk policyholders
    - Leverages overconfidence (cognitive bias) in less safe drivers, allowing the company to justify higher premiums for those with lower driving experience, ultimately reducing the risk of taking on high-risk policyholders
- Work with underwriters to implement the model for the purposes of automating the screening process
  - Implementing this model can automatically screen out high-risk candidates before they reach an underwriter, which not only enhances productivity but also reduces labor costs for the company by streamlining the workflow




