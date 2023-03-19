# House Insurance Customer Retention
## Introduction
* Kangaroo is a House Insurance American Company that is concerned about the company’s retention rates and wants to know what is causing policy cancellation and also retain existing customers.
* The Kangaroo data set is based on 4 years of property insurance policies from 2013 to 2017. There are almost 30,000 policies in our dataset.  
* The aim of this project is to create a retention model to identify policies that will be renewed or canceled before the end of the term and understand what variables are most influential in causing a policy cancellation. 
## Business Case
* Homeowners Insurance is a valuable policy option that provides coverage for not just the house but also its contents and the owner's liability. Approximately 85% of homeowners have home insurance policies, according to data from the National Association of Insurance Commissioners (NAIC).
* The average annual cost of homeowners insurance in the U.S. is $1,445, according to Value Penguin's 2021 analysis using a sample policy in each state. 
* The average money spent on homeowners’ insurance coverage has risen in the past several years, across all forms of policy, based on the NAIC's survey of premiums spent. This increase in premium may be attributed to the early cancellation of claims. 
* To understand this better, we chose to work on this project. The goal of this project is to understand the factors that are driving the customer to continue or cancel the existing policy.
## Metric
* Our goal is to decrease the number of customers who have been incorrectly classified as not having canceled their insurance policy. 
* This is important because such misclassifications can result in missed opportunities for the company to take proactive measures to retain customers who may be considering canceling their policy. 
* By accurately identifying these customers, the company can implement preemptive steps to prevent them from leaving the policy, ultimately improving customer retention and satisfaction.
## Data Dictionary
  ![image](https://user-images.githubusercontent.com/48169929/226154408-74f0f330-5bc5-47b8-ba68-868f5f684f18.png)
## Insights
### Zone Vs Cancel
* For kangaroo company, the number of canceled policyholders are coming from 2,6 i.e., Arizona and Iowa, whereas the least cancellations are coming from Virginia and Pennsylvania.
  ![image](https://user-images.githubusercontent.com/48169929/226154432-736822bd-a8e8-43ea-a0eb-4bc71f5fc641.png)
![image](https://user-images.githubusercontent.com/48169929/226154444-ffe45466-7a96-44cb-89f2-b552f0c8b27a.png)
### Sales Channel Vs Cancel
* For the majority of continuing policies, the preferred sales channel is via a broker, whereas for canceled policies, it is via phone and broker
  ![image](https://user-images.githubusercontent.com/48169929/226154526-52d27d62-e056-4bbf-85d5-246a6ee3d8c1.png)
### Number of Claims Vs Cancel
* Cancelled policies tend to show higher claim rate when compared to continuing policies
  ![image](https://user-images.githubusercontent.com/48169929/226154587-b35f0da2-575f-494d-9f83-0d31f4b64310.png)
### Credit Vs Cancel
* It seems like continuing policyholders are having a high credit scores, but the reverse is not true, high credit customers don’t mean they will continue the policy.
  ![image](https://user-images.githubusercontent.com/48169929/226154850-629612d9-555a-44b9-aa48-589761ddabb5.png)
## Model Comparison
  * Our criteria is to reduce the number of customers who have been misclassified as not canceled (FP). Considering this, Majority Voting gave the best result in terms of sensitivity.
  ![image](https://user-images.githubusercontent.com/48169929/226154929-96d6043b-3ff7-48b5-a6e0-f539e65004ee.png)
## Recommendations
* To concentrate on the zones of Arizona and Iowa states by rolling out offers, because there is a rise on customers canceling their membership in these areas.
* To focus on customers who are claiming benefits- offering a nominal subsidy on their next premium, which might retain their membership with the business
* We want to advise the company to give preference to customers with high credit scores, as we can infer low, and medium is included to cancel the plan.
*  Offering reasonable premiums for customers with low/medium credit scores would retain the customers with the company
 


