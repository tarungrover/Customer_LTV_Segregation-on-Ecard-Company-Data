# Customer_LTV_Segregation-on-Ecard-Company-Data
 Project in R
 
 Your client is an online greeting card company. The company offers monthly subscriptions at a rate of $1 per month for access to their eCard website. The client is interested in understanding the life-time value (ltv) of their customers.

The life-time value of a customer is defined as the total revenue earned by the company over the course of their relationship with the customer.

The enclosed (synthetic) data represent usage statistics for 10,000 customers. Usage is summarized at a daily level and covers a period of 4 years from 2011-01-01 to 2014-12-31. 

The following is a description of each field captured in the enclosed data set.

id: A unique user identifier
status: Subscription status '0'- new, '1'- open, '2'- cancelation event
gender: User gender 'M'- male, 'F'- female
date: Date of in which user 'id' logged into the site
pages: Number of pages visted by user 'id' on date 'date'
onsite: Number of minutes spent on site by user 'id' on date 'date'
entered: Flag indicating whether or not user entered the send order path on date 'date'
completed: Flag indicating whether the user completed the order (sent an eCard)
holiday: Flag indicating whether at least one completed order included a holiday themed card

Tasks

1.	Develop an attrition model, to predict whether a customer will cancel their subscription in the near future. Characterize your model performance.

2.	Develop a model for estimating the ltv of a customer. Characterize your model performance.

3.	Develop a customer segmentation scheme. Include in this scheme the identification of sleeping customers, those that are no longer active but have not canceled their account. 

