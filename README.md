## Maths and Data Modelling, Engineering Mathematics, University of Bristol
# Quartix Speeding Incident Accuracy Project
![](https://github.com/DozeyBot/False-Negative-speedAlertIds/blob/main/Birds%20Eye%20View%20Screenshots%20and%20Graphs/GeneratedDataRegionsMapNearLimeLaneRoundabout.png)

Quartix's black box software has faults at misallocate speeding incidents where roads lie close together, mostly through poor GPS hardware. We (Tom Finbow, Charles Marsh, Mu'izz Asif and myself) explored the use of PCA analysis and a Naive Bayes classifier on features drawn from the data to assess if speeding incidents could be more accurately assessed for these high density road situations. We found the use of a Regions feature (where sections betwen and on each road) was beneficial for the accuracy of our classifier. The ![final report](report_analysing_confidence_of_gps_locations .pdf) can be found in the repository.

![](https://github.com/DozeyBot/False-Negative-speedAlertIds/blob/main/Birds%20Eye%20View%20Screenshots%20and%20Graphs/2DGraphsTrainedOnGenDataTestedOnManualData.png)

It should be noted this repository has been posted to show what was achieved through this project - this code is not collaborative or executable as it does not contain required sensitive information (Quartix speeding data) to run. No installation instructions therefore will be supplied

Python packages used:
  - Folium and OpenStreet maps
  - sklearn
  - Pandas
  - standard python libraries (NumPy, matplotlib, etc.)

Finally attached is the [subset of all speeding fines](BadDataIDs) given that include what we have allocated as incorrectly flagged incidents. These IDs should not incur a fine as they are very likely false negatives
![](https://github.com/DozeyBot/False-Negative-speedAlertIds/blob/main/Birds%20Eye%20View%20Screenshots%20and%20Graphs/FinalBadPoints.png)
