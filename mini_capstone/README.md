# Week 4 instructions

## Pre-assignment 1: choose a dataset
This can be anything*! I recommend using a dataset you collected or are working with for research or a class project. If you need inspiration I can give you any number of cool surface processes datasets! 

(*)Well, ok, not anything - the only requirement is a dataset that contains at least one column of numerical data (better if it's two, see below). This activity will be more fun and intuitive if it is a ["wide"](https://en.wikipedia.org/wiki/Wide_and_narrow_data) dataset, and the wider the better!

## Pre-assignment 2: get inspired with an example
I have included an example of my attempt at re-creating a figure from a publication using data supplied in the supplement (which is sometimes very difficult or impossible if the authors are bad at sharing their data; more on that later) with `mini_capstone_example.ipynb`. You can see that, though it takes a little time and coding, you can (1) load data, (2) "clean" it (eliminate errant symbols and correct data types), and (3) plot it nicely just like in the paper! 

## Tips before you start
Plan it out: take a few minutes to envision what your “perfect plot” would look like. What data are on the X and Y axes? Would this data best be shown as a scatterplot? Line plot? Bar plot? Try sketching out the ideal plot, and use symbols or different shading to denote colors and symbols that might change with data properties. 

Now, work backwards from here to figure out how you will construct this plot using the tools you’ve learned so far. Will you have one dataset on one axis object? Two plots on one axis? Two axes? Will you need to specify a c-axis? 

Once you’ve worked through the logical planning of the plot mechanics, now it’s time to think of any tasks related to the data itself. Do you need to perform any transformations to the raw data to achieve those results? Calculations? Unit conversions? Statistical analyses? Maybe you have many datasets and you’d rather plot the mean of each population against another variable – how might you go about doing that, and in what order? These are all aspects of data reduction, which is just the fancy term for going from raw data to a plot that a non-expert might understand, or that tells a specific story about your data. 


## Deliverable for Week 4

You will be responsible for creating an <b>informative</b> and <b>publication-worthy</b> plot of a dataset special to you. Your steps are to:
1. load a dataset that contains at least one column of numerical data from a `.csv` or `.txt` file into `pandas` (or, if you are feeling adventurous, use data from an online repository and download from the URL)
2. perform any data "cleaning" (convert strings to numbers, replace symbols or weird numbers with `np.nan`, etc.) using scripting*
3. perform at least one calculation on at least one column of numerical data (e.g. bare minimum is converting temperatures in F to C)
4. use `matplotlib` and/or `pandas` built-in plotting to make a plot where data are displayed on not just the x and y axes but an additional data layer in the form of symbol color (`c` axis), size, shape, etc. My hint for you here is to use a dataset with at least two numerical columns such that a scatterplot of the primary relationship is made with a secondary relationship acting as the `c` axis. 

Please turn in a <b>zipped folder</b> containing <b>both</b> the dataset and the `.ipynb` file used to create your figure (unless using a URL). 

(*)I challenge you to do as much as possible with code instead of "by hand" in Excel etc., but I understand if it's easier to clean your data in Excel when you are just learning. I trust you to make the call that's right for you!