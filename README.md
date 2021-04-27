# Quality assessment of drill holes with supervised machine learning methods based on vibration data

Quality assessment is a crucial step after CNC machining of parts which are mechanically interconnected. 
The objective of this work is to classify the drill hole quality of gearbox components using vibration data of the production process itself. 
We applied the five most frequently used supervised machine learning methods from thematically related studies: Support Vector Machine (SVM), 
Convolutional Neural Network (CNN), Artificial Neural Network (ANN), Random Forest (RF) and K-Nearest Neighbors (KNN). In an experimental setup, 
we investigate the performance of the models, taking into account balanced and unbalanced class distributions, pre- and fine drilling of each drilling 
process and using quantitatively preprocessed data. From the results we conclude that within the invested resources none of the classifiers could 
replace a separate quality control. The results of this investigation further suggest, that the performance of RF, ANN and KNN decreases under 
real class distribution and increases with the help of quantitatively preprocessed data. We explain the model’s poor prediction accuracy by possibly 
insufficient model selection. Furthermore, the limited data and modelling conditions due to low computing power in the test environment may have reduced 
the model’s performance. We also consider it possible, that the quality of drill holes can not be derived from the sensor data at all.
