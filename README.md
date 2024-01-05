Abstract:
This project focuses on analyzing the relationships between diabetes, obesity, and physical inactivity using statistical methods and linear regression models. The study employs data from different sources and employs various statistical measures to investigate the associations between these health indicators. Additionally, three linear regression models are built to predict inactivity, diabetes, and obesity based on selected variables.

Motivation:
Understanding the relationships between health indicators such as diabetes, obesity, and physical inactivity is crucial for public health planning and intervention strategies. This project aims to contribute valuable insights into these relationships and provide a basis for further research and policy development.

Background:
The project utilizes data on diabetes (% DIABETIC), obesity (% OBESE), and inactivity (% INACTIVE) obtained from different datasets. Statistical measures such as mean, median, skewness, standard deviation, and kurtosis are calculated to gain an initial understanding of the data's distribution and characteristics.

My Work:
The data preprocessing steps involve cleaning and converting selected columns to numeric values. Subsequently, descriptive statistics, including mean, median, skewness, standard deviation, and kurtosis, are computed for each health indicator. Further, a new Excel sheet is created by merging relevant data, and repeated columns are removed in subsequent steps.
Linear regression models are constructed to analyze the relationships between the health indicators. Model A predicts inactivity based on diabetes and obesity, Model B predicts diabetes based on obesity and inactivity, and Model C predicts obesity based on inactivity and diabetes. The models are evaluated using cross-validation, VIF calculations, and statistical significance tests.

Results:
The analysis reveals insights into the relationships between diabetes, obesity, and inactivity. Model B, predicting diabetes based on obesity and inactivity, shows the highest mean R-squared and F-statistic, indicating its better performance compared to other models. However, all models exhibit some level of multicollinearity, as evidenced by elevated VIF values.

Conclusion:
The project contributes to the understanding of the complex relationships between health indicators, emphasizing the importance of considering multiple factors simultaneously. While Model B appears to perform the best in terms of predictive accuracy, further investigation and refinement of models are recommended to account for potential multicollinearity issues.
