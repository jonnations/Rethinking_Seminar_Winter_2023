# Rethinking Seminar Winter 2023

This is the GitHub repository for the GeoSci Seminar in Winter 2023 led by Mark Webster

## Information

## Resources

Here are a few resources I (Jon) find indispensable when working with Bayesian multilevel models:

- [brms R package website](https://paul-buerkner.github.io/brms/)
  + brms is an all-in-one Stan interface for Bayesian regression modeling that uses a simple syntax and is incredibly powerful and user friendly. Vignettes, Functions, etc. can be found here.<br>
<br>

- [Statistical Rethinking v.2 with `brms`, `ggplot`, and the `tidyverse`](https://bookdown.org/content/4857/)
  + This is undoubtedly the most useful tool for my forrays into modeling. [@SolomonKurz](https://twitter.com/SolomonKurz?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor) goes chapter by chapter though Statistical Rethinking v.2 and works out all of the models in `brms`, generates all of the figures in [`ggplot`](https://ggplot2.tidyverse.org/), and does all the data wrangling in the [`tidyverse`](https://www.tidyverse.org/). (*Note: if you are not wedded to a data formatting methodology like base R or `pandas`, check out the tidyverse sooner rather than later*.) Plus there are some tidbits throughout the text that really take it to the next level, such as using great color palettes, using [patchwork](https://patchwork.data-imaginist.com/) for plot layouts, and excellent bonus sections like this one on [different ways to model categorical predictor variables](https://bookdown.org/content/4857/the-many-variables-the-spurious-waffles.html#summary-bonus-we-can-model-categorical-variables-in-more-ways-than-one)<br>
<br>

- [Probability Distribution Applet](https://homepage.divms.uiowa.edu/~mbognar/) 
  + What does an Exponential Distribution with a $\lambda$ of 3 look like? How thick are the tails on a Student-$T$ with a $\nu$ parameter of 4? Do I use a Poisson on Negative-Binomial Distribution for these count data? This applet makes visualizing continuous distributions really easy. There is a mobile app too.<br>
<br>

- [tidybayes](http://mjskay.github.io/tidybayes/articles/tidy-brms.html)
  + An excellent tidy way to extract draws, predictions, and plot uncertainty for Bayesian models.<br>
<br>

- [Stan Discourse Forum](https://discourse.mc-stan.org/)
  + ****First place to check for any questions regarding Stan, brms, and Rethinking.*** Topics range from OS issues ("R not compiling my models properly") to conceptual topics to new features or methods.  



