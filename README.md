This project implements a machine learning-based predictive maintenance system to forecast industrial machinery failures before they occur.
By analyzing real-time and historical sensor data (temperature, speed, torque, tool wear, etc.), the system identifies patterns that precede failures, enabling proactive maintenance and reducing costly downtime.

==>Key Features :
Data Collection & Preprocessing: Cleaned, normalized, and feature-engineered dataset from Kaggle.

Model Development: Implemented Random Forest Classifier for multi-class failure prediction.

Deployment: Hosted on IBM Cloud watsonx.ai Studio with a real-time API endpoint.

Monitoring: Integrated IBM Cloud Object Storage, Cloud Monitoring, and Dashboard for visualization and alerts.

Evaluation: Metrics include accuracy, precision, recall, F1-score, and confusion matrix.

==>Tech Stack :
IBM Cloud (Watson Machine Learning, Object Storage, Monitoring)

Python (Pandas, NumPy, Scikit-learn)

Machine Learning Algorithms: Random Forest, SVM (optional)

==>Results :

The deployed model accurately predicts multiple fault types, enabling organizations to schedule maintenance ahead of failures, improving operational efficiency and reducing downtime.
