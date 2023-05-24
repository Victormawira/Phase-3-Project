# Business Understanding

In the 21st Century, communication has been improved from letters and word of mouth to data transmission through text, voice, audio or video across the globe. This has been contributed by the development of telephone and transmission mediums that supports it like radio, wire and optics through which they transmit the data. The world has greatly embraced this technology to the extent that almost every single person has a mobile phone. This development has lead to the development of companies that offer communication support services.
When many companies offering similar products and services arise, consumers usually have a wide range of choices in regards to which services and service provider to consider. Therefore, customer satisfaction and checks to ensure that customers are likely to purchase the products are important as the company stays in business because of monetary rewards generated from the sale of their products. The above project is aimed at helping the management of SyriaTel Telecommunication company discover whether their customers will remain in business with them and  the amount of money lost when customers don’t stay in business with them.

Objectives for the project include:
- Investigate labeled data on customers who use the company's services
- Provide inferential statistics and visualisations based on this data.
- Create predictive, supervised learning models from the data to predict churn


By conducting the above project, the management for SyriaTel Telecommunication company will be enlightened to know their average sales per day and the probability of losing their customers and the lose they will undergo if a customer failed to subscribe.

The parameters of this model were:
- `loss = 'exponential'`
- `learning_rate = 0.01`
- `min_samples_leaf = 0.1`
- `min_samples_split = 0.1`
- `max_depth = 3`
- `SMOTE balancing`
- `StandardScaler`

## Definitions:

- Churn:  a customer who closes their account with SyriaTel.  A prediction of `True` relates to a customer who will churn. 
- Predictive model:  

## Conclusions

As we can see above, our model did not perform as well as hoped on the test data.  2.9% of predictions of this model are false negatives.  We have reduced this down to a reasonable number.  

With more time and further iterations, this score could continue to be improved upon. 
  

## Next Steps and Future Investigation:

It was highlighted during the EDA of this project that there are many areas which the company could improve to help reduce high churn factors.  Below are some possible suggestions of what could be further investigated:
- Further investigation should be devoted to looking into the other characteristics of these customers to find out why there was a need to make this many calls to customer service and how the company could better assist these customers.
- Given that over 39% of international plan holders churn, further investigation into retention efforts for these customers might be a worthwhile effort. 
- Further investigation should be done to see what is going on in these high churn states to see what trends might be causing this.
- Investigate ways to incentivise customers with total day charges over $50 to stay with with the company by creating added value and perks.  This investigation found that 100% of these customers churn.
