# NeuralNetwork

Neural Network - House Price Prediction
simple neural network that predicts house prices using the California Housing dataset from sklearn.
What it does
takes 8 features about a housing district (like income, house age, location etc) and predicts the median house price.
Dataset
California Housing dataset — 20,640 samples, 8 features. loaded directly from sklearn so no need to download anything.
Libraries used

scikit-learn
numpy
matplotlib

How to run:
open the notebook in Google Colab and click Runtime → Run all. thats it.
Model

MLPRegressor (scikit-learn)
1 hidden layer with 16 neurons
ReLU activation
Adam optimizer
500 iterations

Results:

MAE: ~0.50
RMSE: ~0.70
R²: ~0.80
