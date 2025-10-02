# Report


## Iris

Iris table

``` r
library(tidyverse)
count(iris, Species)
```

         Species  n
    1     setosa 50
    2 versicolor 50
    3  virginica 50

table

``` r
library(knitr)
count(iris, Species)
```

         Species  n
    1     setosa 50
    2 versicolor 50
    3  virginica 50

ggplot

``` r
ggplot(iris, aes(Species, Sepal.Length)) +
  geom_boxplot()
```

![](README_files/figure-commonmark/unnamed-chunk-3-1.png)
