# Rotten-v-s-Fresh-Fruit-Detection
## To Classify fruits based on freshness factor

**Author** : SHAILESH DHAMA

Study and classify the 9 categories of most common Northern European mushrooms genuses.
                
### Dataset :

    It contains monthly rainfall detail of 36 meteorological sub-divisions of India.

#### Content of Dataset:

    1.Time Period: 1901 - 2015

    2.Granularity: Monthly

    3.Location: 36 meteorological sub-divisions in India

    4.Rainfall unit: mm

## Approach:

### Data processing & Exploratory Data Analysis:

    1.Import Libraries
    2.Loading and processing data
    3.Predictions
        3.1 Linear Model
        3.2 Support Vector Machine
        3.3 Artificial Neural Networks
        
#### 3.1 Linear Model      
Linear model is used in different ways according to the context. The most common occurrence is in connection with regression models and the term is often taken as synonymous with linear regression model. However, the term is also used in time series analysis with a different meaning. In each case, the designation "linear" is used to identify a subclass of models for which substantial reduction in the complexity of the related statistical theory is possible.

#### 3.2 Support Vector Machine
Support Vector Machine (SVM) is a supervised machine learning algorithm which can be used for both classification and regression challenges. We plot each data item as a point in n-dimensional space (where n is number of features) with the value of each feature being the value of a particular coordinate. Then, we perform classification by finding the hyper-plane that differentiates the two classes very well. A Support Vector Machine models the situation by creating a feature space, which is a finite-dimensional vector space, each dimension of which represents a "feature" of a particular object. The goal of the SVM is to train a model that assigns new unseen objects into a particular category. It achieves this by creating a linear partition of the feature space into two categories. Based on the features in the new unseen objects, it places an object "above" or "below" the separation plane, leading to a categorization. It is non-probabilistic, because the features in the new objects fully determine its location in feature space and there is no stochastic element involved. A subset of training data lies on Biased and Unbiased Hyper planes

#### 3.3 Artificial Neural Networks
A neural network is a series of algorithms that endeavors to recognize underlying relationships in a set of data through a process that mimics the way the human brain operates. In this sense, neural networks refer to systems of neurons, either organic or artificial in nature. Neural networks can adapt to changing input; so the network generates the best possible result without needing to redesign the output criteria.
           
## RESULTS :

#### Percent missing data by feature
![Percent missing data by feature](./RAIN_1.png)

#### Rainfall per month
![Rainfall per month](./RAIN_2.png)

#### Annual Ranifall over 120 years
![Annual Ranifall over 120 years](./RAIN_3.png)


#### Monthly Ranifall over 120 years
![Monthly Ranifall over 120 years](./RAIN_4.png)
![Monthly Ranifall over 120 years](./RAIN_5.png)

#### Annual Rainfall of different states
![Annual Rainfall of different states](./RAIN_6.png)
![Annual Rainfall of different states](./RAIN_7.png)
![Annual Rainfall of different states](./RAIN_8.png)
![Annual Rainfall of different states](./RAIN_9.png)
![Annual Rainfall of different states](./RAIN_10.png)
![Annual Rainfall of different states](./RAIN_11.png)
![Annual Rainfall of different states](./RAIN_12.png)
![Annual Rainfall of different states](./RAIN_13.png)
![Annual Rainfall of different states](./RAIN_14.png)
![Annual Rainfall of different states](./RAIN_15.png)
![Annual Rainfall of different states](./RAIN_16.png)
![Annual Rainfall of different states](./RAIN_17.png)
![Annual Rainfall of different states](./RAIN_18.png)
![Annual Rainfall of different states](./RAIN_19.png)
![Annual Rainfall of different states](./RAIN_20.png)
![Annual Rainfall of different states](./RAIN_21.png)
![Annual Rainfall of different states](./RAIN_22.png)
![Annual Rainfall of different states](./RAIN_23.png)
![Annual Rainfall of different states](./RAIN_24.png)
![Annual Rainfall of different states](./RAIN_25.png)
![Annual Rainfall of different states](./RAIN_26.png)
![Annual Rainfall of different states](./RAIN_27.png)
![Annual Rainfall of different states](./RAIN_28.png)
![Annual Rainfall of different states](./RAIN_29.png)
![Annual Rainfall of different states](./RAIN_30.png)
![Annual Rainfall of different states](./RAIN_31.png)
![Annual Rainfall of different states](./RAIN_32.png)
![Annual Rainfall of different states](./RAIN_33.png)
![Annual Rainfall of different states](./RAIN_34.png)
![Annual Rainfall of different states](./RAIN_35.png)
![Annual Rainfall of different states](./RAIN_36.png)
![Annual Rainfall of different states](./RAIN_37.png)
![Annual Rainfall of different states](./RAIN_38.png)
![Annual Rainfall of different states](./RAIN_39.png)
![Annual Rainfall of different states](./RAIN_40.png)
![Annual Rainfall of different states](./RAIN_41.png)

