# tetouan-power-consumption-prediction

## Abstract
This project focuses on leveraging machine learning algorithms to predict power consumption in Tetouan city, Morocco, using a comprehensive dataset spanning from January 1st, 2017, to December 30th, 2017. The dataset encompasses various environmental factors such as temperature, humidity, wind speed, and different diffuse flows, alongside power consumption data from three distribution zones: Quads, Smir, and Boussafou. The goal is to explore the efficacy of different machine learning techniques, including Decision Tree Learning, Random Forests, KNN, Naïve Bayes, SVM, and Artificial Neural Networks, in accurately predicting power consumption. Through comparative analysis, this project aims to identify the most suitable algorithm for predicting power consumption, considering historical data and environmental factors. The findings contribute to a deeper understanding of machine learning applications in energy consumption forecasting and provide insights relevant to urban energy management in Tetouan city and similar contexts&#8203;:citation[oaicite:3]{index=3}&#8203;.

## Goal
The primary objective of this project is twofold. Firstly, we aim to leverage machine learning algorithms to derive regression models capable of accurately predicting power consumption within the Tetouan city networks. These regression models serve as vital tools for forecasting energy demand, facilitating efficient resource allocation, and aiding in infrastructure planning.

Secondly, our focus lies on conducting a detailed comparative analysis of different machine learning algorithms. By evaluating and contrasting the performance of these algorithms in the context of power consumption prediction, we could draw a conclusion on their strengths, weaknesses, and applicability within the domain. Through this comparative analysis, we aim to provide valuable insights into the suitability of various machine learning approaches for addressing similar real-world problems in energy consumption forecasting.

## Dataset Description
**Origin of the Data:**
The dataset used for this project is sourced from https://archive.ics.uci.edu/dataset/849/power+consumption+of+tetouan+city . This dataset provides detailed information on the power consumption across three different distribution networks in Tetouan, a city located in northern Morocco. The primary objective of this dataset is to facilitate regression tasks aimed at predicting power consumption based on various environmental and temporal factors.

**Significant Attributes:**
- **DateTime:** Recorded at ten-minute intervals, this feature tracks power consumption over time, crucial for understanding temporal dynamics and periodicity in energy usage.
- **Temperature:** A continuous variable representing weather temperature and is a significant predictor of power consumption due to its influence on air conditioning and cooling systems.
- **Humidity:** Another continuous variable, measures the moisture content in the air. Typically, higher humidity levels can influence the operation of dehumidifiers and air conditioning systems, thereby affecting power consumption.
- **Wind Speed:** Another continuous feature that captures wind velocity in meters per second, influencing perceived temperature and cooling requirements, and thus energy usage.
- **General Diffuse Flows and Diffuse Flows:** Measure solar radiation in watts per square meter, essential for understanding the impact of sunlight on power consumption, particularly for heating and cooling demands.
- **Zone 1, Zone 2, and Zone 3 Power Consumption:** These are the target variables representing electricity usage in three distinct zones of Tetouan city, used to develop models predicting power consumption based on environmental and temporal features.


## Conclusion
This project undertook a comprehensive comparative analysis of various machine learning models (Decision Tree, Random Forest, K-Nearest Neighbors, Support Vector Machine, Naive Bayes, and Neural Networks) for a regression task aimed at predicting power consumption in three zones of Tetouan City, Morocco. Through meticulous model tuning and performance evaluation, we derived valuable insights into the efficacy of each algorithm in capturing the patterns within the power consumption data.

This comparative analysis enriches the existing body of knowledge by empirically demonstrating the strengths and weaknesses of different machine learning models in a specific application context. It highlights the importance of model selection and tuning in achieving optimal predictive performance. By linking model performance to both algorithmic characteristics and data patterns, this study provides a nuanced understanding of why certain models perform better than others, and highlights the significance of using comprehensive datasets for training models, particularly in scenarios where capturing intricate relationships is crucial for accurate predictions.

From a practical side, the results can provide a framework for predicting power consumption in urban settings, offering utility companies and policymakers robust tools to forecast demand more accurately. Such predictions can inform load management strategies, optimize resource allocation, and enhance the reliability of the power grid, particularly during peak usage periods driven by extreme weather conditions.

## Note
A detailed documentation of the project is available in the file named "Machine_Learning_Project_Report.pdf".
