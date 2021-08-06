# Searching-For-Exoplanets-in-Deep-space-With-Ai



* This Project was On the Kepler's Telescope Data. The Data was Numerical , 3k dimensional and Extremely High imbalanced with ratio of 99.7% negative_points & 0.3% Positive Points. And the Task was to classify if there is a exoplanet in orbit of that star or not after giving Intensity Values of Light of That Star.
* After EDA & Preprocessing(outlier removing and  Scalling) I Used T-sne to reduce Dimensionality and Visualization of Data. Then I explored various Machine Learning Algorithms Like knn,Liner-Models,Decision Tree, RF on both Imbalanced Train Data And Balanced_Train_Data That i Obtained After Oversampling to Handle Imbalance Problem of Dataset.
* My Best Model Was of Logistic-Regression which gives me Recall-Score of 80% and 89% of AUC on Test Data.
* Created Whole Data Science Pipeline in just 1 Function "is_there_any_exoplanet_in_orbit_of_That_star_or_not". This Function can predicted the Related Class About the Raw_Data-Point We give after Performing whole preprocessing , loading , prediction Internally. 
* I have Written a Very  detailed Medium blog About the project. Where i talked on questions like What is the problem , How We can Solve it Using Ai , How I choose my Main Performance Metric, How I solved Using Ml. Etc.. Please Go through it once to know some points : 
* https://utkarshjhansi11.medium.com/lets-find-planets-beyond-our-solar-system-milky-way-galaxy-with-the-help-of-905dcfc95d3d
*  Model is Deployed on Heroku. please visit the link bellow to see my model in production :
*  https://exoplanet-finder.herokuapp.com/

