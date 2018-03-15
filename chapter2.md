title: trying this out again

Exercise 1 - Scatter Plot - oooooh.
type: NormalExercise
lang: r
xp: 100
skills: 1
key: 8a04d1ed04
A lot of courses start off teaching the scatter plot even though it might be the least used in humanitarian work. Why then are we starting off with it? Because it's so easy. By default when you give a x and y to qplot, it will produce a scatter.

Let's do a scatterplot of the diamonds data set using the famous diamonds dataset.

@instructions run a scatterplot of

@hint did you load the library

@pre_exercise_code

y <- 3
@sample_code

# Assign 5 to the variable x
@solution

# Assign 5 to the variable x
x <- 5
@sct

test_error()
test_object("x",
            undefined_msg = "Make sure to define `x`!",
            incorrect_msg = "Have you correctly assigned 5 to `x`!")
success_msg("Awesome! It's considered good style to write spaces either side of the assignment arrow.")
