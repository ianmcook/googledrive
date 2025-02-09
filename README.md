
<!-- README.md is generated from README.Rmd. Please edit that file -->

# googledrive <img src="man/figures/logo.png" align="right" height=140/>

[![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/googledrive)](https://cran.r-project.org/package=googledrive)
[![Build
Status](https://travis-ci.org/tidyverse/googledrive.svg?branch=master)](https://travis-ci.org/tidyverse/googledrive)[![AppVeyor
Build
Status](https://ci.appveyor.com/api/projects/status/github/tidyverse/googledrive?branch=master&svg=true)](https://ci.appveyor.com/project/tidyverse/googledrive)[![codecov](https://codecov.io/gh/tidyverse/googledrive/branch/master/graph/badge.svg)](https://codecov.io/gh/tidyverse/googledrive?branch=master)

## Overview

googledrive allows you to interact with files on Google Drive from R.

## Installation

Install the CRAN version:

``` r
install.packages("googledrive")
```

Or install the development version from GitHub:

``` r
# install.packages("devtools")
devtools::install_github("tidyverse/googledrive")
```

## Usage

Please see the package website:
<https://tidyverse.github.io/googledrive/>

Here’s a teaser that uses googledrive to view some of the files you see
on <https://drive.google.com> (up to `n_max = 25`, in this case):

``` r
library("googledrive")
drive_find(n_max = 25)
#> # A tibble: 13 x 3
#>    name                id                                drive_resource
#>  * <chr>               <chr>                             <list>        
#>  1 googledrive-NEWS.md 15pfwRfXvpxekxhdERmSUnoxQY5K701y7 <list [38]>   
#>  2 def                 1hr4EFw3r5vAMm5Jgw2SsFluBpN-oAC-x <list [32]>   
#>  3 abc                 11lidFPceZAcNTHasQARiwAhE0NgmSfJN <list [32]>   
#>  4 THANKS              1zNZpVO4MCjNUFUHOwSv3WlyUh4Dq_du3 <list [39]>   
#>  5 BioC_mirrors.csv    1vV0fPdNOyo3Ti9ofA38MuTQm27pXvYq5 <list [38]>   
#>  6 logo.jpg            1OFeNdd63NfoavqvDf5-xa3LORiamfKXS <list [40]>   
#>  7 Rlogo.svg           11sxsw-ux-UjQjzVdxd1wjNz37hJeBrBu <list [40]>   
#>  8 Rlogo.pdf           1cn7oVxQRgD0l_hCI4nrSSWrKeVFysUp7 <list [39]>   
#>  9 DESCRIPTION         1MjV4stVPhlMNz1AcrIizcL7yTcVaRuBo <list [39]>   
#> 10 chicken.txt         1xmwFZ_UN-CSs3Ic2aPUw22DbxZxoenVT <list [39]>   
#> 11 chicken.pdf         1eK9ozP1TZjXfAgaAGmP9GrUTovGUaO9S <list [39]>   
#> 12 chicken.jpg         1JnGjIdruQXErd20xR_ecAzN3yP_fTcfF <list [40]>   
#> 13 chicken.csv         1eHoOi9Ch3zk3_QBRKCJajFEIO4aeGINr <list [38]>
```

## Contributing

If you’d like to contribute to the development of googledrive, please
read [these guidelines](.github/CONTRIBUTING.md).

Please note that the googledrive project is released with a [Contributor
Code of Conduct](.github/CODE_OF_CONDUCT.md). By contributing to this
project, you agree to abide by its terms.
