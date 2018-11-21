
<img src="figures/logo.png" height=140/> <br>

<br/>
<br/>

Please visit [here][here] for the shiny gapminderplus datasetset or altenatively copy and paste the link below in your browser of choice. The accompanying packages can be downloaded via instruction below.

```
https://zeeva85.shinyapps.io/gpmd/
```

[here]: https://zeeva85.shinyapps.io/gpmd/    

> The accompanying gapminder package can be downloaded via instruction below.

------

<img src="figures/logo1.png" align="right" height=140/>

gapminderplus
=============

This is an R package that has extended the gapminder dataset. This package also has included a simple `subset_country()` function which returns the mini dataset that was required for as many countries possible.

Installation
------------

You can install gapminderplus from github with:

``` r
# install.packages("devtools")
devtools::install_github("zeeva85/gapminderplus")
```

Example
-------

``` r
library(gapminderplus)


head(gapminder2)
       country continent year lifeExp      pop gdpPercap meanSchool
 1 Afghanistan      Asia 1972  36.088 13079460  739.9811        1.1
 2 Afghanistan      Asia 1977  38.438 14880372  786.1134        1.4
 3 Afghanistan      Asia 1982  39.854 12881816  978.0114        1.8
 4 Afghanistan      Asia 1987  40.822 13867957  852.3959        2.1
 5 Afghanistan      Asia 1992  41.674 16317921  649.3414        2.3
 6 Afghanistan      Asia 1997  41.763 22227415  635.3414        2.6

tail(gapminder3)
     country continent year lifeExp      pop gdpPercap meanSchool infantMortality
519   Zambia    Africa 2002  39.193 10595811 1071.6139        7.9            86.5
520   Zambia    Africa 2007  42.384 11746035 1271.2116        8.0            61.3
521 Zimbabwe    Africa 1992  60.377 10704340  693.4208        8.4            54.5
522 Zimbabwe    Africa 1997  46.809 11404948  792.4500        9.0            62.7
523 Zimbabwe    Africa 2002  39.989 11926563  672.0386        9.6            62.7
524 Zimbabwe    Africa 2007  43.487 12311143  469.7093       10.0            59.9

......
