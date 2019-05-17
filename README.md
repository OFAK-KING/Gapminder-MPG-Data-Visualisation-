# Gapminder-MPG-Data-Visualisation-
This project uses the Gapminder and MPG dataset to explore the Tidyverse package with the aid of questions in chapter 3 of the Garrett Grolemund and Hadley Wickham' R for Data Science book (https://r4ds.had.co.nz/data-visualisation.html) and beyond. 

We explored Ideas like:

Adjust the number of bins to 2, then 40, then 100, to determine What's a good number bin for the data

Run ggplot(data = mpg). What do you see?

How many rows are in mpg? How many columns?

What does the drv variable describe? Read the help for ?mpg to find out.

Make a scatterplot of hwy vs cyl.

What happens if you make a scatterplot of class vs drv? Why is the plot not useful?

What’s gone wrong with this code? Why are the points not blue?

Which variables in mpg are categorical? Which variables are continuous? (Hint: type ?mpg to read the documentation for the dataset). How can you see this information when you run mpg?

Map a continuous variable to color, size, and shape. How do these aesthetics behave differently for categorical vs. continuous variables?

What happens if you map the same variable to multiple aesthetics?

What does the stroke aesthetic do? What shapes does it work with? (Hint: use ?geom_point)

What happens if you facet on a continuous variable?

What do the empty cells in plot with facet_grid(drv ~ cyl) mean? How do they relate to this plot?

What plots does the following code make? What does . do?

What are the advantages to using faceting instead of the colour aesthetic? What are the disadvantages? How might the balance change if you had a larger dataset?

Read ?facet_wrap. What does nrow do? What does ncol do? What other options control the layout of the individual panels? Why doesn’t facet_grid() have nrow and ncol arguments?

When using facet_grid() you should usually put the variable with more unique levels in the columns. Why?

What geom would you use to draw a line chart? A boxplot? A histogram? An area chart?

Run this code in your head and predict what the output will look like. Then, run the code in R and check your predictions.

What does show.legend = FALSE do? What happens if you remove it?
Why do you think I used it earlier in the chapter?

What does the se argument to geom_smooth() do?

Will these two graphs look different? Why/why not?

Recreate the R code necessary to generate the following graphs.

What is the problem with this plot? How could you improve it?

What parameters to geom_jitter() control the amount of jittering?
