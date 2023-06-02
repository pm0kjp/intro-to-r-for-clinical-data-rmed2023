# Intro to R for Clinical Data: R/Medicine 2023

This is the GitHub repository for the R/Medicine 2022 pre-conference workshop R/Medicine 101: Intro to R for Clinical Data.  This repository contains the files you need to be able to complete the exercises in the workshop.  Exercises for you to complete are in the [exercises](exercises) folder, and working solutions files are found in [solutions](solutions).

## Where to do the exercises

### Use Posit.cloud

The easiest way to do the workshop exercises is to create a free account at <https://posit.cloud> and then go to <https://posit.cloud/content/6050527> and make your own permanent copy of this project so you can make changes and work with it later.

### Use Your Own R/RStudio

If you want, you can install R and RStudio Desktop for free on your computer, following the instructions at <https://posit.co/download/rstudio-desktop/>.  Then you can either:

* Use File > New Project to create a new project from version control and add the URL of this repository (namely, https://github.com/pm0kjp/intro-to-r-for-clinical-data-rmed2023)
* Download the files in this repository (the green "Code" button will allow you to download a zip file of this repository's contents) and then use File > New Project > Existing Directory to create an R project in the directory where you stashed those files.

## Dependencies

The files here depend on several R libraries, which you can install using the following command:

```r
install.packages(c(
  "tidyverse",
  "rmarkdown",
  "flexdashboard",
  "plotly",
  "DT"
))
```

Slides of the teaching presentation that accompany the workshop are available at <https://joy-payton-chop.quarto.pub/r-101-rmed-2023> and are version controlled in a different repository, at <https://github.com/pm0kjp/r-101-rmed-2023>.



## License

All of the material in this GitHub repository is copyrighted under the [Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) copyright to make the material easy to reuse. We encourage you to reuse it and adapt it for your own teaching as you like!
