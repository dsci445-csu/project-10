# project-10
Class project for group 10 in DSCI445 @ CSU

# Reproduce

We initially did our work in 'code.Rmd', 'code2_Nat.Rmd', 'predictions.Rmd', 'predictions2.rmd', and several other files that now reside in the folder 'oldfiles'. We copy and pasted that code into slides.Rmd and paper.Rmd as they were needed. All necessary code now resides in slides.Rmd and paper.Rmd. You can look at the other files if you're curious, but some of them are kind of a mess, since for some reason some of us added new files to the repo instead of just editing the files that were already there, but it's whatever.

To reproduce our presentation slides, knit slides.Rmd to a PDF.

To reproduce our paper, knit paper.Rmd to a PDF. 

Your local R installation will need to have the following packages:

+ ggplot2
+ readr
+ leaps
+ glmnet
+ car
+ pls
+ dplyr
+ knitr 
+ skimr
+ ggpubr
+ boot 
+ ISLR
+ gbm
+ caret
+ zoo
+ splines
+ modelr
+ GGally
+ MASS
+ rpart
+ tree

Frankly I'm not sure how each of these is used, but they are in the code for the slides. Rstudio should automatically prompt you to install missing dependencies.
