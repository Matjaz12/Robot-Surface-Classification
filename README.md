# Classifying surface types from robot sensory data

In this notebook we attempt to classify surface types from robot sensor data ( [3]). The notebook is heavily inspired by the following two projects, presented in [1], [2]. We experiment with a LSTM Model and CNN + LSTM Model, as well as augmentation techniques for time series data.

### TODO:
+ It seems like the normalization of the time series is incorrect, research this and potentially retrain the models with correct normalization.

## References 
[1] https://www.youtube.com/watch?v=PCgrgHgy26c&t=85s&ab_channel=VenelinValkov
[2] https://www.youtube.com/watch?v=ODEGJ_kh2aA&ab_channel=VenelinValkov
[3] https://www.kaggle.com/competitions/career-con-2019/data