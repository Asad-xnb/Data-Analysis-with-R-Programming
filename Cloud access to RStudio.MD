## Activity overview

<hr>

By now, you've learned about RStudio, an integrated development environment that allows you to more efficiently create and manage projects using R. In this activity, you will learn how to access the cloud version of RStudio.

Upon completing this activity, you will be more familiar with the RStudio interface and comfortable using its basic tools. This is a foundational step that will prepare you for upcoming RStudio activities during this course. This hands-on activity, and the future RStudio activities you will complete, are essential to developing job-ready R programming skills.

## Access RStudio Cloud

<hr>

**RStudio Cloud** (now called **Posit Cloud**) is the primary tool you will use for this course. In order to use RStudio Cloud, you need stable internet access. It won't matter what operating system you have because it works in your browser.

You can also install a desktop version, which you can download based on instructions provided in the next (optional) activity. This is a good alternative if you want to be able to work with R offline. 

In order to access RStudio Cloud, follow these steps:

1. Sign up for an account at the [RStudio Cloud Sign-up page](https://posit.cloud/plans/free)

Here, you will find more information about RStudio Cloud, including the pricing plans. You will use the free version, but it does have a few limitations. You can only have up to 15 projects on your free account, and can only use 15 project hours per month. You might consider upgrading later on if you find yourself using RStudio a lot.

2. For now, click the **Sign Up** button on the bottom-right to start with the free version.

3. Input your email, a password, as well as your first and last name. 

4. Once you have signed up, open RStudio Cloud for the first time.

![RStudio Cloud interface](./Images/RStudio%20cloud.jpg)

5. Click **New Project** to create a new project workspace and open the RStudio Cloud console.

![RStudio Cloud panes](./Images/RStudio%20Cloud%20panes.jpg)

## Install and load packages

<hr>

Once you have opened a new project in your console, you can install packages to RStudio Cloud. 

**Packages** are units of reproducible R code. Members of the R community create packages to keep track of the R functions that they write and reuse. Packages offer a helpful combination of code, reusable R funcitons, descriptive documentation, tests for checking your code, and sample data sets.

The lubridate package that you are about to install is the part of the **tidyverse**. The tidyverse is a collection of packages in R with a common design philosophy for data manipulation, exploration, and visualizatio. For a lot of data analysts, the tidyverse is an essential tool. You will learn more about the tidyverse later on.

To install the core tidyverse packages and load them, follow these steps:

1. In the bottom of the console, type **install.packages("tidyverse")** and press **Enter**.

![tidyverse package](./Images/tidyverse.jpg)

This may take a while. You can tell if the process is still running by checking the red **stop** icon in the upper right of the console. You can click this icon to interrupt the running code and cancel the command.

![Stopping any command](./Images/RStudio%20Stop%20Command.jpg)

2. Load the tidyverse library with the **library()** function. To load the core tidyverse, type **library(tidyverse)** and press **Enter**. 

You only need to install a package once, but you need to reload it every time you start a new session.

![library(tidyverse)](./Images/library(tidyverse).jpg)

3. Load the lubridate package. Since this is already part of the tidyverse package, these is no need to re-install. However, the library will need to be loaded. Type **library(lubridate)** into the console pane and press **Enter**.

After you complete these steps, you can exit RStudio. Feel free to explore RStudio Cloud on your own to get more familiar with the tools and practice what you are learning.