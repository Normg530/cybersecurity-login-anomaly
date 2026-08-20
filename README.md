# cybersecurity-login-anomaly
Machine learning project for detecting suspicious activity 
dataset used is cybersecurity_login_dataset.csv which 
uses login activity and the following features:

- login_attempts
- failed_logins
- unusual_login_hour
- new_ip_address
- suspicious

A Logistic Regression model is used to classify login activity
as normal or suspicious

regarding the model, 
The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score

findings 

The project demonstrates how machine learning can be used to
identify potentially suspicious login or patterns.

The analysis shows that several login characteristics are associated with
suspicious activity.

The strongest model feature was login_attempts, followed by
unusual_login_hour, new_ip_address, and failed_logins.


Results
The results suggest that repeated login attempts and unusual login behavior
can provide useful signals for identifying potentially suspicious activity.

Limitations
There are limitations such as no ip addresses , just new ip addresses
Also, there are only five columns and more information would be useful. 
Lastly, the dataset only shows suspicious activity, not that an actual event took 
place. 


