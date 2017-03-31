# R Introduction with RStudio

Today's tutorial has three stages:

1. __Download__ then install R and RStudio; download the tutorial files
1. __RStudio__: run R commands; create Rmarkdown reports
1. __R commands and libraries__: learn to use the essential basics

Stage 1: __Downloads__

1. Create a single directory for today's material (that you can easily find)
1. Download all of the files from https://github.com/data-space/r-intro 
1. Copy all of these files (from your Downloads directory) into the directory you created
1. Download then install R: 
    - [Download R for Windows](https://cran.rstudio.com/bin/windows/base/R-3.3.3-win.exe) 
      (direct download, Windows XP and higher)
    - [Download R for Mac](https://cran.rstudio.com/bin/macosx/R-3.3.3.pkg) 
      (direct download, Mac OS X 10.9 and higher)
    - [Download R for Linux](https://cran.rstudio.com/bin/linux/)
    - You can go to https://cran.rstudio.com to download R for any operating system
1. Dowload then install RStudio
    - Download: https://www.rstudio.com/products/rstudio/download/ 
    - Select the link under "Installers" that matches your operating system

Stage 2: __RStudio__

1. Run RStudio
1. Select _Global Options..._ from the _Tools_ menu, then select each of these icons:
    - _Appearance_: choose your favorite theme
    - _Pane Layout_: notice the location of the _source_ and _console_ panes
    - _Sweave_: Select `knitr` after "Weave Rnw files using: "
1. Find the _Console_ pane and the console prompt "`> `". At the "`> `" prompt:
    - Type: `c(4,5,6)` (and hit the __return__ key)
    - Type: `x = c('Analytics', 'Without', 'Borders')`
    - Type: `x`
    - Type: `x[1]`
1. Click on `New Project` in the upper right hand corner
    - Select `Existing Directory` 
    - Select `Browse` and find the directory where you place the tutorial files
1. Find the _Files_ pane:
    - Navigate, using the `...` button, to the directory where you stored the tutorial files
    - Now select `Set As Working Directory` from the `More` mini-menu
    - Now click on the `README.md` file
1. Find the _pane:
    
Stage 3: __R commands and libraries__