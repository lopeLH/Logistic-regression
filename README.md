# LogisticRegression
Logistic Regression by gradient descent

<img src="https://github.com/lopeLH/LogisticRegression/blob/master/LogisticRegression/githubImages/Sin%20t%C3%ADtulo.png"  width=350 height=455 />


this is a Java implementation of the Logistic Regression classification technique. (Only two features
are provided but we generate more by exponentiation of those provided).The algorithm is applied the same way if we have more natural features (but it would be harder to represent graphically).

The implementation is based on the following update rule,as explained by prof. Andrew Ng at the Stanford-Machine Learning course in Coursera:

<img src="https://github.com/lopeLH/GradientDescent/blob/master/GradientDescent/githubImages/alg.PNG"  width=350 height=175 />

As you can see, the update rules are the same that those used in gradient descent for linear regression, the only difference
is the hypothesis function that now is somehow plugged into the sigmoid (aka logistic) function, that looks like this:

<img src="https://github.com/lopeLH/LogisticRegression/blob/master/LogisticRegression/githubImages/Logistic-curve.svg.png"  width=320 height=213 />

and therefore, the hypothesis function (called h() on the update rule equation) looks like this:

<img src="https://github.com/lopeLH/LogisticRegression/blob/master/LogisticRegression/githubImages/56fc4a24b7084ff8f218aaeb5bfe1c4e.png"  width=184 height=43 />

So the output of the hypothesis function is always somewhere between [0,1]. The output values (labels) of the training set elements
must be inside this range of values too.

In this example you click on the graph to add new points, right clik will create "X"-calss elements and left click will create "O"-class
elements, then use the "fit" button to execute gradient descent and train our model.
