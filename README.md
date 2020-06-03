# MRCHANGE

A [workflowr][] project. [workflowr]: https://github.com/jdblischak/workflowr

To run the analysis, download the project, open analysis/index.Rmd in RStudio, and either Run the Code or Knit the Project

To update: 

* wflow_build()

Ensure that all data are pushed to the repository (i.e., for subject 1114):

* wflow_publish(c("analysis/*Rmd","data/*csv", "data/s1114/*dat"), message ="Update data") 

Then push to GitHub

* wflow_git_push()
