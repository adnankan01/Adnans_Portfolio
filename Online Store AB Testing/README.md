## Making Business Decisions Based on Data Project Description
- You are an analyst at a big online store. Together with the marketing department, you've compiled a list of hypotheses that may help boost revenue. You need to prioritize these hypotheses, launch an A/B test, and analyze the results.

### Description of the data
Data used in the first part of the project
/datasets/hypotheses_us.csv

### Hypotheses — brief descriptions of the hypotheses
- Reach — user reach, on a scale of one to ten
- Impact — impact on users, on a scale of one to ten
- Confidence — confidence in the hypothesis, on a scale of one to ten
- Effort — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

### Data used in the second part of the project
/datasets/orders_us.csv

- transactionId — order identifier
-visitorId — identifier of the user who placed the order
-date — of the order
-revenue — from the order
-group — the A/B test group that the user belongs to

### Project description 2
/datasets/visits_us.csv

- date — date
- Group — A/B test group
- visits — the number of visits on the date specified in the A/B test group specified

Make sure to preprocess the data.
There might be mistakes in the original datasets; for example, some of the visitors might have gotten into both group A and group B.
