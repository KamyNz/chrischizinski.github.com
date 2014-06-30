Multiple plots in ggplot2
========================================================

The RMarkdown source to this file can be found [here](\Rmd\22014-04-28-multiple-plots.Rmd)

As I have mentioned previously is that I use ggplots a ton in my work.  It is my goto for plotting in R and I have really loved the ease of plotting with this package.  One thing that can see kind of tricky is plotting multiple panels in a single figure.   There are a couple of different ways to do this using **ggplot2** and the **gridExtra** packages.  

### ggplot2 and facet_wrap
Within **ggplot2** there is [`facet_wrap`](http://docs.ggplot2.org/0.9.3.1/facet_wrap.html) which will allow you to create multiple panels by a variable with a single line of code.  


