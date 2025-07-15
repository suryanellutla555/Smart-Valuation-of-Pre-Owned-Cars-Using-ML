# Smart-Valuation-of-Pre-Owned-Cars-Using-ML

The focus of this project is to develop machine learning models that can accurately predict the
price of a used car based on its features. In this project, we investigate supervised machine
learning models to predict the price of used cars in India. The predictions are based on historical
data of car details, taken from CarDekho.com. Different models like Random Forest, Extra
Tree Regressor, Bagging Regressor and Decision Tree have been used to make the predictions.
The predictions are then compared in order to find those which provide the best performances.
All four methods provided comparable performance. The number of different attributes is
measured, and also it has been considered to predict a more reliable and accurate result. We
also compared the prediction accuracy of these models to determine the best one. Our results
show that the Random Forest model yields the best results.


## Dataset
The dataset are based on historical data of car details, taken from CarDekho.com.

## Result
| Name of Regressor     | R-Squared Score     | Accuracy        |
| ------------- | ------------- | --------    |
| Decision Tree Regressor        | 0.9457        | 83.71   |
| Random Forest Regressor         | 0.9573        | 87.92   |
| Extra Trees Regressor | 0.9616| 89.12
|Bagging Regressor |  0.9540| 87.57

## Conclusion

Car sales are more often in metropolitan cities where the young software engineers,
business man are showing interest to buy the new cars with the updated technology. So, there
are high chances that they would not want to keep the old car with them and they opt to sale it.
On the other side, new learners and middle-class families don’t show interest in buying the new
expensive cars and opt to buy the refurbished cars.

Refurbished Car price prediction is a challenging task as it involves various parameters
in terms of car specifications and customers satisfaction for solving a high accuracy in
predicting the sales values. The major step involved in this project is data analysing and preprocessing. It involved the study of various attributes, cleaning, inserting and deleting some of
the important and redundant parameters for a better understanding and implementing the
machine learning algorithms.

For this project, the supervised algorithms have been used and four different types of
regression algorithms has been implemented. The algorithms are implemented on the same
dataset in terms of testing data. The error calculations such as Mean Absolute Error (MAE),
Root Mean Squared Error (RMSE) and R-square score were calculated to predict the high
accuracy among the algorithms. Extra Tree Regressor has outperformed decision tree and
bagging regressor. By the fact that both random forest and extra trees regressor are equally
robust the latter slightly dominated. Extra trees regressor is more optimal algorithm for this
problem statement as it has comparatively less time complexity and also similar accuracy.


