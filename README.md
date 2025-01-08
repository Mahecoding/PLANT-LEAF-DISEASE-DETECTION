## PLANT LEAF DISEASE DETECTION AND RECOMMENDATION OF CROPS AND FERTILIZERS USING DEEP NEURAL NETWORK 
[click here to view ppt](https://docs.google.com/presentation/d/1hyhX96FMG9jVcbzHTkac3pvSfe--ksTA/edit?usp=sharing&ouid=109400921624374952423&rtpof=true&sd=true)
**output**
![image](https://github.com/user-attachments/assets/70701d77-b942-44fe-827e-69388e5b8858) ![image](https://github.com/user-attachments/assets/32cd3056-79ef-4565-acfc-2df52bf0dfc8)
![image](https://github.com/user-attachments/assets/006d7c56-6942-41dc-931f-25b5a4692c3d)
![image](https://github.com/user-attachments/assets/a6bf2222-5a5b-4ded-8f51-0dbc55e46252)


**Abstract**
Plants are the primary source of food for the whole population. This work included 3 models namely plant disease prediction, hybrid crop recommendation, fertilizer recommendation. 

The  objective of this proposed work is to detect plant diseases of the tomato leaf of 10 classes and also 13 different crops of 38 classes using machine learning algorithms and provide correct amount of fertilizers to the affected plant and recommend the crop based on soil in the city and state.
On prediction, disease prediction model gives the crop name and disease, cause of disease, how to prevent or cure the disease. 
  
**OBJECTIVE** 

The main objective of proposed system is to design such system to detect the plant leaf disease accurately and efficiently identity and classify disease or abnormalities in plant based on images or visual data and to provide remedy for the disease that is detected.

And also identify type of  the disease of  plants and suggesting the name of pesticides to be used and recommending the most effective and appropriate strategies for disease management.Providing advice on fertilizer which is based on soil and also giving suggestions regarding the recommendation of fertilizer to prevents farmers from applying an excessive amount of fertilizers and minimizing the related environmental damages and maximizing their productivity and profitability while considering sustainability and environmental factors.

The objective of crop recommendation is to provide farmers with actionable crops advice based on the soil test result from the user input.

**ALGORITHMS**

CROP RECOMMENDATION:
The proposed work is also  recommending crops of 22 classes by developing 6 Machine learning  model were tested and trained such as Decision tree, Gaussian Naive Bayes, SVM, Logistic Regression, Random Forest and Xgboost.

FERTILIZER RECOMMENDATION:
Prepared a custom dataset by combining the crop and fertilizer dataset for 21classes in the fertilizer recommendation model.
It gives organic manure and easy ways to overcome the widespread of disease by giving input to the  N,P,K pHvalues, soil.

PLANT DISEASE PREDICTION:
CNN was educated for one lakh datasets obtained from Kaggle website and operating with the Resnet9 algorithm This layer performances overall best compared to other models  and getting 99.1% of accuracy in training. 
In ResNet unlike in traditional neural networks, each layer feeds into the next layer, we use a network with residual block, to avoid over-fitting. This also helps in preventing vanishing gradient problem and allow us to train deep neural networks.
Between the subsequent Con2D layers, batch normalization followed by ReLU (Rectified Linear Unit) activation layer was added. At the end of each stage, the stage is outcome is added with the original images and passed through  ReLU activation layer before starting the next layer.
  







**CONCLUSION**
Plant disease prediction and hybrid crop recommendation will be more helpful for the persons who don’t have knowledge about the agriculture.The model is basically tested on some types of plant species with some types of plant diseases. The overall system results show that ResNet9 model works better as compared to the other models and provide better accuracy in detecting the diseases .As an extension to the project the number of classes of plants and its diseases will be increased.

The core strategy of the project is to predict the crop based on the soil nutrient content and the location where the crop is growing. . This system will help farmers to choose the right crop for their land and to give the suitable amount of fertilizer to produce the maximum yield.

**FUTURE WORK**

In future work, we will address the problems in real-time data collection and develop a multi-object deep learning model that can even detect plant diseases from a bunch of leaves rather than a single leaf. Further  we can include automatic plant disease sensing detector and automatic fertilizer sprayer. The proposed scheme could be expanded to provide additional facilities such as nearby government markets, pesticide price lists, and a nearby open market, among others.

Furthermore, we are working towards implementing a mobile application with the trained model from this work and also looking to develop live weather prediction that will also help the users to predict the crop water needs.
