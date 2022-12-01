# Group 9 Vignette - Binary Classification Bootstrap
Created as a the final module assignment for Group 9 of PSTAT 197A in Fall 2022, this is the template repository for a vignette on binary classification bootstrapping using student mental health data.


## Contributors:

-  *Luke Fields*
-  *Thomas Shi*
-  *Lily Li*
-  *Dingan Jiang*

## Abstract:

What we will be doing is taking many bootstrap samples from a dataset comprised of student mental health conditions, and then running individual machine learning models on each bootstrap sample to get a confidence interval of the accuracy. Our dataset is only about 100 observations, so taking bootstrap samples can help us better understand a certain estimate with more confidence; in this case the accuracy of our boosted tree model we implement to each 1000 bootstrap sample. 

## Repository Contents:

-   `data` contains responses to a survey conducted by a University student to examine the mental health conditions of students in college, one file is raw and one is cleaned 
-   `scripts` contains the R markdown files that we all worked on to perform data cleaning, exploratory data analysis, different, model building, bootstrap function, and results analysis that we then turned into the final product
-   `results` contains a template called `Vignette-Group9.qmd` that summarizes our findings in a QMD file for other students to use when they are curious about bootstrapping methods
-   `img` contains the images we use to visualize our findings

## Reference List:

-  https://www.tidymodels.org/learn/statistics/bootstrap/
-  https://link.springer.com/article/10.1007/s13278-021-00760-0
