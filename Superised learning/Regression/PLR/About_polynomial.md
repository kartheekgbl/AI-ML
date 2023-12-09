# Polynomial Regression

- If the relationship between the dependent and independent variable is not linear, then linear regression cannot be used as it will result in large errors

![Simple](Images\Simple_Linear.png)
![polinomial](Images\ploynomial.png)

### We have 2 methods to do the problem of non linear regression

- Transformation of non-linear data to linear data, so that the linear regression can handle the data
- Using polinomial regression

#### 1. Transformation

- The trick is to convert non-linear data to linear data that can be handled using the linear regression method

- Let us consider an exponential an function $y=ae^{bx}$
- The transformation can be done by applying log function to both sssides to get

## ln(y)=ln(a)+ln($e^{bx}$)

## ln(y)=ln(a)+bx\*ln(e)

## ln(y)=ln(a)+bx

The above last equation is the linear function which is looks like **y=c+mx**

Now we have to apply the linear regression model after that we should reverse the same process to convert the linear to polinomial

#### 2. Polinomial Regression

- It can handle non-linear relationships among variables by using nth degree of a polinomial
- Instead of applying transformations, polynomial regression can be directly used to deal with differnt levels of curvillinearity.
- for example the second degree polinomial (called quadratic transformation) is give as:
  y=$a0$+$a1x$+$ax^2$ and third degree polinomial (called cubic transformation) given as:
  y=$a0$+$a1x$+$ax^2$+$ax^3$
- Generally, polynomials of maximum degree 4 are used, as higher order polinomials take some strange shapes and make the curve more flexible.
- It leads to a situation of overfitting and hence is avoided

## Let Consider the polinomial of 2nd degree

The equation is: y=$a0$+$a1x$+$ax^2$

Formula to find the cofficients a0,a1,a2 is: a=$X^{-1}B$

here image clears your doubt:
![Alt text](Images\process1.png)

![Alt text](Images\process2.png)

## Now This is the time to see the code in PLR series
