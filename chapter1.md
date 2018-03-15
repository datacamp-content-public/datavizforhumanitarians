

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

A lot of  courses start off teaching the scatter plot even though it might be the least used in humanitarian work.  Why then are we starting off with it?  Because it's so easy.  By default when you give a x and y to qplot, it will produce a scatter.

Let's do a scatterplot of the diamonds data set using the famous diamonds dataset.

`@instructions`
Explore the how a size (carat) affects a diamons price. run a scatterplot on these two variables in the diamonds data set.

`@hint`
did you load the library ggplot
did specify the correct x and y values in the correct order?
did you speciy the correct data frame

`@solution`
```{r}
library(ggplot2)

str(diamonds)

qplot(carat, price, data=diamonds)

```

`@sct`
```{r}

```



