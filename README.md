# health_data
This repo contains data analysis task (classification) using health data. 
 
### Classic machine learning algorithms
- Logistic Regression: lightweight and suitable for simple, linearly separable problems when interpretability is crucial
- SVM: best for complex problems with high-dimensional data
- Random Forest: complex problems specifically for robust and generalised predictions
- Ridge Classifier: good for problems with correlated features
  
### Peformance metrics
#### Brief overview of metrics used for model evaluation <br>
<b>Accuracy </b>: The ratio of correctly predicted observations to the total observations. Best used when the target classes are balanced. <br/>
Formula: Accuracy = Total Observations / True Positives+True Negatives  <br/>
 <br/>​
<b>Precision</b>: The ratio of correctly predicted positive observations to the total predicted positives. Used when the cost of false positives is high, for example, in fraud detection.  <br/>
Formula: Precision = True Positives+False Positives / True Positives  <br/>
​ <br/>
<b>Recall (Sensitivity)</b>: The ratio of correctly predicted positive observations to all actual positives. the emphasis is on capturing all positive cases, like disease detection  <br/>
Formula: Recall = True Positives+False Negatives / True Positives <br/>
​	 <br/>
<b>F1 Score</b>: The combined mean of precision and recall, providing a balance between the two. in scenarios with an uneven class distribution, where both false positives and false negatives matter. <br/>
Formula: F1 Score = 2 × (Precision+Recall / Precision×Recall)
​
