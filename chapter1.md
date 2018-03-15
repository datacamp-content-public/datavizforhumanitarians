---
title: Dirty Boxing with qplot
description: >-
  In this chapter we'll teach you how to use qplot to win a fight.  Mastering the ggplot2 language can be overwhelming at first and there is a helper function called qplot() (q for quick plot) which can be used to create the most common types of graphs.  You'll probably be suprised how powerful it is and may be even inspired to go up a weight class later with ggplot.






---
## Playing a video

```yaml
type: VideoExercise
lang: r
xp: 50
skills: 1
key: 78e4bc56dc
```

`@projector_key`
undefined





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
run a scatterplot on the diamonds data

`@hint`
did you load the library ggplot2?
did specify the correct x and y values?
did specify the correct data frame?


`@pre_exercise_code`
```{r}

```

`@sample_code`
```{r}

```

`@solution`
```{r}
library(ggplot2)

str(diamonds)

qplot(carat, price, data=diamonds)
```

`@sct`
```{r}

```
