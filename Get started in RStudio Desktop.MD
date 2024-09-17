## Activity Overview

<hr>

In earlier activities, you explored programming with R and may have downloaded R to your computer. You also set up cloud access to RStudio, an integrated development environment for programming in R. In this activity, you will download RStudio Desktop -- the offline version of RStudio -- to your computer.

By the end of this activity, you will be able to use RStudio Desktop on your computer. This will give you more flexibility while programming with R, as you will be able to access everything RStudio has to offer even if you are not connected to internet.

## Download RStudio Desktop
<hr>

RStudio allows you to create and manage projects using R more efficiently. You can find more information about RStudio Desktop on the [RStudio Website](https://rstudio.com/). It is available to download with the open source edition, so it is free to use under a public license. The free trial of RStudio Pro, which has all of the features of the open source edition and a commercial license, is also on this website.

1. Determine which operating system (OS) you have on your computer. 
2. If you haven't already, install R onto your computer. You can find links to download R for Mac, Windows, and Linux on the [CRAN website](https://cran.rstudio.com/). For more information.

3. Once you have installed R, go to the [RStudio Desktop download page](https://posit.co/download/rstudio-desktop/#download)

![RStudio Desktop download page](./Images/RStudio%20desktop%20download%20page.jpg)

4. Download the appropriate RStudio Desktop installer for your operating system.

5. Once you have downloaded the installer, open it and install **RStudio**.

6. After installation, open the application for the first time. You should find the RStudio console you are already familiar with -- but now you can access it locally.

## Install and load packages
<hr>

You can install and load packages in your RStudio Desktop console, just like you did for RStudio Cloud. Now, you will install and load the lubridate package in the tidyverse. 

As a refresher, the tidyverse is a collection of packages in R with a common design philosophy for data manipulation, exploration, and visualization. For a lot of data analysts, the tidyverse is an essential tool. 

1. To install the core tidyverse packages, type **install.package("tidyverse")** into the RStudio console pane and click **Run**.
2. Load the tidyverse library with the **library()** function. Type library(tidyverse) into the console pane and click **Run**. 

You only need to install a package once, but you need to reload it every time you start a new session.

3. Load the [lubridate](https://lubridate.tidyverse.org/) package. Type **library(lubridate)** into the console pane and click Run.