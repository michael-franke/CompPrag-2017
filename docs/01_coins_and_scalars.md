## Homework 1: Coins & scalars

<script src="https://cdnjs.cloudflare.com/ajax/libs/KaTeX/0.8.3/katex.min.js" integrity="sha384-L9gv4ooDLrYwW0QCM6zY3EKSSPrsuUncpx26+erN0pJX4wv1B1FzVW1SvpcJPx/8" crossorigin="anonymous"></script>

Solutions are due on Friday, October 20th by noon. Please send your solutions as a zipped archive, including two *.webppl files with your code and in-code comments to [Michael Franke](mailto:michael.franke@uni-tuebingen.de). Please name the archive `lastName_HW1.zip` and the included files `lastName_HW1_ex1.webppl` and `lastName_HW1_ex2.webppl`. 

#### Exercise 1: Coin flips

Use the code from [Chapter II from MH Tesslers BDAPPL Webbook](https://mhtess.github.io/bdappl/chapters/02-buildingModels.html) to calculate your rational beliefs about the bias of a coin. Suppose that your prior beliefs about the coin's bias $$\theta$$ are given by a Beta distribution with parameters $a = 0.5$ and $b = 0.5$. In WebPPL, you can construct this distribution by:

```js
var priorDistribution = Beta({a: 0.5, b: 0.5})
```
