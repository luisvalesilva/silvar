[![Travis-CI Build Status](https://travis-ci.org/hochwagenlab/hwglabr.svg?branch=master)](https://travis-ci.org/hochwagenlab/hwglabr)

# silvar
### My personal R package

Compilation of miscellaneous functions I like to keep at hand.

#### Installation

Install directly from the source code on GitHub. Requires Hadley Wickham's
`devtools` R package:
``` r
install.packages("devtools")
devtools::install_github("luisvalesilva/silvar")
```

#### Docs

Use the package GitHub [repo](https://github.com/luisvalesilva/silvar) and the
[documentation website](http://www.nyu.edu/projects/hochwagen/hwglabr_docs/).
Function documentation is accessible within R in the standard way, by typing one
of the following:

``` r
help("function_name")

?function_name
```

You can also get the list of included functions directly within R using one of the following:

``` r
ls("package:silvar")   # List function names

lsf.str("package:silvar")   # List function names and their arguments
```

---

For a short description of the process of creating an R package, check out my
[blog post](http://luisvalesilva.com/datasimple/r_packages.html) about it.