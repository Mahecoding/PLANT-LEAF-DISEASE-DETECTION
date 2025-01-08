## PLANT LEAF DISEASE DETECTION AND RECOMMENDATION OF CROPS AND FERTILIZERS USING DEEP NEURAL NETWORK 
[click here to view ppt](https://docs.google.com/presentation/d/1hyhX96FMG9jVcbzHTkac3pvSfe--ksTA/edit?usp=sharing&ouid=109400921624374952423&rtpof=true&sd=true)


**OUTPUT**
![image](https://github.com/user-attachments/assets/3fa12489-6508-4bc3-9917-1a26a2bd4aed)
![image](https://github.com/user-attachments/assets/ab79e535-ab20-40e8-a75a-c29c41f40321)
![image](https://github.com/user-attachments/assets/f5e2ecd3-9ed0-4709-805e-f0c2eb1c536b)
![image](https://github.com/user-attachments/assets/90156425-5c80-4a60-a9ed-67ade34a3384)
![image](https://github.com/user-attachments/assets/39512a58-57bc-47e1-b582-71637fa56cf5)


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
![image](https://github.com/user-attachments/assets/cfcc034b-0a4d-4e70-b151-7e7d954b2c5c)

FERTILIZER RECOMMENDATION:
Prepared a custom dataset by combining the crop and fertilizer dataset for 21classes in the fertilizer recommendation model.
It gives organic manure and easy ways to overcome the widespread of disease by giving input to the  N,P,K pHvalues, soil.
![image](https://github.com/user-attachments/assets/3985977c-118a-45a2-98a1-c6e8461c4d40)

PLANT DISEASE PREDICTION:
CNN was educated for one lakh datasets obtained from Kaggle website and operating with the Resnet9 algorithm This layer performances overall best compared to other models  and getting 99.1% of accuracy in training. 
In ResNet unlike in traditional neural networks, each layer feeds into the next layer, we use a network with residual block, to avoid over-fitting. This also helps in preventing vanishing gradient problem and allow us to train deep neural networks.
Between the subsequent Con2D layers, batch normalization followed by ReLU (Rectified Linear Unit) activation layer was added. At the end of each stage, the stage is outcome is added with the original images and passed through  ReLU activation layer before starting the next layer.

![image](https://github.com/user-attachments/assets/1cc62814-6bd3-4685-8503-6dcbff9611cd)


**RESULT**
HYBRID  CROP  RECOMMENDATION:
For the hybrid crop recommendation system the DECISION TREE achieved the accuracy of 0.90, LOGISTIC REGRESSION achieved the accuracy of 0.95227, RANDOM FOREST achieved the accuracy of 0.9909090, XGBOOST achieved the accuracy of 0.9931818, SVM achieved the accuracy of 0.1068181,NAIVE BAYES achieved the accuracy of 0.990909.
When compared with others RANDOM FOREST and XGBOOST achieved the highest accuracy 0f 99 and SVM has the least accuracy in the training phase.
PLANT DISEASE DETECTION:
ResNet has been shown to achieve state-of-the-art results in various image classification tasks, including plant disease detection. By using ResNet, it achieved higher accuracy in detecting and diagnosing plant diseases compared to traditional computer vision methods of 99.2%.

![image](https://github.com/user-attachments/assets/2c23e08d-7c73-40b6-a49c-b198bfe4a596)
![image](https://github.com/user-attachments/assets/4fabfa91-70a4-4273-9fe2-c193da7446e3)








**CONCLUSION**
Plant disease prediction and hybrid crop recommendation will be more helpful for the persons who don’t have knowledge about the agriculture.The model is basically tested on some types of plant species with some types of plant diseases. The overall system results show that ResNet9 model works better as compared to the other models and provide better accuracy in detecting the diseases .As an extension to the project the number of classes of plants and its diseases will be increased.

The core strategy of the project is to predict the crop based on the soil nutrient content and the location where the crop is growing. . This system will help farmers to choose the right crop for their land and to give the suitable amount of fertilizer to produce the maximum yield.

**FUTURE WORK**

In future work, we will address the problems in real-time data collection and develop a multi-object deep learning model that can even detect plant diseases from a bunch of leaves rather than a single leaf. Further  we can include automatic plant disease sensing detector and automatic fertilizer sprayer. The proposed scheme could be expanded to provide additional facilities such as nearby government markets, pesticide price lists, and a nearby open market, among others.

Furthermore, we are working towards implementing a mobile application with the trained model from this work and also looking to develop live weather prediction that will also help the users to predict the crop water needs.
