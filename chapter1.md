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

A lot of  courses start off with the scatter plot.  We're going to do the same  even though it might be the least used type of graphic in humanitarian work.  Why are  we starting off with it?  Because it's so easy!  Qplot plot produces a scatter by default when giving an x and a y. 

Let's do a scatterplot of the diamonds data set using the famous diamonds dataset.

`@instructions`
1.  Explore how a size (carat) affects a diamonds price by creating a  scatterplot on these two variables in the diamonds data set.  Put 

2.  Explore how a diamonds clarity also a

Remember the format is:

qplot(x, y, data=, color=, fill=, shape=, size=, alpha=, geom=, method=, formula=, facets=, xlim=, ylim=, xlab=, ylab=, main=, sub=)

`@hint`
did you load the library ggplot?
did specify the correct x and y values in the correct order?
did you specify the correct data frame?
did you specify the correct variable to fill?


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





