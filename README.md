# indoor_outdoor_classification_by_GPS_features
1. goal
use the GPS information to classify whether it is indoor or outdoor

2. more inllustration
GPS is a very general way to localize, and it always useful outdoors but not indoors.
While there are some special situations such as the places near windows/doors, which frequently confusing to make a judgement by GPS info.
Here the project is a research about how to make a classification between indoor & outdoor by only using GPS info.

3. data
Collect data of different scenes, all including indoor & outdoor.
Training data was collected by one person, with testing data collected by another, which could reduce overfitting.
And the main features about the data contain 12 features, such as:
1) number: how many numbers of satellites the mobile phone can find
2) SNR (sigal noise ratio): the total of every satellite's snr.
3) ele: the total of every satellite's  elevation.
etc. 

4. models:
Then using different models to learn and predict, such as Random forest, SVM, logistic regression, & neural networks.

5. files
1) GPS_test01.ipynb, the code icluding how to parse raw data as CSV strutured training & testing data, model to train & test, visualization of analysis, etc.
2) gps_features_analysis.pdf, the analysis report.
3) gps_models_performances.pdf, the performance of different models
4) trained_nn_models, the list of trained Neural Network models that have relatively good performance with accuracies all above 85%.

6. more file will be uploaded, such as the raw data, CSV training and testing data, and some necessary data when parsing the raw.

7. Thank you
