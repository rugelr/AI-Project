# AI-Project

## To set up Jupyter Notebook for R
1. Install [R](https://cran.r-project.org/bin/windows/base) & [RStudio](https://rstudio.com/products/rstudio/download).
1. Open RStudio.
1. Open command prompt.
1. Open an R terminal with `R`.
1. Run `install.packages(c('repr', 'IRdisplay', 'evaluate', 'crayon', 'pbdZMQ', 'devtools', 'uuid', 'digest'))`. This command will prompt you to select a CRAN mirror. Any one is fine.
1. Open RStudio.
1. In the console (bottom left pane), run `install.packages('ldavis', 'C:/Users/[username]/Anaconda3')`. Note: replace `C:/Users/[username]/Anaconda3` with where you have Anaconda installed.
1. Jupyter is now ready! Run `jupyter notebook` from the command prompt & a new tab should open in your browser. Navigate to where the .ipynb file is saved & it should open once clicked on.
