# CONTENT-BASED RECOMMENDER SYSTEM APPROACH WITH MOVIES SUMMARIES AND USING A DOC2VEC MODEL

Recommender systems are everywhere. Maybe you don’t kwon but when you are using Netflix platform, Amazon, Youtube or, maybe, Skyscanner for booking a flight you are interacting with a recommender system.

### ADVANTAGES OF USING A RECOMMENDER SYSTEM

We can study it from two perspectives: a business approach and a human behavior approach.

#### Business 

Recommender system let companies put the customer in the center of the business by making easier to access and surf huge catalogs of data, products and services.

Also, a really interesting point is that these platforms are transforming business as we know nowadays. And interesting sector where you can see these changes is the advertising sector. Companies like Google or Facebook use these systems for knowing the best moment, best people and best add to show in order to maximize and optimize a campaign budget. 

These changes are supposing huge strategic movements in traditional companies (and also in the digital ones)

#### Humans

We are social animals that really like make recommendations in two different ways: we have something to show or, on the other hand, we know the person that we want to recommend something. 

Being fair, for a human is quite easy to understand what is similar (or not) or what are the interests, passions or pleasures of other people. But, how can we explain this “similarity” concept to a machine?

In this context is moment to introduce the feature concept. For example, we can describe a house by the number of rooms, square meters… so, all of them are characteristics that describe them. 

![alt text](https://github.com/qgvidal/contentRecommenderSystem/blob/main/images/rs1.png) 

And being numeric characteristics, we are able to superimpose in a space (like a graph) where each direction is a feature. This space is called characteristics space and is really useful in the data science world.

 ![alt text](https://github.com/qgvidal/contentRecommenderSystem/blob/main/images/rs2.png) 
 
Having all the houses over this space, we can measure distances between them and recommend those who are closer. 

![alt text](https://github.com/qgvidal/contentRecommenderSystem/blob/main/images/rs3.png) 

But there is a problem. What if, instead of having numeric characteristics we have text, images, or sounds?

Here is where deep learning takes its place. Using deep learning models (like doc2vec or CNN), we are able to transform this input (and non-numeric data) to numeric vectors that we call embeddings and… put them over our characteristics space and measure distances!

 ![alt text](https://github.com/qgvidal/contentRecommenderSystem/blob/main/images/rs4.png)

These are recommender systems called content-based because we are just considering products and services data (and context) characteristics. And that is what we will develop in this tutorial.

