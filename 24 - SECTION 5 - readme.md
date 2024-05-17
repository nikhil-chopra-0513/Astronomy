## SECTION 5: RESULTS

##### Model Results
<p>The following indicates the results obtained from the various models: 

Global View Data - Valid Accuracy, Test Accuracy
<ul>
<li>Time Series Transformer: 0.8194, 0.7582</li>
<li>ResNet: 0.8750, - </li>
<li>InceptionTime: 0.4167, - </li>
<li>LSTM_FCN: 0.8194, - </li>
<li>xresnet1d34: 0.4167</li>
<li>MiniRocket: 0.8194, - </li>
</ul>

Raw View Data - Valid Accuracy, Test Accuracy
<ul>
<li>Time Series Transformer: 0.7702, 0.6989</li>
<li>ResNet: 0.7973, - </li>
<li>InceptionTime: 0.7703, - </li>
<li>LSTM_FCN: 0.7838, - </li>
<li>xresnet1d34: 0.7838, - </li>
<li>MiniRocket: 0.7297, - </li>
</ul>


As we can see, the best model is the Time Series Transformer, by a large margin; and the best dataset was the 'global view'. Hence, this model was further trained, with 1000 epochs and optimised with hyperparameter tuning applied to the dropout rate.
The final test accuracy obtained was 84%.