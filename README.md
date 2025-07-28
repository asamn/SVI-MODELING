Colab URL: https://colab.research.google.com/drive/1X4i6mHtawzV4QUCqpoEvicYnTWO1mmee?usp=sharing

Gun violence remains an undeniably critical health issue in the United States, with significant disparities observed across communities. This study investigates the relationship between the Centers for Disease Control and Prevention’s (CDC) Social Vulnerability Index (SVI) and firearm-related death rates at the county level, employing machine learning to identify predictive patterns. 

We compare the performance of multiple regression models—Support Vector Regression (SVR), Random Forest, and XGBoost—trained on three datasets derived from the SVI: thematic scores, demographic measurements, and an extended dataset incorporating GDP per capita and educational attainment. Results demonstrate that XGBoost outperforms other models, achieving the lowest root mean squared error (RMSE = 9.188) when trained on the extended demographic dataset. Feature importance analysis reveals that socioeconomic status is the most influential thematic predictor of gun violence, while demographic measurements highlight the disproportionate impact on African American communities. 

Our findings underscore the utility of the SVI as a tool for understanding gun violence and emphasize the need for targeted interventions in socioeconomically vulnerable and minority com- munities. Future research could enhance predictive power by integrating additional variables such as gun ownership rates and mental health statistics. 

Index Terms—gun violence, social vulnerability index, machine learning, predictive modeling, regression, XGBoost
