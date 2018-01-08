# Guess-Who-Game
Thesis

The files/experiments that are examined in the current GitHub profile are the following:

Preprocessing - Extracting the Description feature: This experimnet is using some simple regular expression to isolate the necessary components that are required for further experimentation. In specific, the physical description of each instance and the ImageID is extracted. The same process occured for the question feature although it is not presented since the process is almost the same with some small changes on the Regular Expression script.

Preprocessing 1: Description Feature: This experiment describes some preprocessing tha applied on the Description feature in order to bring it into a more readable form and easy to be processed.

Preprocessing 2: Question Feature. This experiment describes some preprocessing tha applied on the Question feature in order to bring it into a more readable form and easy to be processed.

Process 1 - LDA - The current experiment examines the process of LDA: This applied on the question feature with the aim to identify the topics which can be treated as features for a new database. The results are thoroughly examined in the thesis document.

Process 2 - Clustering with K-means:he current experiment examines the appliance of the K-means algorithm to the question feature. The aim is to identify the centroids and review which are best describing the questions as a whole. The aim is not only to identify the clusters but also to review whether those clusters can be labeled and represent features for the new database that the thesis aims to construct.

Process 3 - Coefficients Investigation with Logistic Regression: This experiment applied the logistic regression on the question feature. It examines the largest and the smallest coeefficients which are words that are positively or negatively corelated accordingly to a target feature.There is a throughout examination of the results in the thesis document. The experiment that the thesis examines, is using four different target features (hair, wear, skin and eyes) with the aim to identify their coefficients which can be treated potentially as values for those four features.
