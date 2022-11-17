# Neural_Network_Charity_Analysis
## Overview
### Purpose

The purpose of this analysis is to practice using deep-learning neural networks and optimizing them to assist a fictional charity organization in predicting where to make future investments. 


## Results
### Data Preprocessing
- The target variable in the model is the IS_SUCCESSUL column
- Application Type, Affiliation, Classification, Use Case, Organization Status, Income Amount, Special Considerations, and Ask Amount are the considered model features
- Columns EIN and NAME are removed columns, for they will not be used as features

### Compiling, Training, and Evauluating the Model

#### Original 
<img width="730" alt="Screen Shot 2022-11-17 at 12 35 21 AM" src="https://user-images.githubusercontent.com/106895220/202373893-caad1ab8-569f-48a4-b9cd-2f66bc632827.png">
<img width="1099" alt="Screen Shot 2022-11-17 at 12 38 46 AM" src="https://user-images.githubusercontent.com/106895220/202374458-07ddcd48-c9b6-445d-90be-a707aadcb1b3.png">


#### "Optimized"
<img width="742" alt="Screen Shot 2022-11-17 at 12 35 27 AM" src="https://user-images.githubusercontent.com/106895220/202373905-be703ad9-152d-413e-b344-1119e3d58a4c.png">
<img width="1096" alt="Screen Shot 2022-11-17 at 12 39 23 AM" src="https://user-images.githubusercontent.com/106895220/202374546-3bc50e63-bd0c-4455-a5ad-8eb197be9b0b.png">

I added an additional layer while maintaining the same number of neurons for the original two in my new model. This seemed to not make much of a difference in performance. More improvements need to made to achieve 75% optimization. 

## Summary

While tweaking the layer count and neuron count may help with opztimization, dropping one of our features from our set may also help. Another activation or optimization function may also help. Using a random forest classifier may also yield better results compared to the current model.
