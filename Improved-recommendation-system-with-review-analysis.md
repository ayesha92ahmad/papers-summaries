<h1>Improved Recommendation System with Review Analysis</h1>

This is a paper by Ms. Vinaya B. Savadekar and Mr. Manoj E. Patil.

In this paper the authors talk about recommender systems and the different kinds of recommender systems that are present today. Most existing recommendation systems undergo the scalability and efficiency problem in processing data. The authors present an English language keyword list and domain thesaurus based personalized recommendation method.

---
Keywords: Big data, Hadoop, Map reduce, User Preferences, Recommendation systems
---
# Introduction:
1. Big data: datasets that are too big to capture, store, manage and analyse.
2. Recommendation systems provide suggestions of of items that a user might like. It helps users identify useful products in a mass of large number of products.
3. Current recommendation methods are divided in to 3:
   a. Content based - User's preferences from the past
   b. Collaborative
      - Item based CF - same user
      - User based CF - different users with similarity
   c. Hybrid - Mix of the two
--
# Problem statement and objective:
1. Previous system suffers from scalibily and inefficiency problems while processing large amount of data.
2. Authors claim that the paper processes a novel method or personalized recommendation system:
          - Keyword lists are maintained for different domain.
          - Preference are taken from users.
          - Similar users are searched for by using keyword extraction and similarity calculations
          - Keywords are classified, weights of review of similar users are calculated.
          - Recommendation list of top-k items are generated.
          
# Literature survey:
For their literature survey they have done comparisons between different recommendation techniques 

# Recommendation Method
1. User based collaborative filtering algorithm to generate appropriate recommendations.
2. Specialized domain thesauruses are built to support the keyword extraction and dfferent domain thesauruses are built for different domains.

# Results
MAE has been used as accuracy metric. Lower the MAE better the accuracy.
MAE of this product has been compared to KASR-ASC, KASR-ESC, UPCC and IPCC and is apprantly better.

---
Why I like about this paper?
1. Easy to understand because it was very basic. 
2. Did not show me crazy mathematical equations( I will be moving to them slowly but initially I'd like to see simpler papers.
3. I liked how they have used reviews to increase the accuaracy of recommendation.

What I didn't like about this paper?
1. Too general. Explains the concept of recommendation systems more than the project. 
2. I believe that similar keywords may not mean that users are similar. Eg. Just because 2 people say that the product is "awesome" are necessarily similar.
3. Recommended method is an almost copy paste of problem statement and objective.
4. Architechture of the system is basically, point 3 as a flow chart.
