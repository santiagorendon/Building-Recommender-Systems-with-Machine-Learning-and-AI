# Title

## Pre-watch questions
what is churn?
what is responsiveness?
How are a/b tests used in recommender systems.

## Chunk 1
(only write concepts)
churn
responsiveness
a/b tests
online vs offline
surrogate problem


## Chunk 1 converted
- the `3 main points`
- the `plain English explanation`
- `why it matters`
- `one example`

### 3 main points
1. Churn - How much user interactions affect the recommendations. If a user likes only one pokemon trading card video and now they have only pokemon recommendations that will be high churn. However if you show same results for long time despite other interactions that is low churn. Like all metrics there is a balance to find.
2. Responsiveness - how quickly recommendations change based on interaction. Think tiktok where based on user interactions recommendations change almost realtime, however these realtime systems come with a lot of expenses and complexity tradeoffs.
3. A/B tests, the ultimate way to evaluate your recommender models. A lot of time offline says we will do well but then actual online performance is bad. This is most important evaluation

Churn and responsiveness are other metrics that you need to tune in recommendation systems. Churn is how volatile recommed system is when seeing new user data, responsiveness is speed that recommendation system can change from near realtime to several days. Finally we go over the best way to evaluate your model which is a/b testing. Netflix and Youtube have noticed surrogate problem which is offline doing well but online doing poorly. At end of day testing with real users is best, given algorithm recommendations do not always perform the best. Youtube says its less of a science and more of an art so algorithm will not always win even if in theory it should.

## Chunk 1 compressed
Concept: churn responsiveness and ab tests help us evaluate our recommendation systems.
Why it matters: ab tests is best way to evaluate recommender models, online is ultimate tests where users vote with their wallets.
Example: 
One confusion: offline metrics do not actually predict online success all the time and so online ab testing is best way to evaluate recommender models.
