<h1> Face Mask Detection using Convolutional Neural Networks </h1>
<br/>
Introduction
In this project, we'll explore the task of detecting whether a person in an image is wearing a face mask or not using Convolutional Neural Networks (CNNs). The dataset used for this project contains images of people both with and without masks.

Steps Involved
1. Setting Up Environment
We start by configuring the environment and installing necessary packages like kaggle to fetch the dataset.

2. Importing Dataset
We download the face mask dataset from Kaggle using the Kaggle API and extract it.

3. Importing Dependencies
We import the required libraries such as numpy, matplotlib, cv2, etc., for image processing and model building.

4. Preprocessing Images
Images are resized to a common size of 128x128 pixels and converted to numpy arrays for further processing.

5. Creating Labels
Labels are created for images with masks (1) and without masks (0).

6. Train-Test Split
The dataset is split into training and testing sets to evaluate the model's performance.

7. Building CNN Model
A CNN model is constructed using TensorFlow's Keras API, consisting of convolutional layers, max-pooling layers, dropout layers, and dense layers.

8. Model Training
The CNN model is trained using the training data.

9. Model Evaluation
The trained model is evaluated using the test data to measure its accuracy.

10. Predictive System
A system is built to predict whether a person in an input image is wearing a mask or not.

<hr/>

### Impact on Society : 
Face mask detection systems like the one developed in this project have significant implications, especially in the context of public health and safety, particularly during pandemics like COVID-19. Here are some potential applications and impacts:

Public Health Monitoring: Automated face mask detection systems can be deployed in public spaces such as airports, train stations, and hospitals to monitor compliance with mask-wearing regulations.

Workplace Safety: Employers can use these systems to ensure that employees are following safety protocols by wearing masks in workplaces, reducing the risk of virus transmission.

Crowd Monitoring: In crowded areas such as shopping malls or events, these systems can help authorities monitor compliance with mask mandates and take appropriate actions if violations occur.

Contactless Enforcement: Automated detection systems eliminate the need for manual enforcement, reducing human intervention and potential conflicts.

Efficient Resource Allocation: By identifying areas with low compliance, resources can be directed towards education and enforcement efforts more efficiently.

Overall, face mask detection systems contribute to public health efforts by promoting adherence to safety guidelines, potentially reducing the spread of infectious diseases, and ultimately saving lives.
<hr/>

### Example Application :

An example application of this face mask detection system is in airports. Airports are high-traffic areas where people from various regions come into contact. By deploying face mask detection systems at airport entrances and other key areas, airport authorities can ensure that all passengers and staff comply with mask-wearing regulations. This not only enhances the safety of travelers but also helps in maintaining the smooth operation of air travel, reducing the risk of virus transmission across different regions.
