# ANN-Research---Breast-Cancer
Using Artificial Neural Network to Compare the Importance of Different Features of Breast Cell Nuclei in Breast Cancer Diagnosis

Breast cancer is a prevalent cancer in the globe, killing hundreds of thousands of people annually. The incorporation of Artificial Intelligence (AI) in early cancer detection shows great potential in recent years. 
In the research, an Artificial Neural Network (ANN) model is trained on Breast Cancer Wisconsin (Diagnostic) Data Set that contains information about various characteristics of the cell nuclei present in a digitized image of a fine needle aspirate (FNA) of a breast mass. 
By adjusting the number of hidden layers and calculating the corresponding loss functions, the study aims to achieve high-accuracy predictions based on the 30 features provided by the dataset. A model with 3 hidden layers is developed, with 22 nodes in each layer. 
With 100 epochs, the model can achieve a 97.48% accuracy, 97.6% precision and 97.6% recall on the validation dataset. The impact of individual characteristics of the cell nuclei on the accuracy of diagnosis is then analyzed by using the same model but only including data that are relevant to the studied characteristics as features. 
The prediction accuracy is the highest when concave points are the only feature (94.4%) and lowest when only the fractal dimension or texture is considered (72.0%). Therefore, the research suggests that concave points have the strongest correlation with breast cancer diagnosis, whereas fractal dimension and texture play the least significant role
