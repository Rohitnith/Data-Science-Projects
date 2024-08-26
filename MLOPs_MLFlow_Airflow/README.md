# Lead-Scoring problem MLoPs using Airflow & ML flow
## Problem Statement:

You learnt that CodePro is an EdTech startup that had a phenomenal seed A funding round. 
It used the money to increase its brand awareness. As the marketing spend increased, it got several leads from different sources. Although it had spent significant money on acquiring customers, it had to be profitable in the long run to sustain the business. 
The major cost that the company is incurring is the customer acquisition cost (CAC). Now, we will discuss what customer acquisition means.

At the initial stage, customer acquisition cost is required to be high in companies. But as their businesses grow, these companies start focussing on profitability. Many companies first offer their services for free or provide offers at the initial stages but later start charging customers for these services. For example, Google Pay used to provide many offers, and Reliance Jio in India offered free mobile data services for over a year. Once these brands were established and brand awareness was generated, these businesses started growing organically. At this point, they began charging customers.

Businesses want to reduce their customer acquisition costs in the long run. There are many ways to do that. 
The reasons for the high customer acquisition cost are as follows:

- Improper targeting 
- High competition
- Inefficient conversion

# How can help in the reduction of CodePro’s CAC?

1. Improper targeting can be resolved by the marketing team. They can do so using better targeting strategies and using ad recommendations.
2. To resolve the issue of high competition, brand differentiation is required, which can be taken up by the product team.
3. To address inefficient conversion, the sales team must undergo upskilling and prioritise the leads generated.
4 . The sales team must work with the data science team to figure out how to prioritise leads. The data science team must come up with lead scoring for all the leads generated.

# The main objectives of lead scoring are as follows:

Remove Junk by categorising leads on the basis of propensity to purchase
Gain insights to streamline lead conversion and address improper targeting
We have chosen L2AC (Leads to Application Completion) as our business metric, as choosing L2P (Leads to Payment) will aggressively drop the leads.
A lead is generated when any person visits CodePro’s website and enters their contact details on the platform. A junk lead is generated when a person who shares their contact details has no interest in the product/service.

Having junk leads in the pipeline creates significant inefficiency in the sales process. Thus, the goal of the data science team is to build a system that categorises leads based on the likelihood of their purchasing CodePro’s course. This system will help remove the inefficiency caused by junk leads in the sales process.
we are creating three different pipelines for our use case.

1. Data Pipeline
2. raining Pipeline
3. Inference Pipeline

## Our system metrics for the ML model are :
- AUC score >75%
- Precision > 65%
- Recall > 75%

Since this is the first iteration of the model we are not aiming for high performance from the model but we are aiming to get value from the model as soon as possible by deploying the model into production, and then continuously improving our model once our baseline is deployed. Thus we will not focus much on developing the best possible model but we will make do with a simple model and focus more on deploying it into production.

## We will create the pipelines for getting the final output
