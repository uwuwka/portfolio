teacher training project

description:
Customers began to leave Beta-Bank. Every month. A little, but noticeable. Banking marketers figured it was cheaper to keep current customers than to attract new ones.

it is predicted whether the client will leave the bank in the near future or not.

3 models with different hyperparameters were considered in the project: LogisticRegression, RandomForestClassifier, DecisionTreeClassifier. From these models, the model with the best ratio of speed and accuracy was selected.
Models with an extremely large value of the F1-measure are constructed.
Additionally measured AUC-ROC and compared with the value with the F1-measure.

The result of the work of the models was high AUC-ROC and F1-measures, which tells us about the high quality of the models themselves, i.e. models make their predictions quite accurately and these predictions can be trusted.
the final model was tested for adequacy in comparison with the contant model:
accuracy_score with model constant: 0.791
accuracy_score of the final model: 0.837
AUC-ROC model constant: 0.5
AUC-ROC of the final model: 0.849
model with parameters: depth - 12 number of branches - 20 and random state - 12345