#### Annual Rainfall in India from Year 1901 to 2015
![Annual Rainfall in India from Year 1901 to 2015](./RAIN_42.png)

#### Seasonal Rainfall from Year 1901 to 2015
![Seasonal Rainfall from Year 1901 to 2015](./RAIN_43.png)

#### Rainfall in Subdivisions of India
![Rainfall in Subdivisions of India](./RAIN_44.png)

#### Annual Rainfall in Subdivisions of India
![Annual Rainfall in Subdivisions of India](./RAIN_46.png)

#### Subdivision wise Average Annual Rainfall
![Subdivision wise Average Annual Rainfall](./RAIN_47.png)

#### Monthly Rainfall in India
![Monthly Rainfall in India](./RAIN_48.png)

#### Kerala Annual Rainfall from Year 1901 to 2015
![Kerala Annual Rainfall from Year 1901 to 2015](./RAIN_50.png)

#### Rainfall in Districts of Kerala
![Rainfall in Districts of Kerala](./RAIN_51.png)

#### Districts with Minumum Rainfall in India
![Districts with Minumum Rainfall in India](./RAIN_52.png)

#### Districts with Maximum Rainfall in India
![Districts with Maximum Rainfall in India](./RAIN_53.png)

#### Places with Heavy and Scanty Rainfall in India
![Places with Heavy and Scanty Rainfall in India](./RAIN_54.png)

#### Correlation Matric
![Correlation Matric](./RAIN_94.png)

#### Linear Model predictions
![Linear Model predictions](./RAIN_95.png)
![Linear Model predictions](./RAIN_97.png)

#### SVM predictions
![SVM predictions](./RAIN_100.png)
![SVM predictions](./RAIN_101.png)

#### Neural Networks predictions
![Neural Networks predictions](./RAIN_104.png)
![Neural Networks predictions](./RAIN_105.png)
![Neural Networks predictions](./RAIN_106.png)

#### Final Inference
![Final Inference](./RAIN_107.png)

### For further information:

Please review the narrative of our analysis in [our jupyter notebook](./Rainfall%20Predictions%20in%20India.ipynb)

For any additional questions, please contact **shaileshettyd@gmail.com)

##### Repository Structure:

```
├── README.md                                                                                                   <- The top-level README for reviewers
├── Rainfall%20Predictions%20in%20India.ipynb                                                                   <- narrative documentation of analysis
├── https://www.kaggle.com/maysee/mushrooms-classification-common-genuss-images                                 <- Dataset
└── images                                                                                                      <- generated from code
```
## Citing :

```
@misc{Shailesh:2020,
  Author = {Shailesh Dhama},
  Title = {Rainfall-Predictions-in-India},
  Year = {2020},
  Publisher = {GitHub},
  Journal = {GitHub repository},
  Howpublished = {\url{https://github.com/ShaileshDhama/Rainfall-Predictions-in-India}}
}
```
