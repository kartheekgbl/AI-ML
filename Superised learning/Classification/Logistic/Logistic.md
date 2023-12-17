# Logistic Regression

![Logistic](Images\log1.png)

## It is similar to Linear regression

![linear](Images\Linear.png)

#### 1. Logistic regression have two type of categorical variables 0 and 1

#### 2. We have to change the continuous values into categorical values

#### For that purpose we use Sigmoid Function

## $g(x)=1/1+e^-x$

## Our Model Looks like this

![Logistic Curve](images/log2.png)

### about Probability values (0 to 1)

![Pb](images/pb.png)

## Decision Boundary

- Which boundary seperate the two classes that boundary is called Decision Boundary

- To predict which class a data belongs, a **Threshold can be set**
- Based upon threshold , the obtained estimation probability is classified into classes.
- This Threshold is claaed the Decision Boundary

- Say if predictd_value >= 0.5 then classify email is spam else not spam

- **Decision boundry can be linear or non-linear.** Polinomial order can be increased to get complex decision boundary
- We can fix the threshold value by **ROCAUC** curves

## Types of Logistic Regression

### 1. Binary

- The target variable have only two possible outcoms
- for ex. Classifying e-mail is spam or not spam

### 2. Multinomial

- The target variable have more than 3 outcomes with out oredering
- for ex. Veg ,Non-veg, vegan

### 3. Ordinal

- The target variable have more than 3 outcomes oredering
- for ex. movie rating from 1 to 5
 