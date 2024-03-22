# The State of Charge Estimation of LiFePO4 Batteries Performance Using Feed Forward Neural Network Model

## About
This is actually my final college project researching the most optimal machine learning model for predicting the State of Charge (SoC) of Lithium Iron Phosphate (LFP) batteries. Here, I use hyperparameter tuning with GridSearch to identify the best model parameters.

## Model architecture
I use Deep Feed-Forward Neural Network to estimate the SoC of LFP Battery which contains 5 layer. Here is my architecture diagram

![[architecture diagram]](/img/model_architecture.png)

## Model performance
This model achieved the best performance in predicting the State of Charge (SoC) of the battery.  The final Mean Absolute Error (MAE) of the model was 0.0061, and the Spearman's Rank Correlation Coefficient was a high 0.99.
here is my model performance

![[Model Performance]](/img/model_performance.png)

## result
The relationship between State of Charge (SoC) and voltage is visualized through a graph.

![[Graph of SoC]](/img/graph.png)


### Journal
If you are interested in my research, you can deeply read my journal and understand it by reaching it on this Link. https://bit.ly/4a7hQc2
