---
title: Descriptive stats, tables and stuff
description: >-
  maybe this should go first, whatever

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
