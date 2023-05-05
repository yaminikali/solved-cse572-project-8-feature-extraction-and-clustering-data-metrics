Download Link: https://assignmentchef.com/product/solved-cse572-project-8-feature-extraction-and-clustering-data-metrics
<br>
Given:   Meal Data of 2 subjects

Amount of carbohydrates in each meal

Todo:

<ol>

 <li>Extract features from Meal data</li>

 <li>Cluster Meal data based on the amount of carbohydrates in each meal</li>

</ol>

Extracting Ground Truth:

Derive the max and min value of meal intake amount from the Y column of the Insulin data. Discretize the meal amount in bins of size 20. Consider each row in the meal data matrix that you generated in Assignment 2. According to their meal amount label put them in the respective bins.

In total you should have   bins.

Performing clustering:

Now ignore the mealAmountData. Without using the meal amount data use the features in your assignment 2 to cluster the mealDataX.csv into  clusters. Use DBSCAN or KMeans. Try these two.

Report your accuracy of clustering based on SSE, entropy and purity metrics.