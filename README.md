# Welcome to our crane app!

This app displays variation in sandhill crane distribution over seasons and years. If you wish to view the app online, it is accessible here:
  
  https://pheasant.shinyapps.io/craneGame/
  
  If you would like to download the code and work with it in R, check out [this link.](https://drive.google.com/drive/folders/1Quq8jMe42JD-6L2XY4xC3P1bcjvCtGGq?usp=sharing) 

If you would like to run the app from github, we'll need a few R packages. Make sure that you have them installed before we proceed:

```{r}

install.packages(c(shiny, shinyWidgets, leaflet, maps, tidyverse, lubridate))
```
Once you have all the packages installed, simply run these lines in the RStudio Console or from a script. It will download the app and display it in a browser window:


```{r}

library(shiny)
runGitHub(rep = "cranes", username = "lsw5077", ref = "main")

```


