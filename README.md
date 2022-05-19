# Device_Failure
The purpose of this model is to predict whether a device, which in this case are delivery trucks, require maintenance based on the provided data containing maintenance records and 
failure rates for each device. The challenge of this project is the ambiguity in the features in the dataset. Each feature is labeled as "attribute1" to "attribute9". Without a
descriptive feature name, it is difficult to correlate one feature to another or to identify trends; thererfore, requiring data extraction and manipulation to understand the 
dataset.

This project required me dive into my own personal experience and domain knowledge in product manufacture to extract additional information from the given serial numbers to 
identify the device model. After data cleansing, extraction and manipulation, a classification-based model was built to predict whether a device will fail or not. The model was 
tested using the following classification algorithm: Gaussian, Bernoulli, K-Nearest Neighbor, Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. Random Forest demonstrated in the best results.

Despite the decent outcome, the data set test is a very small sample size with just over 1100 samples. 



