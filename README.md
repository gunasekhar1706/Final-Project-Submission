# Predictive Maintenance of Industrial Machinery

Project Summary
This project focuses on Predictive Maintenance of Industrial Machinery using IBM Cloud Lite services and machine learning techniques. The primary objective is to anticipate machine failures before they occur, enabling proactive maintenance that minimizes unplanned downtime and operational costs.

Using the Predictive Maintenance dataset from Kaggle, which includes critical features such as air temperature, process temperature, rotational speed, torque, and tool wear, the data was processed and analyzed entirely on IBM Watson Studio. The project leveraged AutoAI pipelines to automatically preprocess data, select features, and train multiple classification models to predict different failure types, including:

Tool Wear Failure

Power Failure

No Failure

Among all generated pipelines, the Batched Tree Ensemble Classifier (Snap Random Forest Classifier) achieved the highest holdout accuracy of 99.7%, with exceptional precision, recall, and F1 scores, as validated by ROC curves, precision-recall curves, and threshold analysis.

The trained model was deployed using IBM Cloud Watson Machine Learning, allowing real-time prediction of failure types via CSV or JSON input, ensuring quick and reliable decision-making for industrial applications.

This implementation demonstrates how cloud-based machine learning can be effectively applied for predictive maintenance, providing a scalable and cost-efficient solution for industrial machinery monitoring.

