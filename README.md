# Article-Recommender-system-using-Implicit-data

Recommender systems are everywhere, helping you find everything.

The goal for the project is to develop a recommender system with implicit data collection which is clickstream data, in our case. I have used data from Articles sharing and reading from CI&T DeskDrop. Deskdrop is an internal communications platform that allows companies employees to share relevant articles with their peers, and collaborate around them.

The data contains about 73k users interactions on more than 3k public articles shared in the platform, more importantly, it contains rich implicit feedback, different interaction types were logged, making it possible to infer the user’s level of interest in the articles.

Implicit Library has been used, a Fast Python Collaborative Filtering for Implicit Datasets, for our matrix factorization.
