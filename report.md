# CS 178 Final Report

## 1. Abstract
Income is a significant measure of a individual, thier  lifestyle, and their role in society. When individuals make goals regarding thier career or finances, understanding how individuals become sucessful or have a high income is importaint. Reporting demographics or US citizens against a certain annual income helps isolate features and feature combinations that result in financial sucess for individuals, can help police reported incomes, and gives a clearer picture into the lives of the nation, and how they change over time. In particular, this report will feature what makes an individual an above-average earner. Kaggle and the UCI ML Repo provide the Adult Income Dataset, a subset of Income data from the 1996 US Census, that provides a demographics against a classification of individual income. This classification regards if the income of an individual, in the 1995 fiscal year, was above $50,000 USD. Various models including Graient and Hisogram Boosed Tree models will be used for classification.

## 2. Data Exploration

The Adult Income dataset consists of 32,561 observations of 15 factors, including both categorical and numeric factors.

#### Numeric Factors

| Factor          | Variance       | Mean      |
|-----------------|----------------|-----------|
| age             | 186.056        | 38.5816   |
| fnlwgt          | 1.11405e+10    | 189778    |
| education_num   | 6.61869        | 10.0807   |
| capital_gain    | 5.45409e+07    | 1077.65   |
| capital_loss    | 1.62372e+05    | 87.3038   |
| hours_per_week  | 152.454        | 40.4375   |

#### Categorical Factors



## 3. Data Preprocessing
- **Data Cleaning**: Handling missing values, outliers, and inconsistencies.
- **Feature Engineering**: Creation of new features, feature selection, and transformation.
- **Data Splitting**: Splitting the data into training, validation, and test sets.

## 4. Model Selection and Training
- **Model Choices**: Description of different models considered (e.g., neural networks, support vector machines, random forests).
- **Parameter Tuning**: Exploration of various hyperparameters and their impact on model performance.
- **Model Training**: Training process for each model, including any specific techniques used.

## 5. Model Evaluation
- **Performance Metrics**: Metrics used to evaluate model performance (e.g., accuracy, precision, recall, F1 score).
- **Validation Techniques**: Use of validation or cross-validation to assess model performance.
- **Comparison of Models**: Comparative analysis of different models and their performance.

## 6. Model Optimization
- **Addressing Underfitting/Overfitting**: Strategies used to handle underfitting and overfitting.
- **Feature Design**: Impact of feature design on model performance.
- **Special Data Handling**: Techniques used to handle special aspects of the data (e.g., missing features, large numbers of zeros).

## 7. Final Model and Results
- **Chosen Model**: Description of the final model selected.
- **Final Performance**: Performance of the final model on the test set.
- **Insights and Interpretations**: Key insights and interpretations from the final model's performance.

## 8. Conclusion
- **Summary**: Summary of the project and key findings.
- **Future Work**: Potential future work and improvements.

## 9. References
- **Citations**: List of references and resources used in the report.