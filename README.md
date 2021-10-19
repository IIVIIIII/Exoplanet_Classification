# Exoplanet_Classification

This project involves training two separate machine learning models to classify potential exoplanets discovered by the Kepler Space Observatory as 'CONFIRMED', 'FALSE POSITIVE', or 'CANDIDATE'. All data originates from the NASA Exoplanet Archive.

One model uses sklearn's random forest classifier and the other uses sklearn's support vector classifier (SVC). Both models undergo hyperparameter tuning using sklearn's GridSearchCV.

#### The tuned random forest classifier model had a score of 0.716
![alt text](https://github.com/IIVIIIII/Exoplanet_Classification/blob/main/photos/randomforest_results.png?raw=true)

#### The tuned SVC model had a score of 0.749
![alt text](https://github.com/IIVIIIII/Exoplanet_Classification/blob/main/photos/svc_results.png?raw=true)




Tools Required:
- Python
- Pandas
- sklearn
- Joblib