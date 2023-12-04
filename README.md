### Description (ENG)
Maintaining and stimulating user activity is an important task for a product like ours. To do this, our team of marketers decided to organize a flashmob in the news feed: participants must make a post where they tell some interesting fact about themselves and publish it with a hashtag. The three posts with the most likes receive prizes.

The flashmob took place from 2023-10-12 to 2023-10-18. Our task as an analyst is to evaluate the effectiveness of this event.

**Task:**

1) Guess which metrics should have changed during the flashmob and how. Why? Offer at least 5 metrics.
2) Check if these metrics actually changed using CausalImpact. If a change actually occurred, describe exactly how the metric changed and by how much.
3) Did the flashmob have any long-term effects? Draw conclusions.

**Selecting metrics:**

Metrics were selected based on the following logic:

- Flash mob stimulates user activity $\Longrightarrow$ we expect an increase in **DAU**, **views** and **number of new users** who want to take part in the competition or simply help a friend with a like.

- To receive a prize, you must collect the largest number of likes $\Longrightarrow$ we expect a significant increase in **total number of likes**, as well as **number of likes per user** and, possibly, a change in **CTR** and **number of views per user**.

Thus, we're gonna consider the following metrics: **DAU**, **views**, **number of new users**, **likes**, **likes per user**, **CTR** and **views per user**.

### Results

**General conclusion:** on the one hand the flashmob had a positive, statistically significant impact on the total number of likes and views of users. At the same time, the increase in activity in the application was limited only to the flashmob period and had no visual impact on these metrics in the long term. Also, during the flashmob, not only likes and views increased, but also related metrics - the number of likes and views per user. The changes are statistically significant. In addition, there was a small but statistically significant increase in CTR.
