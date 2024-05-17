## SECTION 4 - MACHINE LEARNING MODELS

### Model Sources
In order to be able to apply many models to the data, pre-built models were selected; this came with the added benefits that they were known to be effective for the task of time-series classification, and and performance evaluation and inference was in-built in most of them. These came from 2 sources: the python package [tsai](https://timeseriesai.github.io/tsai/) and public models from [Kaggle](https://www.kaggle.com/)

##### TSAI
Using tsai, we performed a benchmark test (only validation accuracy was recorded) with a variety of models on both datasets, this then guided which models to apply to the datasets; this was done as the time it takes to fully train all these models would have been computationally significant.

Full models:
- ResNet
- XceptionTime
- InceptionTime
- Time Series Transformer
- MiniRocket

##### Kaggle
The following notebook models were used: 
- [Exoplanet Hunting: TOP Score using SMOTE and CNN](https://www.kaggle.com/code/antonzv/exoplanet-hunting-top-score-using-smote-and-cnn/data)
- [Exoplanet detection using Spiking Neural Networks](https://www.kaggle.com/code/ashish21/exoplanet-detection-using-spiking-neural-networks)


