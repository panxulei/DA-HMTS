## Model Introduce
```model introduce
The DA-HMTS model, a high-performance hybrid model for multivariate time series prediction based on dual attention mechanisms. First, the model designs a variable selection module that adaptively selects feature variables based on the information gain rate criterion. Second, the feature attention mechanism and the temporal attention mechanism are applied to the time convolutional neural network and the long short-term memory network layer, respectively. Finally, a quantile loss function is designed to achieve interval prediction. Additionally, the proposed model is compared and analyzed with other methods using different datasets from various fields, and the following conclusions are drawn: 

```
* The First
```The First
The DA-HMTS model uses feature attention mechanism and temporal attention mechanism to optimize the output features of the TCN model and the output of the LSTM model, which improves the prediction accuracy of key moments. 
```
* The Second
```The Second
Compared with other methods, the DA-HMTS model has the best overall performance, reducing the MSE by at least 55.24% and the MAE by at least 37.60% under the same conditions. 
```
* The Third
```The Third
The ablation experiment results show that removing different modules will lead to different degrees of loss increase, indicating that the model structure optimization is reasonable. 
```
* The Fourth
```The Fourth
The DA-HMTS model has good interpretability and can accurately identify significant events in critical time periods (such as identifying landslides during the rainy season). 
```
* The Fifth
```The Fifth
The DA-HMTS model has high computational efficiency and achieves good results in terms of computational efficiency, prediction accuracy, and interpretability compared to other deep learning models with the same input sample size. Although the XGBoost and ARIMAX methods have faster training efficiency than the DA-HMTS model, their predictive accuracy and interpretability are relatively poor.
```
`Only the model architecture is provided here.`