[MetaMapR](http://spark.rstudio.com/dgrapov/MetaMapR/) 
========

## A metabolomic network mapping tool 
![demo](Manual/metamapr long.gif.gif)

### Installation
Requires [R](http://cran.us.r-project.org/) and [Shiny](https://github.com/rstudio/shiny-server). 
Try it out using the [Shiny glimmer server](http://spark.rstudio.com/dgrapov/MetaMapR/) 
or run locally by pasting the following code into the R console:
 ```r
library(shiny)
shiny::runGitHub('MetaMapR','dgrapov')
 ```
Alternatively download the .zip file, unzip and run the following code (example for file on desktop)
```r
library(shiny)
shiny::runApp('~/../Desktop/MetaMapR-master/MetaMapR-master')
```
NOTE: modify file paths for OSX and LINUX 

### Instructions
* [Tutorial](http://ufpr.dl.sourceforge.net/project/metamapr/Metmapr%20v1.2.1%20tutorial%20v1.doc.pdf) (a more detailed version coming soon)
* [Examples](http://dgrapov.github.io/MetaMapR/)

### Information
Version: MetaMapR (v1.2.1) released 02/24/14

License: GNU General Public License (v3), [read more](https://github.com/dgrapov/MetaMapR/blob/master/LICENSE)

### TODO
* fix double translations bug
* add hashing for various edgelist to speed filtering

