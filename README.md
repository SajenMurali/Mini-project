## Title of the Project
Smartphone Usage and Sleep Quality: Insights and Predictions with Additional Validation Using Smartwatch Data is a data-driven study that examines how daily smartphone usage patterns influence sleep quality. The project combines self-reported data (such as screen time, bedtime, and perceived sleep quality) with objective smartwatch sleep metrics to create a hybrid, research-grade dataset. Using statistical analysis, data visualization, and machine learning models, the study identifies key relationships between phone usage habits and sleep outcomes, predicts sleep quality levels, and validates findings using smartwatch data for improved accuracy and reliability.

## About
Smartphone Usage and Sleep Quality: Insights and Predictions with Additional Validation Using Smartwatch Data is a comprehensive data science project aimed at understanding the relationship between smartphone usage habits and sleep quality among individuals. In today’s digital era, excessive smartphone use—especially before bedtime—has raised concerns about its impact on sleep duration, sleep efficiency, and overall sleep health. This project seeks to scientifically analyze these effects using both subjective and objective data sources.

The study involves collecting self-reported data from participants through structured online forms, including variables such as daily smartphone screen time, phone usage before sleep, bedtime routines, wake-up time, perceived sleep quality, and daytime tiredness. To improve the reliability and accuracy of the analysis, this data is validated and enhanced with smartwatch-based sleep data, such as total sleep duration, deep sleep time, light sleep time, number of awakenings, and overall sleep efficiency. The combination of these two data sources creates a hybrid, research-grade dataset that reduces bias and strengthens the findings.

Once the data is collected, extensive data preprocessing and cleaning are performed to handle missing values, remove inconsistencies, and standardize measurements (for example, converting sleep duration into decimal hours). Exploratory Data Analysis (EDA) techniques, including visualizations and statistical summaries, are then applied to identify patterns and correlations between smartphone usage behavior and various sleep parameters. This helps in understanding trends such as how increased screen time or late-night phone usage affects sleep quality and sleep fragmentation.

Following the exploratory phase, machine learning models are developed to predict sleep quality levels based on smartphone usage features. Models such as linear regression, decision trees, or classification algorithms are used to estimate outcomes like sleep quality rating or sleep efficiency. The performance of these models is evaluated using appropriate metrics, and predictions are cross-checked with smartwatch data to ensure consistency and validity.

The final outcome of the project provides actionable insights into how smartphone habits influence sleep health and demonstrates how combining subjective survey data with objective wearable data leads to more accurate and trustworthy conclusions. This project has practical applications in health analytics, behavioral research, and personalized wellness recommendations, and it highlights the importance of responsible smartphone usage for improving sleep quality

## Features
- Uses a hybrid dataset combining self-reported smartphone usage data and smartwatch-based sleep metrics for higher accuracy.
- Implements machine learning models to analyze patterns and predict sleep quality.
- Supports data validation using wearable device data to reduce bias and improve reliability.
- Performs exploratory data analysis (EDA) with statistical and visual insights.
- Ensures high scalability for adding more users and extended data collection over time.
- Optimized for low time complexity through efficient data preprocessing and model training.
- Enables future deployment as a framework-based application (web or dashboard).
- Provides research-grade insights suitable for academic and healthcare analytics.
- Allows easy feature expansion, such as additional sleep or health parameters from smartwatches.

## Requirements
* Operating System: Requires a 64-bit operating system such as Windows 10/11 or Ubuntu for efficient data processing and model execution.
* Development Environment: Python 3.7 or later is required for data analysis, machine learning model development, and evaluation.
* Machine Learning Frameworks: Utilizes scikit-learn for traditional machine learning models and TensorFlow/Keras for advanced predictive modeling.
* Data Analysis Libraries: Includes NumPy and Pandas for data handling, preprocessing, and transformation.
* Data Visualization Tools: Matplotlib and Seaborn are used for exploratory data analysis and graphical representation of insights.
* Smartwatch Data Integration: Supports data inputs from wearable devices (e.g., CSV/JSON formats) for sleep metrics validation.
* IDE: Visual Studio Code (VSCode) is used as the Integrated Development Environment for coding, debugging, and package management.
* Version Control: Git is used for source code management, collaboration, and tracking project changes.
* Additional Dependencies: Includes Jupyter Notebook, SciPy, and Joblib for experimentation, statistical analysis, and model persistence.

## System Architecture

<img width="555" height="324" alt="image" src="https://github.com/user-attachments/assets/6ef4249a-d474-4af7-bb50-6389c348646c" />



## Output
#### Output1 - Name of the output

<img width="509" height="358" alt="image" src="https://github.com/user-attachments/assets/8e1f4c7a-536b-4979-8864-e079ca6a05d9" />
Detection Accuracy: 48.7%



#### Output2 - Name of the output
<img width="480" height="375" alt="image" src="https://github.com/user-attachments/assets/0ca558d5-51d7-4eb8-b103-4e6bc548dfae" />


Detection Accuracy: 67%



## Results and Impact
The experimental results demonstrate that smartphone usage patterns exhibit a measurable, though moderate, relationship with sleep-related outcomes. For subjective sleep quality prediction, the Random Forest model achieved a mean cross-validation accuracy of approximately 48%, while the Artificial Neural Network (ANN) improved performance to around 54%. This indicates that deep learning models are more effective in capturing the non-linear and complex behavioral interactions between screen time, social media usage, and phone unlock frequency. However, the moderate accuracy also highlights the inherent limitations of relying solely on self-reported sleep quality, which is influenced by individual perception and recall bias.

When models were trained on the objective sleep duration target, performance showed a clearer and more stable pattern. Random Forest achieved higher accuracy compared to subjective sleep quality prediction, and ANN demonstrated competitive performance across folds, exceeding random chance for three-class classification. These results confirm that objective sleep metrics are more predictable from behavioral data than subjective assessments, reinforcing the importance of measurable sleep indicators in sleep-health research.

The impact of this work lies in its methodological contribution rather than raw predictive accuracy. By systematically identifying issues such as data leakage, class balance, and subjectivity in labels, the proposed framework establishes a reliable and research-grade approach to behavioral sleep analysis. The clear contrast between subjective and objective targets strongly supports the integration of smartwatch-derived physiological data for validation. This hybrid modeling and validation strategy enhances scientific reliability and positions the system as a scalable, cost-effective solution for digital wellness research, personalized health monitoring, and future sleep-aware interventions.

## Articles published / References
1.K. Demirci, M. Akgönül, and A. Akpinar, “Relationship of smartphone use severity with sleep quality, depression, and anxiety in university students,” Journal of Behavioral Addictions, vol. 4, no. 2, pp. 85–92, 2015.
2.S. Abdullah, M. Matthews, E. Frank, G. Doherty, G. Gay, and T. Choudhury, “Automatic detection of sleep duration and quality using wearable and smartphone data,” Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies, vol. 1, no. 3, pp. 1–22, 2016.





