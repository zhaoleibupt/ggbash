<!-- README.md is generated from README.Rmd. Please edit that file -->
ggbash
======

ggbash is the bash-like environment for ggplot2.

``` r
library(ggbash)

ggbash() # enter into ggbash session
```

``` r
user@host currentDir $ use iris
```

``` r
Observations: 150
Variables: 5
$ Sepal.Length (dbl) 5.1, 4.9, 4.7, 4.6, 5.0, 5.4, 4.6, 5.0, 4.4, 4.9, 5.4, 4.8, ...
$ Sepal.Width  (dbl) 3.5, 3.0, 3.2, 3.1, 3.6, 3.9, 3.4, 3.4, 2.9, 3.1, 3.7, 3.4, ..
$ Petal.Length (dbl) 1.4, 1.4, 1.3, 1.5, 1.4, 1.7, 1.4, 1.5, 1.4, 1.5, 1.5, 1.6, ..
$ Petal.Width  (dbl) 0.2, 0.2, 0.2, 0.2, 0.2, 0.4, 0.3, 0.2, 0.2, 0.1, 0.2, 0.2, ..
$ Species      (fctr) setosa, setosa, setosa, setosa, setosa, setosa, setosa, ...
```

``` r
user@host currentDir (iris) $ point 2 3 color=4
```

``` r
executed: ggplot(dataset) + geom_point(aes(Sepal.Width,Petal.Length))
```
