Resolving classification and regression problems

1. Adults

Best model: XGBoost  ~87 % accuracy

Our basic model achieved 87% accuracy with a quite stable learning curve (a bit overfitted but for the purpose of this exercise acceptable). 

2. Adults2
In this case the hyperparameters optimization (hyperopt and grid random search) was for no use at all.  Non of the them contibuted to a better performance. My  model got overfitted with the best loss: 0.8570989865902344. 
That being said, I should probably develop a bit more feature engineering part or increase the amount of data. Perhaps, the model was too sophisticated for such a simple problem and small dataset.

Summary:
I’ve learned how to use Decision Tree, Random Forest, touch a bit of feature engineering and parameter optimization. After all, validation plays a huge role and can be very helpful in further estimations.

3. Adults3
I made an attempt to split dataset with StratifiedKFold and add some more features. The initial basic model achieved: 87,52%. After using optimization my model have decreased to 85,78 % (which is still less than initial model, but more than "Adults2").


