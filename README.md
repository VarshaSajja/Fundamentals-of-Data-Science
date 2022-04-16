# Fundamentals-of-Data-Science
Data Mining pipeline steps with eSports data

**Research Area :**

This project focusses on the steps of data mining pipeline with eSports dataset.

**Results :**

•	The raw data consists of 2 datasets: highest_earning_players, highest_earning_teams having common variables as Genre and Game. Thus, both datasets have been merged to find which Genre has most players and highest earnings. 

•	Analysis has been initially performed on merged dataset: highest_earnings (92800 rows, 12 variables) which has been later transformed as per required analysis. 

•	The dataset is cleaned and further no actions have been performed towards cleaning it. Instead data binning has been done due to significant analysis to be performed on Genre. Also, data type for few significant variables (Game, Genre) have been transformed into factors. Normalization process is applied on the data and dummies are created to check for PCA. 

•	Principal Component Analysis resulted in 100% of variance around the data with 1 component itself. Scree plot also suggested the same. 

•	Kmeans clustering is used for this data and optimal clusters were reported as 7 after analysis. 

•	During different classifications, kNN worked best with the data where partitioning of data is done beforehand. Accuracy was reported to be 100% for k=9. 

•	During different classifications, decision tree gave the similar accuracy but its performance is bad as we predict from confusion matrix giving accuracy as only 50%. 

•	Evaluation of the model resulted in transforming the data into 2 classes by binning method where ONLINE class consists of Multiplayer Online Battle Arena and Battle Royale, OFFLINE class consists of First-Person Shooter, Collectible Card game and Strategy. The results are interesting and are similar to the initial analysis as the highest earnings, most played were from Online class.  

**Conclusion :**

•	The conclusion from the analysis performed is that the highest played and earned genre is Multiplayer Online Battle Arena where the results also show same.

•	Preprocessing methods give exact results which can be later used for clustering/ classification depending upon what we need from data and what data gives us.
