## charter2：LITERATURE REVIEW
### 1. Introduction
Collaborative filtering is a method that uses your past choices to predict what you might want in the future. There are two main approaches to this: item-based filtering looks at what other items you have liked, while user-based filtering looks at what other people who have similar tastes have liked.
In recent years, with the rapid development of e-commerce, the system's personalized recommendation demand for users is also increasing. These requirements can not only improve user satisfaction, but also achieve rapid business growth of the company. However, CF faces several challenges, including sparse data, the integration of contextual factors, and the cold start problem.
This review delves into the existing research landscape, identifying its limitations and pinpointing areas ripe for further investigation. By addressing these challenges, we can refine CF techniques and deliver even more effective recommendation systems.

### 2.1 Considering User Contextual Information
Recommendation systems that can adapt to different situations (like where you are or how you're feeling) are becoming more and more important to give better suggestions.
The old way of recommending things to people isn't always so effective because of their tastes to change. The researchers did this by considering factors such as location and time. Karatzoglou et al. (2010) further enhanced this approach by using matrix factorization techniques to significantly improve movie preference prediction.

People's online shopping habits are influenced by where they live and what time of year they are. Researchers have shown that by using this information, we can give better recommendations that people might like to buy. However, collecting and using this data can be tricky and raises privacy concerns, so more research is needed to address them.

### 2.2 Addressing the Cold-Start Problem
Let's say you're trying to recommend a movie to a new friend. If you don't know much about them tastes, it's hard to come up with something they'll like. It's similar to Recommender system. To solve this problem, we can combine different approaches to do better Suggestion.
When there's a new product that comes along, we don't know if people will like it, and that's called the "cold start problem." To solve this problem, researchers have come up with some clever ideas. For example, in 2002, Schein and his team combined two different methods to better predict new products. They used what people generally like (based on content) and how similar people are to other products (collaboration). Similarly, Sedhain and his colleagues used a special computer model called an autoencoder to predict a user's preferences, even if we didn't have a lot of data. They do this by using other available information.
Another way to fix the cold start problem is to use information from external sources, such as social media and your browsing history. For example, He and his team showed in 2014 that using social network data could be a good way to provide good recommendations for newcomers to the service. However, the use of such data may raise some privacy concerns and may be difficult to combine with other types of data.
The authors hope this hybrid method and the import of knowledge from external sources contribute toward the creation of a better recommendation system. In fact, these systems have overcome problems inherent in traditional recommendation methods in their present form.

### 2.3 Handling Data Sparsity Issues
The big problem with CF models is that there is a lot of missing information about what people like. In order to solve this problem, people usually use a technique called matrix factorization. More recently, using deep learning, a new method was developed called Neural Collaborative Filtering, or NCF for short. NCF is better at finding the patterns in this missing information, which helps us make more accurate recommendations.
Consider having a big puzzle with a lot of missing pieces. Clustering is like putting together similar parts of a puzzle to make the whole picture easier to see. In such a way, it provides a deeper understanding of what people like and gives them better recommendations. For instance, Zhou and his team grouped people with similar tastes before using the traditional recommended method: Although it works, one should group people correctly, and that is not an easy thing to do.

### 3. Limitations
Some of the significant challenges for recommendation systems involve handling a huge number of users and items, a task that really demands considerable computational powers. Another problem arises when any model fits too well on training data but then does poorly on new data. Overfitting, in cases of noisy or incomplete data, generally arises.
Most recommender systems assume that the taste and preferences of people remain constant over time. However, this is not the case. While trying to use external sources of information, such as social media, to provide better recommendations, we have to balance between getting accurate results and preserving privacy. Another important issue is that some complex models, especially those involving deep learning, are often hardly interpretable, which can be problematic in domains where the cost of an error may be fatal.
If we want to create better, more reliable recommendation systems, we need to find solutions to these problems.

### 4. Research Gap
Although recommendation systems have improved a lot, there are still some problems. One major problem is that it can't catch up with the rapid changes in the people's shopping habits. Moreover, additional information assisting new users or products isn't always reliable.

There are some essential strategies that allow recommender systems to have more capability for adaptability towards new-coming data, along with effective handling of situations involving both new users or new items. We try to seek out the discovery of information generated by users and/or utilization of knowledge elicited by experts in such challenging situations:.

For very large data sets that contain a lot of missing information, we need computer systems that handle large amounts of data and compute fast. Deep learning is a powerful tool, but it's often difficult to understand why it makes certain predictions. In the future, we should focus on creating simpler models that can still be very accurate and efficient.
If we can make these models easier to understand, people will be more likely to trust them. This means we can use them in important areas such as healthcare or finance.
In a nutshell, Collaborative Filtering (CF) has really changed the way websites recommend things to us. But to make it better, we need to solve some of its problems and explore new ideas. By using more up-to-date information and reducing our reliance on external data, we can make CF more adaptable and reliable for online shopping. This will make online shopping more personalized and convenient for everyone.
If we do more research, we can make online shopping suggestions more accurate. This means that we can recommend products that people are genuinely interested in. This will keep customers happy and help businesses sell more.

### References
Karatzoglou, A., Amatriain, X., Baltrunas, L., & Oliver, N. (2010). Multiverse recommendation: N-dimensional tensor factorization for context-aware collaborative filtering. In Proceedings of the Fourth ACM Conference on Recommender Systems (pp. 79-86).
Koren, Y., Bell, R., & Volinsky, C. (2009). Matrix factorization techniques for recommender systems. Computer, 42(8), 30-37.
Schein, A. I., Popescul, A., Ungar, L. H., & Pennock, D. M. (2002). Methods and metrics for cold-start recommendations. In Proceedings of the 25th Annual International ACM SIGIR Conference on Research and Development in Information Retrieval (pp. 253-260).
Sedhain, S., Menon, A. K., Sanner, S., & Xie, L. (2015). Autorec: Autoencoders meet collaborative filtering. In Proceedings of the 24th International Conference on World Wide Web (pp. 111-112).
Zhou, X., Xu, M., & Liu, D. (2012). A cluster-based collaborative filtering recommendation algorithm. Journal of Software Engineering and Applications, 5(9), 686-692.
