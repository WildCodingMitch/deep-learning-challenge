# Module 21 Report
### Mitchell Fairgrieve

### Overview of the Analysis

* The purpose of this analysis was to train a neural network model to predict application types for charity data.
* The model is predicting based on the other columns. For example, by using the CLASSIFICATION, AFFILIATION, & INCOME_AMT to predict the application type.
* To predict the data it was pivitol to take a deeper look. Using functions like nunique() and value.counts() we were able to access the data and determine which columns would be most useful in the analysis.
* The model used in this case was a keras Sequential model. This model is very common and is familiar to many neural network users. This, along with the ease of use, is why I chose to implement this model type.

### Results

* Machine Learning Model 1:
    * The model ended up having a total of 4,341 params. This seemed like a good amount to get the desired accuracy of 75%, however the actual numbers were not as good.
    * Loss: 0.5574989318847656, Accuracy: 0.7244315147399902


### Summary

* After running this analysis I feel a more in depth model may have been better for this data.
* It is also important to note that 100 epochs was too many and resulted in overfitting of the model. We can see this from epochs 57-59 where the accuracy fluctuated between 74.24% to 73.67% and then finally to 73.69%. These fluctuations occurred repeatidly throughout the epochs.
* I would not reccomend using this model again, and if I were to do it again I would switch the model to have more processing layers, along with more parameters to better train the model.
