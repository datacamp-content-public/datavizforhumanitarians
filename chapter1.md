---
title: Dirty Boxing with qplot
description: >-
  In this chapter we'll teach you how to use qplot to win a fight.  Mastering the ggplot2 language can be overwhelming at first and there is a helper function called qplot() (q for quick plot) which can be used to create the most common types of graphs.  You'll probably be suprised how powerful it is and may be even inspired to go up a weight class later with ggplot.


---
## Ex 1 - Scatter Plot

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: bb3bd2e856
```

A lot of courses start off with the scatter plot.  We're going to do the same even though it might be the least used type of graphic in humanitarian work.  Why are  we starting off with it?  Because it's so easy!  Qplot produces a scatterplot by default when giving an x and a y. 

Let's do a scatterplot using the famous diamonds dataset.

`@instructions`
1.  Explore how a size (carat) affects a diamonds price by creating a  scatterplot on these two variables in the diamonds data set.  Put 

2.  Explore how a diamonds clarity also affects it’s price

Remember the format is:

qplot(x, y, data=, color=, fill=, shape=, size=, alpha=, geom=, method=, formula=, facets=, xlim=, ylim=, xlab=, ylab=, main=, sub=)

`@hint`
did you load the library ggplot?
did specify the correct x and y values in the correct order?
did you specify the correct data frame?
did you specify the correct variable to fill?

`@pre_exercise_code`
```{r}
library(ggplot2)
```
`@sample_code`
```{r}
#load ggplot 

#look at diamonds dataset with str()

#run qplot using price and carat 

#run the same but set the fill to clarity
```
`@solution`
```{r}
library(ggplot2)

qplot(carat, price, data=diamonds)

qplot(carat, price, data=diamonds, fill=clarity)
```
`@sct`
```{r}
success_msg("Awesome! It's considered good style to write spaces either side of the assignment arrow.")
```





---
## Ex 2 - Scatter again with more options

```yaml
type: NormalExercise

xp: 

key: 6c02af1e65
```

Isnt this easy?  We're going to keep the same scatter but play with a couple more options to get you more excited about qplot.

Specifically, we're going to:

1.  add labels to the x and y axis using _xlab_ and _ylab_
2.  change the transparency of the dots by adjusting the _alpha_
3.  instead of using color to represent the clarity, use _alpha_

qplot(x, y, data=, color=, fill=, shape=, size=, alpha=, geom=, method=, formula=, facets=, xlim=, ylim=, xlab=, ylab=, main=, _sub=)_


`@instructions`
Adding to  the code in the last exercise

1.  add labels to the x and y axis using _xlab_ and _ylab_ .  Enter "
2.  change the transparency of the dots by adjusting the _alpha_
3.  instead of using color to represent the clarity, use _alpha_

`@hint`
are you serious?


`@pre_exercise_code`
```{r}
library(ggplot2)
```
`@sample_code`
```{r}
#code from last time
qplot(carat, price, data=diamonds, fill=clarity)

#add labels to the x and y 


#set the alpha to 1


#set shape to clarity
```
`@solution`
```{r}
library(ggplot2)

qplot(carat, price, data=diamonds)

qplot(carat, price, data=diamonds, fill=clarity)
```
`@sct`
```{r}
success_msg("ya boy!")
```








