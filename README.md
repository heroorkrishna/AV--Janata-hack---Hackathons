# AV-Janta-Hack-Recommendation

Your client is a fast-growing mobile platform, for hosting coding challenges. They have a unique business model, where they crowdsource problems from various creators(authors). These authors create the problem and release it on the client's platform. The users then select the challenges they want to solve. The authors make money based on the level of difficulty of their problems and how many users take up their challenge.

The client, on the other hand makes money when the users can find challenges of their interest and continue to stay on the platform. Till date, the client has relied on its domain expertise, user interface and experience with user behaviour to suggest the problems a user might be interested in. You have now been appointed as the data scientist who needs to come up with the algorithm to keep the users engaged on the platform.

The client has provided you with history of last 10 challenges the user has solved, and you need to predict which might be the next 3 challenges the user might be interested to solve. Apply your data science skills to help the client make a big mark in their user engagements/revenue.


## Dataset Description
We have three data files:

* train.csv: It contains the set of 13 challenges that were attempted by the same user in a sequence
* challenge_data.csv: Contains attributes related to each challenge
* test.csv: Contains the first 10 challenges solved by a new user set (not in train) in the test set. We need to predict the next 3 sequence of challenges for these users.

**Note**: The format is given by "user_id_challenge_sequence". For example, for user ID 2 you must predict the next 3 challenges with sequence 11, 12 and 13 respectively. The corresponding user_sequence would be given by 2_11, 2_12 & 2_13.

### Evaluation Metric
The evaluation metric is Mean Average Precision (MAP) at K (K = 3). MAP is a well-known metric used to evaluate ranked retrieval results. E.g. Let’s say for a given user, we recommended 3 challenges and only 1st and 3rd challenges are correct. So, the result would look like — 1, 0, 1
In this case, The precision at 1 will be: 1*1/1 = 1 The precision at 2 will be: 0*1/2 The precision at 3 will be: 1*2/3 = 0.67 Average Precision will be: (1 + 0 + 0.67)/3 = 0.556. The formula is:

[Problem Statement](https://datahack.analyticsvidhya.com/contest/janatahack-recommendation-systems/#ProblemStatement)

.

# Leaderboard
* **[Public LB](https://datahack.analyticsvidhya.com/contest/janatahack-recommendation-systems/#LeaderBoard)** : **46th**
* **[Private LB](https://datahack.analyticsvidhya.com/contest/janatahack-recommendation-systems/#LeaderBoard)** : **46th**


