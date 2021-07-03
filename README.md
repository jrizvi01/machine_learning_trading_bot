# machine_learning_trading_bot

## Backgound

This application utilizes machine learning algorithms which learns and adapts to new data and evolving markets and generate predictive trading signals.

## Usage

This application does the following:
 * Establishes a Baseline Performance
 * Tunes the Baseline Trading Algorithm
 * Evaluates a New Machine Learning Classifier by using the original training data as    the baseline model

## Technologies
 * pandas - pandas is a fast, powerful, flexible and easy to use open source data             analysis and manipulation tool, built on top of the Python programming             language.
 * numpy -  NumPy is a library for the Python programming language, adding support for             large, multi-dimensional arrays and matrices, along with a large collection             of high-level mathematical functions to operate on these arrays.
 * hvplot - A high-level plotting API for the PyData ecosystem built on HoloViews.
 * scikit-learn - Machine learning library for the Python programming language. It                   features various classification, regression and clustering algorithms                   including support vector machines, random forests, gradient boosting,                   k-means and DBSCAN.


## Evaluation Report

### Establish a Baseline Performance
#### (3 Months)

![image](https://user-images.githubusercontent.com/80922524/124336868-baa45600-db54-11eb-870d-20a37dfc7bea.png)

![image](https://user-images.githubusercontent.com/80922524/124335246-93e32100-db4e-11eb-91fd-15d394df85d1.png)


### Tune the Baseline Trading Algorithm

#### Step 1: Tune the training algorithm by adjusting the size of the training dataset.
#### (18 Months)

![image](https://user-images.githubusercontent.com/80922524/124341468-7bd0c900-db71-11eb-849b-7c4899f8aa43.png)

![image](https://user-images.githubusercontent.com/80922524/124341479-8ee39900-db71-11eb-97aa-810d9d0ac29d.png)

##### Question: What impact resulted from increasing or decreasing the training window?
Answer: By icreasing the training window to 18 months, we can see that performance of the predictive model improved.

#### Step 2: Tune the trading algorithm by adjusting the SMA input features.

![image](https://user-images.githubusercontent.com/80922524/124342054-d2400680-db75-11eb-9a7a-eb58835a45a9.png)

![image](https://user-images.githubusercontent.com/80922524/124342064-e71c9a00-db75-11eb-9319-8f8be34a1580.png)


#### Logistic Regression Model
![image](https://user-images.githubusercontent.com/80922524/124342208-2ac3d380-db77-11eb-9bd7-44bc36b984bb.png)

![image](https://user-images.githubusercontent.com/80922524/124342234-52b33700-db77-11eb-972f-3127a8960d6b.png)

##### Question: What impact resulted from increasing or decreasing either or both of the SMA windows?
Answer: By increasing both the short and long SMA windows  to 50 and 200 respectively, we can see that performance of the predictive model improved.

#### Step 3: Choose the set of parameters that best improved the trading algorithm returns.
18-months model returned the best results


