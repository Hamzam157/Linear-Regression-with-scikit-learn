# Linear-Regression-with-scikit-learn

Python Libraries Used:-
                      Pandas, Numpy, Matplotlib ,Seaborn, Scikit-learn
                      
## Using Linear Regression for predictive analysis 

Using regression on a hypothetical dataset to predict future values and the relationship between the two variables

Variable Y = Revenue 
Variable X = Budget

![image](https://user-images.githubusercontent.com/113868226/201599950-07a2383d-fc0a-4314-80be-d1d088e28f90.png)

![image](https://user-images.githubusercontent.com/113868226/201600079-2c4840ee-9b2e-40ca-a3ea-5ebd5cfd8ad9.png)

Predicting new values using regression:

![image](https://user-images.githubusercontent.com/113868226/201600308-6a9e0ab7-84f5-4cac-a1db-e88d5af4a59e.png)

Fixing the overfit nature of the model:

i: Model performs well on the original (training) dataset, but it does not generalize well to new data (test set)
ii: Removing noise fromt the training set
iii: Setting up a polynomial equation of degree 9 (Perfect Fit) 

poly_m = np.polyfit(x = df.budget, y = df.revenue, deg = 9) # polynomial regression (deg = 9)

Resulting output:

![image](https://user-images.githubusercontent.com/113868226/201600773-ad532856-b973-44e5-bd34-ab085b816284.png)

Solutions to overcome overfitting:
-use a simpler model with fewer parameters (linear rather than polynomial)
-more and better data (remove outliers & errors)
-Constrain the model -> make the model more simple with Regularization

Solutions to overcome underfitting:
-use a more powerful model with more parameters
-add more/better features (independent variables) to the algorithm -> Feature Engineering
-Reduce the constraints of the model -> make it more complex with less Regularization

Using an example of Study Hours vs Pass/Fail

![image](https://user-images.githubusercontent.com/113868226/201601233-5bbc00fb-906a-4e03-94c6-080c5a9bf7b4.png)

Using Linear Regression to draw insights

![image](https://user-images.githubusercontent.com/113868226/201601361-c8a1ef37-dd5d-40ca-845f-667b3ca86661.png)

![image](https://user-images.githubusercontent.com/113868226/201601428-5427e443-e0ae-486c-8c75-40115fcd9cb5.png)

Tuning our model (Overcoming noise within the data)

![image](https://user-images.githubusercontent.com/113868226/201601642-0f5d0aa3-3e73-4ad9-81d9-2153f422cd8b.png)



