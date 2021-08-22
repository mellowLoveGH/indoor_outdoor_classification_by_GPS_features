# indoor_outdoor_classification_by_GPS_features
use the GPS information to classify whether it is indoor or outdoor

GPS is a very general way to localize, and it always useful outdoors but not indoors.
While there are some special situations such as the places near windows/doors, which frequently confusing to make a judgement by GPS info.

Here the project is a research about how to make a classification between indoor & outdoor by using GPS info.

Collect data of different scenes, all including indoor & outdoor.
Training data was collected by one person, with testing data collected by another, which could reduce overfitting.

Then using different models to learn and predict, such as Random forest, SVM, logistic regression, & neural networks.
