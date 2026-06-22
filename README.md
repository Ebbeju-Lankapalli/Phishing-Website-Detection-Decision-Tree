Phishing Website Detection using Decision Tree

Project Overview

This project uses a Decision Tree Classifier to identify whether a website URL is phishing or legitimate based on URL structure, domain information, security features, and website behavior indicators.

The objective is to build a machine learning model capable of detecting potentially malicious websites and helping improve cybersecurity awareness.

⸻

Dataset Information

The dataset contains multiple URL-based features such as:

* Having IP Address
* URL Length
* Shortening Service
* SSL Certificate Status
* Domain Registration Length
* Web Traffic
* Google Index
* Page Rank
* Statistical Reports
* And several other phishing-related indicators

Target Variable

Value	Meaning
-1	Phishing Website
1	Legitimate Website

⸻

Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Google Colab

⸻

Workflow

1. Data Loading

* Imported training and testing datasets.
* Inspected dataset structure and features.

2. Data Cleaning

* Checked for missing values.
* Checked for duplicate records.

3. Exploratory Data Analysis (EDA)

* Target distribution analysis.
* Correlation heatmap visualization.

4. Model Building

* Train-Test Split
* Decision Tree Classifier Training

5. Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix
* Cross Validation

6. Prediction

* Generated predictions for unseen test data.
* Exported predictions as CSV file.

⸻

Model Used

Decision Tree Classifier

Advantages:

* Easy to interpret
* Handles categorical-style features effectively
* Requires minimal preprocessing
* Fast training and prediction

⸻

Results

The model was evaluated using:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Cross Validation Accuracy

⸻

Visualizations

* Target Distribution Plot
* Correlation Heatmap
* Confusion Matrix
* Decision Tree Visualization

⸻

Project Structure

Phishing-Website-Detection-Decision-Tree/
│
├── Phishing_Website_Detection_Decision_Tree.ipynb
├── submission.csv
├── README.md

⸻

Author

Ebbeju Lankapalli

B.Tech Artificial Intelligence & Machine Learning

Aspiring Machine Learning Engineer
