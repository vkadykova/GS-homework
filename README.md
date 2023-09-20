# Greenscreens.ai homework
Task 1.
You should predict rate per mile using your model, features etc.

Example code returns average rate as prediction, it gives 34.85% accuracy.

Rate quality prediction is measured by MAPE (mean absolute percentage error): <img src="https://raw.githubusercontent.com/GreenScreens-company/GS-homework/main/equaimage.png" align="center" border="0" alt="\sum_{i}^{} {\frac{1}{N} \bigg | {1 - \frac{Rate_{predicted}^{i}}{Rate_{real}^{i}}}\bigg | } * 100 \%" width="235" />

There are three files with data: train.csv, validation.csv (validation set infront of train in term of date) and test.csv (for your prediction)
We have divided all US territory into KMA (Key Market Regions). These regions grouped by similar market conditions that are inside each market. Try to enhance the current Rate Engine by pushing knowledge about origin and destination KMA into model. 
The dataset contains the following features: the number of miles of the route, the type of the transport (there are three main types of transport), used for transporting the cargo, the weight of the cargo, the date when the cargo was picked up, the KMA origin point and the KMA destination point.

Try to beat our prediction accuracy (MAPE), we are expecting less than 9%.

Please send estimate your validation MAPE, the predictions for the test.csv and don't forget to attach your code.


Task 2.

Think and propose your version of a asymmetric MAPE-Like Metric. This asymmetry should be adjustable through the introduction of an additional parameter, allowing for fine-tuning of the metric's sensitivity to overestimations and underestimations. Consider the advantages, disadvantages, and limitations of using such a metric.
