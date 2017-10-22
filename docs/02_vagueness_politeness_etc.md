## Homework 2: Vagueness & politeness

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

Solutions are due on Friday, October 27th by noon. Please send your solutions as a zipped archive, including a *.webppl file for each exercise with your code and in-code comments to [Michael Franke](mailto:michael.franke@uni-tuebingen.de). Please name the archive `lastName_HW1.zip` and the included files like `lastName_HW1_ex1_partA.webppl`. 

#### Exercise 1: Vagueness

Use the code from the last model in the first section of [Chapter V of the BDAPPL Webbook](https://mhtess.github.io/bdappl/chapters/05-vagueness.html). This model uses the empirically measured priors over prices for various items to calculate the listener's interpretation of *expensive*. We would like to explore the behavior of this model under different values of its parameters. To do so conveniently, extend the code by wrapping (a large part of) the given code in a convenience function called `predictions`. The arguments to a function call of `predictions` should be:

1. the item (as a string)
2. the speaker optimality parameter $$\alpha$$
3. the cost of the utterance *expensive*

For example, a function call to get the predictions for the item `"watch"` with `alpha = 1` and utterance cost `2` for expensive would be `predictions("watch", 1, 2)`.

The output of the `predictions` function should be two plots, the same ones that are shown by the model code as it is in the chapter:

1. listener's posterior marginalized over prices 
2. listener's posterior marginalized over thresholds

Additionally, make sure that calls like `print("the listener's posterior over XXX prices:")` is properly changed so that the correct item name is included.



