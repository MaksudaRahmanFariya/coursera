<h2>Binomial Logistic Regression </h2>
<p>Binomial Logistic Regression mainly predicts the probability that an
observation falls into one of two categories of dichotomous dependent
variable based on one or more independent variables that can be either continues
or categorical! </p>

<h3>Explanation :</h3>

<p> Binomial Logistic Regression determines impact of multiple independent
variables presented together to predict membership of one or other
of two dependent variable categories. 
In general it can be told that it is used to predict relationship
between predictors and predicted variable.
predictors means independent variable.In dataset which features are used to predict.
There must be two or more independent variables(features)
or predictors for Binomial Logistic Regression.

</p>

<p> Mathematically we can say: <p>
<p> Let X £ <b>R<sup>d</sup></b> X=feature vector </p>
<p>Y £ {0,1}  [Y = label ]</p>
<p>X,  Y = random variables </p>
<p>The dependent variable Y is a nx1 vector

    So P(Y=1|X =x) = sigma(bita_0 + transpose(bita_1)*x)
Where sigma(u) = e<sup>u</sup> /(1+e<sup>u</sup>)
and bita_0 £ <b>R</b> and 
bita_1 £ <b> R <sup>d</sup></b> are parameters of model. 

</p>
<h3> Note :</h3>
<p> Logistic Regression is one of the binomial regression models and
uses logit as its link function! </p>








