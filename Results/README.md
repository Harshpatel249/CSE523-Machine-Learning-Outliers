# CSE 523 Machine Learning Outliers

5. Results: Contains the screenshots of the results for both the implementations.  
--> Result_CosineSimilarity.png (Result of Cosine Similarity with TF-IDF vectorizer)  
    Here the recommendations for the movie "The Dark Knight" are displayed.  
    The recommended movies are very similar based on the genre, cast, directors and keywords (i.e content of the movie).     
--> Gauss.png (Image showing the initial and final gaussian after Expectation Maximization)  
    Here, we can see the initial gaussians and the gaussians after EM algorithm.  
--> RMSE.png (Image showing the RMSE values for 1 gaussian to 30 gaussians)  
    Here, we can see the RMSE values for 30 different cases, i.e 1 gaussian to 30 different gaussians fitted to the given data.  
--> RMSEg.png (Image showing the RMSE vs number of Gaussians)  
    Here, we can see that the RMSE decreases with the increase in number of gaussians but the decrease saturates quickly due to small data.  
--> GMMloglikelihood.png (Image showing the log likehood with increasing iterations)
    Here, we can see that the log likelihood saturates between 40-50 iterations and hence 50 iterations are enough.  