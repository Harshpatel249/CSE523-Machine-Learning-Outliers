# CSE 523 Machine Learning Outliers

## Description
Movie recommendation system implemented using two different approaches:  
Content based: Cosine Similarity with TF-IDF vectorizer  
Collaborative filtering: Gaussian Mixture Model with Expectation Maximization  
  
## Folders
1. Code: Contains jupyter notebooks with the implementation of the above approaches        
--> ContentBasedRefined.ipynb (Cosine Similarity with TF-IDF implementation using scikit learn)  
--> GMM_UsingSciKit.ipynb (Gaussian Mixture Model with Expectation Maximization using scikit learn)  
--> GMM_noscikit.ipynb (Gaussian Mixture Model with Expectation Maximization without using scikit learn)  
2. Dataset: Contains dataset for both the implementations  
--> u.data, u.user (Datasets for GMM with EM)  
--> ContentBased.txt (Link to dataset for Cosine Similarity with TF-IDF)  
3. Presentations: Contains the presentation files for both Midsem and Endsem presentations.  
--> Outliers_Mid_Sem_Project_Presentation.pptx (Midsem Presentation)  
--> Outliers_End_Sem_Project_Presentation.pptx (Endsem Presentation)  
4. Reports: Contains both the Midsem and Endsem reports  
--> Outliers_Mid_Sem_Project_Report.pdf (Midsem report)  
--> Outliers_End_Sem_Project_Report.pdf (Endsem report)  
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