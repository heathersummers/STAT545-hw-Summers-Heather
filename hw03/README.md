
## STAT545 Homework 03
[Return to Main Page](https://github.com/heathersummers/STAT545-hw-Summers-Heather)

This folder contains homework assignment #3 for Heather Summers.

For the completed homework 03 please see the [Markdown file](https://github.com/heathersummers/STAT545-hw-Summers-Heather/blob/master/hw03/hw03.md) and the [R Markdown file]https://github.com/heathersummers/STAT545-hw-Summers-Heather/blob/master/hw03/hw03.Rmd). Also a link to the instructions for this assignment can be found on the [STAT545 Website](http://stat545.com/hw03_dplyr-and-more-ggplot2.html).

### Useful Links:
- [Document on knitr](https://yihui.name/knitr/)

- [ggplot2 cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/03/ggplot2-cheatsheet.pdf)

- [ggplot2 themes](http://ggplot2.tidyverse.org/reference/ggtheme.html)

- [ggplot2 scales, axes, and legends](https://github.com/hadley/ggplot2-book/blob/master/scales.rmd)

### Report Your Process:
One aspect I found very challenging was for the first task I wanted to create a bar plot with continent on the x-axis and GDP per capita on the y-axis and then have bar plots of the minimum and maximum GDP per capita for each continent side-by-side on the graph. However, I was unable to make the graph using the class notes or Jenny's dplyr tutorial so after searching blogs online I found you could make the figure using the package `reshape2`. I found this [blog](https://stackoverflow.com/questions/22305023/how-to-get-a-barplot-with-several-variables-side-by-side-grouped-by-a-factor) particularly helpful in creating the figure. Another challenge I encountered during this assignment was creating my final figure of the relative number of countries with a low life expectancy since I was having trouble connecting the information and commands I had created for the table with the figure. Through trial and error I found out that because I had renamed the column names in the table to make them easier to understand, the variables were not being recognized in the code I had done for the figure. I found the following [link](https://stackoverflow.com/questions/13090838/r-markdown-avoiding-package-loading-messages) which I learned about while reviewing another student's assignment to be particularly helpful at hiding the results, messages, and warnings that come up when loading packages in R Markdown. Lastly, I found the class notes, [ggplot2 themes](http://ggplot2.tidyverse.org/reference/ggtheme.html), and [ggplot2 scales, axes, and legends](https://github.com/hadley/ggplot2-book/blob/master/scales.rmd) particularly helpful in incorporating functions related to theme, axes titles, colours, legends, etc. 
