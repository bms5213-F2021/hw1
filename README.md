# Homework 1

* Due: 10/26/2021, 6pm CDT
* Work within the repo "https://github.com/bms5213-F2021/hw1-ind-yourgithubusername" and upload your finished assignment there.
* Please read the paper [Characterizing mutagenic effects of recombination through a sequence-level genetic map](https://raw.githubusercontent.com/bms5213-F2021/bms5213-F2021.github.io/master/docs/resourcedev/papers/dnm_halldorsson.pdf)
* The 10/19/2021 lecture will cover enough material only for Questions 1 and 2 and enough to start Questions 5 and 6.


## Question 1 (0.5 pts)

Briefly provide a one paragraph summary of the Halldorsson et al paper, making sure to highlight what you think the main analytic question was and please interpret the result.

## Question 2 (1 pt)

For each of the data analytic question types ((A) Descriptive, (B) Exploratory, (C) Inferential, (D) Predictive, (E) Causal, or (F) Mechanistic), provide an example of a data analytic question that Halldorsson et al asked or could have asked with their data. If they did ask the question, please reference the location in the paper pertaining to your answer. If you don't think their data could be used to formulate such a question, please provide what would be the ideal additional data along with your formulated question.

## Question 3 (0.5 pts)

* What type/category of data is the whole genome sequencing (WGS) data that was collected for the paper?
* What type(s) of data is(are) presented in Figure 2B?
* What type(s) of data is(are) presented in Figure 2D?

## Question 4 (0.5 pts)

Imagine that we as a course decide to collect data on the amount of coffee that is consumed daily by adults in Nashville, wishing solely to ask an Exploratory question.

1. Suppose we set up a booth in the middle of the Lipscomb campus and have a large sign with a picture of a travel coffee mug. Respondents then voluntarily approach us and we ask them how many cups of coffee they consume daily as well as a few demographic questions.
  * Do you think the data analytic question is specific enough given the proposed sampling scheme? If not, how would you increase the specificity of the question?
  * What biases will result from the proposed question and sampling scheme?
2. Propose a data sampling approach that minimizes biases in the data and better matches the stated question. Are there any biases you can't eliminate?

## Question 5 -- Summary Statistics in R (0.75 pts)

Using the tidied data `dnm_by_age_tidy_Halldorsson.csv`, find and report summary statistics for each of the last 5 columns/variables. The absolute minimum set of summary stats which you should find include the range, the average, the variance, the standard deviation, and the median. If the average and the median differ, why do they differ?  

You can read the data into R using the following line of code:

```
dnm_data <- read.csv("https://raw.githubusercontent.com/bms5213-F2021/bms5213-F2021.github.io/master/docs/resourcedev/tidy_data/dnm_by_age_tidy_Halldorsson.csv")
```  

## Question 6 -- R Plotting Practice (0.75 pts)


Again, using the tidied data `dnm_by_age_tidy_Halldorsson.csv`, explore the provided data, making 5 plots of your choice. (However, please vary the type of plot such that not all 5 plots are histograms). For each plot, describe what your goal was and what you observe in the plot.

Note: Make sure to include your R code, your plots, and your comments/observations in what you upload to your repository.
