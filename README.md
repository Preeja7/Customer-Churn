# Customer-Churn

# Defining problem statement
The data set belongs to a leading DTH company. The company wants to know the customers who are going to churn, so accordingly they can approach customer to offer some promos.

# Constraints:
In this company, account churn is a major issue because 1 account can have multiple customers. hence by losing one account the company might be losing more than one customer. 
Another constrain is customers leaving without voicing their complaints.

# Scope: 
The scope of this project is to identify factors contributing to customer attrition and thereby recommend strategies that may help in regain trust and improve the overall customer satisfaction levels.

# Approach:
1.	In this project, I have tried to divide customer churn prediction problem into steps like exploration, profiling, clustering, model selection & evaluation. Based on this analysis, we can help retention team to analyse high risk churn customers before they leave the company.
2.	Moreover, we can add on different data sources like customer inquiries, seasonality in sales, more demographic information to make our prediction more accurate.
3.	From the results and explanations presented here, some conclusion can be draw:
The type of account segment has a strict relationship with churned clients, Low Tenure with high complaints could lead a client to leave the service. Clients with a greater number of account_user_count tend to leave.


We can now see that the main factors are.
1.	Customer Demography:
    
    Tenure
      a) Longtime customers are less likely to leave the company.
      b) Loyalty
    
    Gender
      a) Male customers tend to churn more.
      b) Attrack them with some sports, games, and discovery type channels combo packages.

2.	Customer record analysis:
  	
    Account_segment
      a) People having Regular Plus are more likely to leave.
      b) Is there something wrong with the Regular Plus segment?

3.	Customer care service analysis:
    
    Complain_ly
      a) People having more complaints are more likely to leave.
      b) Are customers unhappy with the solution given by customer service.
  	
    Service score
      a) Low score given by customers tend to churn.
      b) Resolve their problems by giving them good offers like cashback or free channels for one month.

# Business Implications:
Depending on the re-engagement campaign, it can be a good trade-off to target the highest possible number of customers at risk to churn, and in parallel unintentionally reach some happy customers, than to leave a high number of customers to cancel without taking proper actions.

It is generally thought to cost five times more to gain a new customer than it costs to keep an existing customer, and from research it shows that boosting your customer retention rate by 5% leads to a profit increase of 25% to 95%.

This makes intuitive sense if you think about all the steps involved — there’s a high associated acquisition cost with acquiring and educating a new customer. You must find a customer, learn their needs, position your product, onboard the new client, and then wow them to stay in the first critical months. That is a lot of steps…

Wouldn’t it be nicer to keep the customers you already have than work twice as hard on the acquisition front? I think so…

# Business Recommendations:
1.	Complaint redressal needs to be a major focus point as a large number of customer attrition is attributed to complaints. To address this, a dedicated customer service team needs to be formed that is trained to be sensitive about complaints and trained to appropriately handle such complaints. Customers should have the option to directly contact this team for faster resolution, through dedicated IVR (Interactive Voice Response) options or dedicated chat links on the company’s website. 
2.	The fact that customers who have recently contacted the CC have attritted more than customers who have not contacted, points to the fact that these customers were unhappy with the way they were dealt with. To address this, the CC staff needs to be trained on technical and soft skills to enable them to provide outstanding customer service. A dedicated training team working in sync with the supervisors would be effective in understanding where the staff is lacking and then accordingly train them to be more effective. This will enhance the customer experience and would greatly help in regaining the customer’s trust.
3.	Tier 2 & 3 customers are more likely to attrite. A survey comprising of both close-ended and open-ended questions would help in understanding the factors leading to tier 2 and tier 3 attritions.
4.	Monitor the issues raised by the Tier 2 and Tier 3 customers to understand the major areas of improvement.

# Conclusion: 
No algorithm will predict churn with 100% accuracy. There will always be a trade-off between precision and recall. That is why it is important to test and understand the strengths and weaknesses of each classifier and get the best out of each. If the goal is to engage and reach out to the customers to prevent them from churning, it is acceptable to engage with those who are mistakenly tagged as ‘not churned,’ as it does not cause any negative impact. It could potentially make them even happier with the service. This is the kind of model that can add value from day one if proper action is taken out of meaningful information it produces.
