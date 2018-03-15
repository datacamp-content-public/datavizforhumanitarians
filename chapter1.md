---
title: Dirty Boxing with qplot - checking to see if I can change this.
description: >-
  In this chapter we'll teach you how to use qplot to win a fight.  Mastering the ggplot2 language can be overwhelming at first and there is a helper function called qplot() (q for quick plot) which can be used to create the most common types of graphs.  You'll probably be suprised how powerful it is and may be even inspired to go up a weight class later with ggplot.


## Exercise 1 - Scatter Plot - oooooh.

```yaml
type: NormalExercise
lang: r
xp: 100
skills: 1
key: 8a04d1ed04
```

A lot of  courses start off teaching the scatter plot even though it might be the least used in humanitarian work.  Why then are we starting off with it?  Because it's so easy.  By default when you give a x and y to qplot, it will produce a scatter.

Let's do a scatterplot of the diamonds data set using the famous diamonds dataset.


`@instructions`
run a scatterplot of 

`@hint`
did you load the library

`@pre_exercise_code`
```{r}
y <- 3
```

`@sample_code`
```{r}
# Assign 5 to the variable x
```

`@solution`
```{r}
# Assign 5 to the variable x
x <- 5
```

`@sct`
```{r}
test_error()
test_object("x",
            undefined_msg = "Make sure to define `x`!",
            incorrect_msg = "Have you correctly assigned 5 to `x`!")
success_msg("Awesome! It's considered good style to write spaces either side of the assignment arrow.")
```







