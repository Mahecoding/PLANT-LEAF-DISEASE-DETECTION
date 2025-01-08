## PLANT LEAF DISEASE DETECTION AND RECOMMENDATION OF CROPS AND FERTILIZERS USING DEEP NEURAL NETWORK 
[click here to view ppt](https://docs.google.com/presentation/d/1hyhX96FMG9jVcbzHTkac3pvSfe--ksTA/edit?usp=sharing&ouid=109400921624374952423&rtpof=true&sd=true)



**output**

![image](https://github.com/user-attachments/assets/72688f3c-093c-430a-95c5-f044c57c1103)
![image](https://github.com/user-attachments/assets/c64bb2e1-68f9-4b6f-8525-96f18f73f1d9)
![image](https://github.com/user-attachments/assets/aa84bcfe-e2d7-46ef-b4b5-cf4f53e20387)
![image](https://github.com/user-attachments/assets/7f658aad-b610-43a1-bbb8-dcbb0f915446)
![image](https://github.com/user-attachments/assets/a80dadae-c750-4ce4-97c6-79cec4ccf2f2)
![image](https://github.com/user-attachments/assets/56393e0f-19df-4220-a077-d0ffb4d90396)
![image](https://github.com/user-attachments/assets/da41905f-ec97-4549-8747-d9f7aafab033)
![image](https://github.com/user-attachments/assets/f4a8be15-685a-4763-ae46-f91870e67903)


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
![image](https://github.com/user-attachments/assets/27f7f2c5-d76b-4977-b618-f8f0fe8c65e5)


FERTILIZER RECOMMENDATION:
Prepared a custom dataset by combining the crop and fertilizer dataset for 21classes in the fertilizer recommendation model.
It gives organic manure and easy ways to overcome the widespread of disease by giving input to the  N,P,K pHvalues, soil.
![image](https://github.com/user-attachments/assets/f4940642-3a15-4fe9-a904-1d046b0e5cc2)

PLANT DISEASE PREDICTION:
CNN was educated for one lakh datasets obtained from Kaggle website and operating with the Resnet9 algorithm This layer performances overall best compared to other models  and getting 99.1% of accuracy in training. 
In ResNet unlike in traditional neural networks, each layer feeds into the next layer, we use a network with residual block, to avoid over-fitting. This also helps in preventing vanishing gradient problem and allow us to train deep neural networks.
Between the subsequent Con2D layers, batch normalization followed by ReLU (Rectified Linear Unit) activation layer was added. At the end of each stage, the stage is outcome is added with the original images and passed through  ReLU activation layer before starting the next layer.
![image](https://github.com/user-attachments/assets/1089a1f7-9ceb-4d70-bc54-3656fe7d474e)

**RESULT**

![image](https://github.com/user-attachments/assets/88950708-e860-4f6a-aaf3-e862d9fba8f1)

![image](https://github.com/user-attachments/assets/dde3e85c-119d-433b-9ed2-3e78de65b6d2)

HYBRID  CROP  RECOMMENDATION:
For the hybrid crop recommendation system the DECISION TREE achieved the accuracy of 0.90, LOGISTIC REGRESSION achieved the accuracy of 0.95227, RANDOM FOREST achieved the accuracy of 0.9909090, XGBOOST achieved the accuracy of 0.9931818, SVM achieved the accuracy of 0.1068181,NAIVE BAYES achieved the accuracy of 0.990909.
When compared with others RANDOM FOREST and XGBOOST achieved the highest accuracy 0f 99 and SVM has the least accuracy in the training phase.
PLANT DISEASE DETECTION:
ResNet has been shown to achieve state-of-the-art results in various image classification tasks, including plant disease detection. By using ResNet, it achieved higher accuracy in detecting and diagnosing plant diseases compared to traditional computer vision methods of 99.2%.


![image](https://github.com/user-attachments/assets/8e37e487-ac95-4272-9c56-561fd8db2b78)


**CONCLUSION**
Plant disease prediction and hybrid crop recommendation will be more helpful for the persons who don’t have knowledge about the agriculture.The model is basically tested on some types of plant species with some types of plant diseases. The overall system results show that ResNet9 model works better as compared to the other models and provide better accuracy in detecting the diseases .As an extension to the project the number of classes of plants and its diseases will be increased.

The core strategy of the project is to predict the crop based on the soil nutrient content and the location where the crop is growing. . This system will help farmers to choose the right crop for their land and to give the suitable amount of fertilizer to produce the maximum yield.

**FUTURE WORK**

In future work, we will address the problems in real-time data collection and develop a multi-object deep learning model that can even detect plant diseases from a bunch of leaves rather than a single leaf. Further  we can include automatic plant disease sensing detector and automatic fertilizer sprayer. The proposed scheme could be expanded to provide additional facilities such as nearby government markets, pesticide price lists, and a nearby open market, among others.

Furthermore, we are working towards implementing a mobile application with the trained model from this work and also looking to develop live weather prediction that will also help the users to predict the crop water needs.
