As_test_code.R
================
ammarahsattar
2022-07-25

``` r
df <- data.frame(installed.packages())

df
```

    ##                     Package
    ## askpass             askpass
    ## aws.s3               aws.s3
    ## aws.signature aws.signature
    ## base                   base
    ## base64enc         base64enc
    ## bit                     bit
    ## bit64                 bit64
    ## blob                   blob
    ## boot                   boot
    ## brew                   brew
    ## brio                   brio
    ## bslib                 bslib
    ## cachem               cachem
    ## callr                 callr
    ## class                 class
    ## cli                     cli
    ## clipr                 clipr
    ## cluster             cluster
    ## codetools         codetools
    ## colorspace       colorspace
    ## commonmark       commonmark
    ## compiler           compiler
    ## cpp11                 cpp11
    ## crayon               crayon
    ## credentials     credentials
    ## csv                     csv
    ## curl                   curl
    ## data.table       data.table
    ## datasets           datasets
    ## DBI                     DBI
    ## desc                   desc
    ## devtools           devtools
    ## diffobj             diffobj
    ## digest               digest
    ## downlit             downlit
    ## dplyr                 dplyr
    ## ellipsis           ellipsis
    ## encode               encode
    ## evaluate           evaluate
    ## fansi                 fansi
    ## farver               farver
    ## fastmap             fastmap
    ## fontawesome     fontawesome
    ## foreign             foreign
    ## fs                       fs
    ## generics           generics
    ## gert                   gert
    ## ggplot2             ggplot2
    ## gh                       gh
    ## gitcreds           gitcreds
    ## glue                   glue
    ## graphics           graphics
    ## grDevices         grDevices
    ## grid                   grid
    ## gtable               gtable
    ## here                   here
    ## highr                 highr
    ## hms                     hms
    ## htmltools         htmltools
    ## htmlwidgets     htmlwidgets
    ## httpuv               httpuv
    ## httr                   httr
    ## ini                     ini
    ## isoband             isoband
    ## jquerylib         jquerylib
    ## jsonlite           jsonlite
    ## KernSmooth       KernSmooth
    ## knitr                 knitr
    ## labeling           labeling
    ## later                 later
    ## lattice             lattice
    ## lifecycle         lifecycle
    ## lubridate         lubridate
    ## magrittr           magrittr
    ## markdown           markdown
    ## MASS                   MASS
    ## Matrix               Matrix
    ## memoise             memoise
    ## methods             methods
    ## mgcv                   mgcv
    ## mime                   mime
    ## miniUI               miniUI
    ## munsell             munsell
    ## nlme                   nlme
    ## nnet                   nnet
    ## openssl             openssl
    ## parallel           parallel
    ## pillar               pillar
    ## pkgbuild           pkgbuild
    ## pkgconfig         pkgconfig
    ## pkgdown             pkgdown
    ## pkgload             pkgload
    ## plogr                 plogr
    ## praise               praise
    ## prettyunits     prettyunits
    ## processx           processx
    ## profvis             profvis
    ## progress           progress
    ## promises           promises
    ## ps                       ps
    ## purrr                 purrr
    ## R6                       R6
    ## ragg                   ragg
    ## rappdirs           rappdirs
    ## rcmdcheck         rcmdcheck
    ## RColorBrewer   RColorBrewer
    ## Rcpp                   Rcpp
    ## readr                 readr
    ## rematch2           rematch2
    ## remotes             remotes
    ## rlang                 rlang
    ## RMariaDB           RMariaDB
    ## rmarkdown         rmarkdown
    ## roxygen2           roxygen2
    ## rpart                 rpart
    ## rprojroot         rprojroot
    ## rstudioapi       rstudioapi
    ## rversions         rversions
    ## sass                   sass
    ## scales               scales
    ## sessioninfo     sessioninfo
    ## shiny                 shiny
    ## sourcetools     sourcetools
    ## spatial             spatial
    ## spec                   spec
    ## splines             splines
    ## stats                 stats
    ## stats4               stats4
    ## stringi             stringi
    ## stringr             stringr
    ## survival           survival
    ## sys                     sys
    ## systemfonts     systemfonts
    ## tcltk                 tcltk
    ## testthat           testthat
    ## textshaping     textshaping
    ## tibble               tibble
    ## tidyr                 tidyr
    ## tidyselect       tidyselect
    ## tinytex             tinytex
    ## tools                 tools
    ## tzdb                   tzdb
    ## urlchecker       urlchecker
    ## usethis             usethis
    ## utf8                   utf8
    ## utils                 utils
    ## vctrs                 vctrs
    ## viridisLite     viridisLite
    ## vroom                 vroom
    ## waldo                 waldo
    ## whisker             whisker
    ## withr                 withr
    ## xfun                   xfun
    ## xml2                   xml2
    ## xopen                 xopen
    ## xtable               xtable
    ## yaml                   yaml
    ## zip                     zip
    ##                                                                            LibPath
    ## askpass       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## aws.s3        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## aws.signature /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## base          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## base64enc     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## bit           /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## bit64         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## blob          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## boot          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## brew          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## brio          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## bslib         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## cachem        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## callr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## class         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## cli           /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## clipr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## cluster       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## codetools     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## colorspace    /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## commonmark    /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## compiler      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## cpp11         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## crayon        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## credentials   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## csv           /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## curl          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## data.table    /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## datasets      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## DBI           /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## desc          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## devtools      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## diffobj       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## digest        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## downlit       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## dplyr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## ellipsis      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## encode        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## evaluate      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## fansi         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## farver        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## fastmap       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## fontawesome   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## foreign       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## fs            /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## generics      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## gert          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## ggplot2       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## gh            /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## gitcreds      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## glue          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## graphics      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## grDevices     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## grid          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## gtable        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## here          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## highr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## hms           /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## htmltools     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## htmlwidgets   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## httpuv        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## httr          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## ini           /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## isoband       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## jquerylib     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## jsonlite      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## KernSmooth    /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## knitr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## labeling      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## later         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## lattice       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## lifecycle     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## lubridate     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## magrittr      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## markdown      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## MASS          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## Matrix        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## memoise       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## methods       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## mgcv          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## mime          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## miniUI        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## munsell       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## nlme          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## nnet          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## openssl       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## parallel      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## pillar        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## pkgbuild      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## pkgconfig     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## pkgdown       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## pkgload       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## plogr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## praise        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## prettyunits   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## processx      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## profvis       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## progress      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## promises      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## ps            /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## purrr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## R6            /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## ragg          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rappdirs      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rcmdcheck     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## RColorBrewer  /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## Rcpp          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## readr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rematch2      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## remotes       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rlang         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## RMariaDB      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rmarkdown     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## roxygen2      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rpart         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rprojroot     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rstudioapi    /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## rversions     /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## sass          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## scales        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## sessioninfo   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## shiny         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## sourcetools   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## spatial       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## spec          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## splines       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## stats         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## stats4        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## stringi       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## stringr       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## survival      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## sys           /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## systemfonts   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## tcltk         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## testthat      /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## textshaping   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## tibble        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## tidyr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## tidyselect    /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## tinytex       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## tools         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## tzdb          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## urlchecker    /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## usethis       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## utf8          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## utils         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## vctrs         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## viridisLite   /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## vroom         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## waldo         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## whisker       /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## withr         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## xfun          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## xml2          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## xopen         /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## xtable        /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## yaml          /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ## zip           /Library/Frameworks/R.framework/Versions/4.2-arm64/Resources/library
    ##               Version    Priority
    ## askpass           1.1        <NA>
    ## aws.s3         0.3.21        <NA>
    ## aws.signature   0.6.0        <NA>
    ## base            4.2.1        base
    ## base64enc       0.1-3        <NA>
    ## bit             4.0.4        <NA>
    ## bit64           4.0.5        <NA>
    ## blob            1.2.3        <NA>
    ## boot           1.3-28 recommended
    ## brew            1.0-7        <NA>
    ## brio            1.1.3        <NA>
    ## bslib           0.4.0        <NA>
    ## cachem          1.0.6        <NA>
    ## callr           3.7.1        <NA>
    ## class          7.3-20 recommended
    ## cli             3.3.0        <NA>
    ## clipr           0.8.0        <NA>
    ## cluster         2.1.3 recommended
    ## codetools      0.2-18 recommended
    ## colorspace      2.0-3        <NA>
    ## commonmark      1.8.0        <NA>
    ## compiler        4.2.1        base
    ## cpp11           0.4.2        <NA>
    ## crayon          1.5.1        <NA>
    ## credentials     1.3.2        <NA>
    ## csv             0.6.2        <NA>
    ## curl            4.3.2        <NA>
    ## data.table     1.14.2        <NA>
    ## datasets        4.2.1        base
    ## DBI             1.1.3        <NA>
    ## desc            1.4.1        <NA>
    ## devtools        2.4.4        <NA>
    ## diffobj         0.3.5        <NA>
    ## digest         0.6.29        <NA>
    ## downlit         0.4.2        <NA>
    ## dplyr           1.0.9        <NA>
    ## ellipsis        0.3.2        <NA>
    ## encode          0.3.6        <NA>
    ## evaluate         0.15        <NA>
    ## fansi           1.0.3        <NA>
    ## farver          2.1.1        <NA>
    ## fastmap         1.1.0        <NA>
    ## fontawesome     0.3.0        <NA>
    ## foreign        0.8-82 recommended
    ## fs              1.5.2        <NA>
    ## generics        0.1.3        <NA>
    ## gert            1.6.0        <NA>
    ## ggplot2         3.3.6        <NA>
    ## gh              1.3.0        <NA>
    ## gitcreds        0.1.1        <NA>
    ## glue            1.6.2        <NA>
    ## graphics        4.2.1        base
    ## grDevices       4.2.1        base
    ## grid            4.2.1        base
    ## gtable          0.3.0        <NA>
    ## here            1.0.1        <NA>
    ## highr             0.9        <NA>
    ## hms             1.1.1        <NA>
    ## htmltools       0.5.3        <NA>
    ## htmlwidgets     1.5.4        <NA>
    ## httpuv          1.6.5        <NA>
    ## httr            1.4.3        <NA>
    ## ini             0.3.1        <NA>
    ## isoband         0.2.5        <NA>
    ## jquerylib       0.1.4        <NA>
    ## jsonlite        1.8.0        <NA>
    ## KernSmooth    2.23-20 recommended
    ## knitr            1.39        <NA>
    ## labeling        0.4.2        <NA>
    ## later           1.3.0        <NA>
    ## lattice       0.20-45 recommended
    ## lifecycle       1.0.1        <NA>
    ## lubridate       1.8.0        <NA>
    ## magrittr        2.0.3        <NA>
    ## markdown          1.1        <NA>
    ## MASS           7.3-57 recommended
    ## Matrix          1.4-1 recommended
    ## memoise         2.0.1        <NA>
    ## methods         4.2.1        base
    ## mgcv           1.8-40 recommended
    ## mime             0.12        <NA>
    ## miniUI        0.1.1.1        <NA>
    ## munsell         0.5.0        <NA>
    ## nlme          3.1-157 recommended
    ## nnet           7.3-17 recommended
    ## openssl         2.0.2        <NA>
    ## parallel        4.2.1        base
    ## pillar          1.8.0        <NA>
    ## pkgbuild        1.3.1        <NA>
    ## pkgconfig       2.0.3        <NA>
    ## pkgdown         2.0.6        <NA>
    ## pkgload         1.3.0        <NA>
    ## plogr           0.2.0        <NA>
    ## praise          1.0.0        <NA>
    ## prettyunits     1.1.1        <NA>
    ## processx        3.7.0        <NA>
    ## profvis         0.3.7        <NA>
    ## progress        1.2.2        <NA>
    ## promises      1.2.0.1        <NA>
    ## ps              1.7.1        <NA>
    ## purrr           0.3.4        <NA>
    ## R6              2.5.1        <NA>
    ## ragg            1.2.2        <NA>
    ## rappdirs        0.3.3        <NA>
    ## rcmdcheck       1.4.0        <NA>
    ## RColorBrewer    1.1-3        <NA>
    ## Rcpp            1.0.9        <NA>
    ## readr           2.1.2        <NA>
    ## rematch2        2.1.2        <NA>
    ## remotes         2.4.2        <NA>
    ## rlang           1.0.4        <NA>
    ## RMariaDB        1.2.2        <NA>
    ## rmarkdown        2.14        <NA>
    ## roxygen2        7.2.1        <NA>
    ## rpart          4.1.16 recommended
    ## rprojroot       2.0.3        <NA>
    ## rstudioapi       0.13        <NA>
    ## rversions       2.1.1        <NA>
    ## sass            0.4.2        <NA>
    ## scales          1.2.0        <NA>
    ## sessioninfo     1.2.2        <NA>
    ## shiny           1.7.2        <NA>
    ## sourcetools     0.1.7        <NA>
    ## spatial        7.3-15 recommended
    ## spec            0.1.7        <NA>
    ## splines         4.2.1        base
    ## stats           4.2.1        base
    ## stats4          4.2.1        base
    ## stringi         1.7.8        <NA>
    ## stringr         1.4.0        <NA>
    ## survival        3.3-1 recommended
    ## sys               3.4        <NA>
    ## systemfonts     1.0.4        <NA>
    ## tcltk           4.2.1        base
    ## testthat        3.1.4        <NA>
    ## textshaping     0.3.6        <NA>
    ## tibble          3.1.8        <NA>
    ## tidyr           1.2.0        <NA>
    ## tidyselect      1.1.2        <NA>
    ## tinytex          0.40        <NA>
    ## tools           4.2.1        base
    ## tzdb            0.3.0        <NA>
    ## urlchecker      1.0.1        <NA>
    ## usethis         2.1.6        <NA>
    ## utf8            1.2.2        <NA>
    ## utils           4.2.1        base
    ## vctrs           0.4.1        <NA>
    ## viridisLite     0.4.0        <NA>
    ## vroom           1.5.7        <NA>
    ## waldo           0.4.0        <NA>
    ## whisker           0.4        <NA>
    ## withr           2.5.0        <NA>
    ## xfun             0.31        <NA>
    ## xml2            1.3.3        <NA>
    ## xopen           1.0.0        <NA>
    ## xtable          1.8-4        <NA>
    ## yaml            2.3.5        <NA>
    ## zip             2.2.0        <NA>
    ##                                                           Depends
    ## askpass                                                      <NA>
    ## aws.s3                                                       <NA>
    ## aws.signature                                                <NA>
    ## base                                                         <NA>
    ## base64enc                                            R (>= 2.9.0)
    ## bit                                                  R (>= 2.9.2)
    ## bit64         R (>= 3.0.1), bit (>= 4.0.0), utils, methods, stats
    ## blob                                                         <NA>
    ## boot                                R (>= 3.0.0), graphics, stats
    ## brew                                                         <NA>
    ## brio                                                         <NA>
    ## bslib                                                 R (>= 2.10)
    ## cachem                                                       <NA>
    ## callr                                                  R (>= 3.4)
    ## class                                  R (>= 3.0.0), stats, utils
    ## cli                                                    R (>= 3.4)
    ## clipr                                                        <NA>
    ## cluster                                              R (>= 3.5.0)
    ## codetools                                              R (>= 2.1)
    ## colorspace                                  R (>= 3.0.0), methods
    ## commonmark                                                   <NA>
    ## compiler                                                     <NA>
    ## cpp11                                                        <NA>
    ## crayon                                                       <NA>
    ## credentials                                                  <NA>
    ## csv                                                          <NA>
    ## curl                                                 R (>= 3.0.0)
    ## data.table                                           R (>= 3.1.0)
    ## datasets                                                     <NA>
    ## DBI                                         methods, R (>= 3.0.0)
    ## desc                                                   R (>= 3.4)
    ## devtools                         R (>= 3.0.2), usethis (>= 2.1.6)
    ## diffobj                                              R (>= 3.1.0)
    ## digest                                               R (>= 3.3.0)
    ## downlit                                              R (>= 3.4.0)
    ## dplyr                                                R (>= 3.4.0)
    ## ellipsis                                               R (>= 3.2)
    ## encode                                                       <NA>
    ## evaluate                                             R (>= 3.0.2)
    ## fansi                                                R (>= 3.1.0)
    ## farver                                                       <NA>
    ## fastmap                                                      <NA>
    ## fontawesome                                          R (>= 3.3.0)
    ## foreign                                              R (>= 4.0.0)
    ## fs                                                     R (>= 3.1)
    ## generics                                               R (>= 3.2)
    ## gert                                                         <NA>
    ## ggplot2                                                R (>= 3.3)
    ## gh                                                           <NA>
    ## gitcreds                                                     <NA>
    ## glue                                                   R (>= 3.4)
    ## graphics                                                     <NA>
    ## grDevices                                                    <NA>
    ## grid                                                         <NA>
    ## gtable                                                 R (>= 3.0)
    ## here                                                         <NA>
    ## highr                                                R (>= 3.2.3)
    ## hms                                                          <NA>
    ## htmltools                                           R (>= 2.14.1)
    ## htmlwidgets                                                  <NA>
    ## httpuv                                              R (>= 2.15.1)
    ## httr                                                   R (>= 3.2)
    ## ini                                                          <NA>
    ## isoband                                                      <NA>
    ## jquerylib                                                    <NA>
    ## jsonlite                                                  methods
    ## KernSmooth                                    R (>= 2.5.0), stats
    ## knitr                                                R (>= 3.3.0)
    ## labeling                                                     <NA>
    ## later                                                        <NA>
    ## lattice                                              R (>= 3.0.0)
    ## lifecycle                                              R (>= 3.3)
    ## lubridate                                     methods, R (>= 3.2)
    ## magrittr                                             R (>= 3.4.0)
    ## markdown                                            R (>= 2.11.1)
    ## MASS              R (>= 3.3.0), grDevices, graphics, stats, utils
    ## Matrix                                               R (>= 3.5.0)
    ## memoise                                                      <NA>
    ## methods                                                      <NA>
    ## mgcv                               R (>= 3.6.0), nlme (>= 3.1-64)
    ## mime                                                         <NA>
    ## miniUI                                                       <NA>
    ## munsell                                                      <NA>
    ## nlme                                                 R (>= 3.5.0)
    ## nnet                                   R (>= 3.0.0), stats, utils
    ## openssl                                                      <NA>
    ## parallel                                                     <NA>
    ## pillar                                                       <NA>
    ## pkgbuild                                               R (>= 3.1)
    ## pkgconfig                                                    <NA>
    ## pkgdown                                              R (>= 3.1.0)
    ## pkgload                                              R (>= 3.4.0)
    ## plogr                                                        <NA>
    ## praise                                                       <NA>
    ## prettyunits                                                  <NA>
    ## processx                                             R (>= 3.4.0)
    ## profvis                                                R (>= 3.0)
    ## progress                                                     <NA>
    ## promises                                                     <NA>
    ## ps                                                     R (>= 3.4)
    ## purrr                                                  R (>= 3.2)
    ## R6                                                     R (>= 3.0)
    ## ragg                                                         <NA>
    ## rappdirs                                               R (>= 3.2)
    ## rcmdcheck                                                    <NA>
    ## RColorBrewer                                         R (>= 2.0.0)
    ## Rcpp                                                         <NA>
    ## readr                                                  R (>= 3.1)
    ## rematch2                                                     <NA>
    ## remotes                                              R (>= 3.0.0)
    ## rlang                                                R (>= 3.4.0)
    ## RMariaDB                                             R (>= 2.8.0)
    ## rmarkdown                                              R (>= 3.0)
    ## roxygen2                                               R (>= 3.3)
    ## rpart                   R (>= 2.15.0), graphics, stats, grDevices
    ## rprojroot                                            R (>= 3.0.0)
    ## rstudioapi                                                   <NA>
    ## rversions                                                    <NA>
    ## sass                                                         <NA>
    ## scales                                                 R (>= 3.2)
    ## sessioninfo                                           R (>= 2.10)
    ## shiny                                       R (>= 3.0.2), methods
    ## sourcetools                                          R (>= 3.0.2)
    ## spatial                      R (>= 3.0.0), graphics, stats, utils
    ## spec                                                  R (>= 2.10)
    ## splines                                                      <NA>
    ## stats                                                        <NA>
    ## stats4                                                       <NA>
    ## stringi                                                R (>= 3.1)
    ## stringr                                                R (>= 3.1)
    ## survival                                             R (>= 3.5.0)
    ## sys                                                          <NA>
    ## systemfonts                                          R (>= 3.2.0)
    ## tcltk                                                        <NA>
    ## testthat                                               R (>= 3.1)
    ## textshaping                                          R (>= 3.2.0)
    ## tibble                                               R (>= 3.1.0)
    ## tidyr                                                  R (>= 3.1)
    ## tidyselect                                             R (>= 3.2)
    ## tinytex                                                      <NA>
    ## tools                                                        <NA>
    ## tzdb                                                 R (>= 3.4.0)
    ## urlchecker                                             R (>= 3.3)
    ## usethis                                                R (>= 3.4)
    ## utf8                                                  R (>= 2.10)
    ## utils                                                        <NA>
    ## vctrs                                                  R (>= 3.3)
    ## viridisLite                                           R (>= 2.10)
    ## vroom                                                  R (>= 3.1)
    ## waldo                                                        <NA>
    ## whisker                                                      <NA>
    ## withr                                                R (>= 3.2.0)
    ## xfun                                                         <NA>
    ## xml2                                                 R (>= 3.1.0)
    ## xopen                                                  R (>= 3.1)
    ## xtable                                              R (>= 2.10.0)
    ## yaml                                                         <NA>
    ## zip                                                          <NA>
    ##                                                                                                                                                                                                                                                                                                                                                                                                                                                   Imports
    ## askpass                                                                                                                                                                                                                                                                                                                                                                                                                                      sys (>= 2.1)
    ## aws.s3                                                                                                                                                                                                                                                                                                                                                             utils, tools, curl, httr, xml2 (> 1.0.0), base64enc, digest,\naws.signature (>= 0.3.7)
    ## aws.signature                                                                                                                                                                                                                                                                                                                                                                                                                           digest, base64enc
    ## base                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## base64enc                                                                                                                                                                                                                                                                                                                                                                                                                                            <NA>
    ## bit                                                                                                                                                                                                                                                                                                                                                                                                                                                  <NA>
    ## bit64                                                                                                                                                                                                                                                                                                                                                                                                                                                <NA>
    ## blob                                                                                                                                                                                                                                                                                                                                                                                                                     methods, rlang, vctrs (>= 0.2.1)
    ## boot                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## brew                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## brio                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## bslib                                                                                                                                                                                                                                                                                                                                           grDevices, htmltools (>= 0.5.2), jsonlite, sass (>= 0.4.0),\njquerylib (>= 0.1.3), rlang, cachem, memoise
    ## cachem                                                                                                                                                                                                                                                                                                                                                                                                                                     rlang, fastmap
    ## callr                                                                                                                                                                                                                                                                                                                                                                                                                      processx (>= 3.6.1), R6, utils
    ## class                                                                                                                                                                                                                                                                                                                                                                                                                                                MASS
    ## cli                                                                                                                                                                                                                                                                                                                                                                                                                                glue (>= 1.6.0), utils
    ## clipr                                                                                                                                                                                                                                                                                                                                                                                                                                               utils
    ## cluster                                                                                                                                                                                                                                                                                                                                                                                                                 graphics, grDevices, stats, utils
    ## codetools                                                                                                                                                                                                                                                                                                                                                                                                                                            <NA>
    ## colorspace                                                                                                                                                                                                                                                                                                                                                                                                                     graphics, grDevices, stats
    ## commonmark                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
    ## compiler                                                                                                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## cpp11                                                                                                                                                                                                                                                                                                                                                                                                                                                <NA>
    ## crayon                                                                                                                                                                                                                                                                                                                                                                                                                          grDevices, methods, utils
    ## credentials                                                                                                                                                                                                                                                                                                                                                                                       openssl (>= 1.3), sys (>= 2.1), curl, jsonlite, askpass
    ## csv                                                                                                                                                                                                                                                                                                                                                                                                                                   data.table, stringi
    ## curl                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## data.table                                                                                                                                                                                                                                                                                                                                                                                                                                        methods
    ## datasets                                                                                                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## DBI                                                                                                                                                                                                                                                                                                                                                                                                                                                  <NA>
    ## desc                                                                                                                                                                                                                                                                                                                                                                                                                            cli, R6, rprojroot, utils
    ## devtools      cli (>= 3.3.0), desc (>= 1.4.1), ellipsis (>= 0.3.2), fs (>=\n1.5.2), lifecycle (>= 1.0.1), memoise (>= 2.0.1), miniUI (>=\n0.1.1.1), pkgbuild (>= 1.3.1), pkgdown (>= 2.0.6), pkgload (>=\n1.3.0), profvis (>= 0.3.7), rcmdcheck (>= 1.4.0), remotes (>=\n2.4.2), rlang (>= 1.0.4), roxygen2 (>= 7.2.1), rversions (>=\n2.1.1), sessioninfo (>= 1.2.2), stats, testthat (>= 3.1.4),\ntools, urlchecker (>= 1.0.1), utils, withr (>= 2.5.0)
    ## diffobj                                                                                                                                                                                                                                                                                                                                                                                                   crayon (>= 1.3.2), tools, methods, utils, stats
    ## digest                                                                                                                                                                                                                                                                                                                                                                                                                                              utils
    ## downlit                                                                                                                                                                                                                                                                                                                                                                          brio, desc, digest, evaluate, fansi, memoise, rlang, vctrs,\nwithr, yaml
    ## dplyr                                                                                                                                                                                                                                                          generics, glue (>= 1.3.2), lifecycle (>= 1.0.1), magrittr (>=\n1.5), methods, R6, rlang (>= 1.0.2), tibble (>= 2.1.3),\ntidyselect (>= 1.1.1), utils, vctrs (>= 0.4.1), pillar (>=\n1.5.1)
    ## ellipsis                                                                                                                                                                                                                                                                                                                                                                                                                                 rlang (>= 0.3.0)
    ## encode                                                                                                                                                                                                                                                                                                                                                                                                                                                   
    ## evaluate                                                                                                                                                                                                                                                                                                                                                                                                                                          methods
    ## fansi                                                                                                                                                                                                                                                                                                                                                                                                                                    grDevices, utils
    ## farver                                                                                                                                                                                                                                                                                                                                                                                                                                               <NA>
    ## fastmap                                                                                                                                                                                                                                                                                                                                                                                                                                              <NA>
    ## fontawesome                                                                                                                                                                                                                                                                                                                                                                                                     rlang (>= 0.4.10), htmltools (>= 0.5.1.1)
    ## foreign                                                                                                                                                                                                                                                                                                                                                                                                                             methods, utils, stats
    ## fs                                                                                                                                                                                                                                                                                                                                                                                                                                                methods
    ## generics                                                                                                                                                                                                                                                                                                                                                                                                                                          methods
    ## gert                                                                                                                                                                                                                                                                                                                                                      askpass, credentials (>= 1.2.1), openssl (>= 1.4.1),\nrstudioapi (>= 0.11), sys, zip (>= 2.1.0)
    ## ggplot2                                                                                                                                                                                                                                                                                                    digest, glue, grDevices, grid, gtable (>= 0.1.1), isoband,\nMASS, mgcv, rlang (>= 0.4.10), scales (>= 0.5.0), stats,\ntibble, withr (>= 2.0.0)
    ## gh                                                                                                                                                                                                                                                                                                                                                                                                 cli (>= 2.0.1), gitcreds, httr (>= 1.2), ini, jsonlite
    ## gitcreds                                                                                                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## glue                                                                                                                                                                                                                                                                                                                                                                                                                                              methods
    ## graphics                                                                                                                                                                                                                                                                                                                                                                                                                                        grDevices
    ## grDevices                                                                                                                                                                                                                                                                                                                                                                                                                                            <NA>
    ## grid                                                                                                                                                                                                                                                                                                                                                                                                                                     grDevices, utils
    ## gtable                                                                                                                                                                                                                                                                                                                                                                                                                                               grid
    ## here                                                                                                                                                                                                                                                                                                                                                                                                                                 rprojroot (>= 2.0.2)
    ## highr                                                                                                                                                                                                                                                                                                                                                                                                                                      xfun (>= 0.18)
    ## hms                                                                                                                                                                                                                                                                                                                                                                          ellipsis (>= 0.3.2), lifecycle, methods, pkgconfig, rlang,\nvctrs (>= 0.3.8)
    ## htmltools                                                                                                                                                                                                                                                                                                                                                                     utils, digest, grDevices, base64enc, rlang (>= 0.4.10),\nfastmap (>= 1.1.0)
    ## htmlwidgets                                                                                                                                                                                                                                                                                                                                                                                     grDevices, htmltools (>= 0.3), jsonlite (>= 0.9.16), yaml
    ## httpuv                                                                                                                                                                                                                                                                                                                                                                                             Rcpp (>= 1.0.7), utils, R6, promises, later (>= 0.8.0)
    ## httr                                                                                                                                                                                                                                                                                                                                                                                                curl (>= 3.0.0), jsonlite, mime, openssl (>= 0.8), R6
    ## ini                                                                                                                                                                                                                                                                                                                                                                                                                                                  <NA>
    ## isoband                                                                                                                                                                                                                                                                                                                                                                                                                                       grid, utils
    ## jquerylib                                                                                                                                                                                                                                                                                                                                                                                                                                       htmltools
    ## jsonlite                                                                                                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## KernSmooth                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
    ## knitr                                                                                                                                                                                                                                                                                                                                                      evaluate (>= 0.15), highr, methods, stringr (>= 0.6), yaml (>=\n2.1.19), xfun (>= 0.29), tools
    ## labeling                                                                                                                                                                                                                                                                                                                                                                                                                                  stats, graphics
    ## later                                                                                                                                                                                                                                                                                                                                                                                                                             Rcpp (>= 0.12.9), rlang
    ## lattice                                                                                                                                                                                                                                                                                                                                                                                                           grid, grDevices, graphics, stats, utils
    ## lifecycle                                                                                                                                                                                                                                                                                                                                                                                                                         glue, rlang (>= 0.4.10)
    ## lubridate                                                                                                                                                                                                                                                                                                                                                                                                                                        generics
    ## magrittr                                                                                                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## markdown                                                                                                                                                                                                                                                                                                                                                                                                                       utils, xfun, mime (>= 0.3)
    ## MASS                                                                                                                                                                                                                                                                                                                                                                                                                                              methods
    ## Matrix                                                                                                                                                                                                                                                                                                                                                                                                     methods, graphics, grid, stats, utils, lattice
    ## memoise                                                                                                                                                                                                                                                                                                                                                                                                                         rlang (>= 0.4.10), cachem
    ## methods                                                                                                                                                                                                                                                                                                                                                                                                                                      utils, stats
    ## mgcv                                                                                                                                                                                                                                                                                                                                                                                                     methods, stats, graphics, Matrix, splines, utils
    ## mime                                                                                                                                                                                                                                                                                                                                                                                                                                                tools
    ## miniUI                                                                                                                                                                                                                                                                                                                                                                                                         shiny (>= 0.13), htmltools (>= 0.3), utils
    ## munsell                                                                                                                                                                                                                                                                                                                                                                                                                               colorspace, methods
    ## nlme                                                                                                                                                                                                                                                                                                                                                                                                                      graphics, stats, utils, lattice
    ## nnet                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## openssl                                                                                                                                                                                                                                                                                                                                                                                                                                           askpass
    ## parallel                                                                                                                                                                                                                                                                                                                                                                                                                                  tools, compiler
    ## pillar                                                                                                                                                                                                                                                                                                                                                cli (>= 2.3.0), fansi, glue, lifecycle, rlang (>= 1.0.2), utf8\n(>= 1.1.0), utils, vctrs (>= 0.3.8)
    ## pkgbuild                                                                                                                                                                                                                                                                                                                                                               callr (>= 3.2.0), cli, crayon, desc, prettyunits, R6,\nrprojroot, withr (>= 2.3.0)
    ## pkgconfig                                                                                                                                                                                                                                                                                                                                                                                                                                           utils
    ## pkgdown                                                                                                                                                                                      bslib (>= 0.3.1), callr (>= 2.0.2), cli, desc, digest, downlit\n(>= 0.4.0), fs (>= 1.4.0), httr (>= 1.4.2), jsonlite, magrittr,\nmemoise, purrr, ragg, rlang (>= 1.0.0), rmarkdown (>=\n1.1.9007), tibble, whisker, withr (>= 2.4.3), xml2 (>= 1.3.1),\nyaml
    ## pkgload                                                                                                                                                                                                                                                                                                                                            cli (>= 3.3.0), crayon, desc, fs, glue, methods, rlang (>=\n1.0.3), rprojroot, utils, withr (>= 2.4.3)
    ## plogr                                                                                                                                                                                                                                                                                                                                                                                                                                                <NA>
    ## praise                                                                                                                                                                                                                                                                                                                                                                                                                                               <NA>
    ## prettyunits                                                                                                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## processx                                                                                                                                                                                                                                                                                                                                                                                                                         ps (>= 1.2.0), R6, utils
    ## profvis                                                                                                                                                                                                                                                                                                                                                                                                                   htmlwidgets (>= 0.3.2), stringr
    ## progress                                                                                                                                                                                                                                                                                                                                                                                                                     hms, prettyunits, R6, crayon
    ## promises                                                                                                                                                                                                                                                                                                                                                                                                          R6, Rcpp, later, rlang, stats, magrittr
    ## ps                                                                                                                                                                                                                                                                                                                                                                                                                                                  utils
    ## purrr                                                                                                                                                                                                                                                                                                                                                                                                                 magrittr (>= 1.5), rlang (>= 0.3.1)
    ## R6                                                                                                                                                                                                                                                                                                                                                                                                                                                   <NA>
    ## ragg                                                                                                                                                                                                                                                                                                                                                                                                       systemfonts (>= 1.0.3), textshaping (>= 0.3.0)
    ## rappdirs                                                                                                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## rcmdcheck                                                                                                                                                                                                                                                                                       callr (>= 3.1.1.9000), cli (>= 3.0.0), curl, desc (>= 1.2.0),\ndigest, pkgbuild, prettyunits, R6, rprojroot, sessioninfo (>=\n1.1.1), utils, withr, xopen
    ## RColorBrewer                                                                                                                                                                                                                                                                                                                                                                                                                                         <NA>
    ## Rcpp                                                                                                                                                                                                                                                                                                                                                                                                                                       methods, utils
    ## readr                                                                                                                                                                                                                                                                                                                           cli (>= 3.0.0), clipr, crayon, hms (>= 0.4.1), lifecycle (>=\n0.2.0), methods, R6, rlang, tibble, utils, vroom (>= 1.5.6)
    ## rematch2                                                                                                                                                                                                                                                                                                                                                                                                                                           tibble
    ## remotes                                                                                                                                                                                                                                                                                                                                                                                                                      methods, stats, tools, utils
    ## rlang                                                                                                                                                                                                                                                                                                                                                                                                                                               utils
    ## RMariaDB                                                                                                                                                                                                                                                                                                                                                        bit64, blob, DBI (>= 1.1.3), hms (>= 0.5.0), lubridate,\nmethods, Rcpp (>= 0.12.4), rlang
    ## rmarkdown                                                                                                                                                                                                                                           bslib (>= 0.2.5.1), evaluate (>= 0.13), htmltools (>= 0.3.5),\njquerylib, jsonlite, knitr (>= 1.22), methods, stringr (>=\n1.2.0), tinytex (>= 0.31), tools, utils, xfun (>= 0.30), yaml\n(>= 2.1.19)
    ## roxygen2                                                                                                                                                                                                                                             brew, cli (>= 3.3.0), commonmark, desc (>= 1.2.0), digest,\nknitr, methods, pkgload (>= 1.0.2), purrr (>= 0.3.3), R6 (>=\n2.1.2), rlang (>= 1.0.0), stringi, stringr (>= 1.0.0), utils,\nwithr, xml2
    ## rpart                                                                                                                                                                                                                                                                                                                                                                                                                                                <NA>
    ## rprojroot                                                                                                                                                                                                                                                                                                                                                                                                                                            <NA>
    ## rstudioapi                                                                                                                                                                                                                                                                                                                                                                                                                                           <NA>
    ## rversions                                                                                                                                                                                                                                                                                                                                                                                                                    curl, utils, xml2 (>= 1.0.0)
    ## sass                                                                                                                                                                                                                                                                                                                                                                                            fs, rlang (>= 0.4.10), htmltools (>= 0.5.1), R6, rappdirs
    ## scales                                                                                                                                                                                                                                                                                                                                         farver (>= 2.0.3), labeling, lifecycle, munsell (>= 0.5), R6,\nRColorBrewer, rlang (>= 1.0.0), viridisLite
    ## sessioninfo                                                                                                                                                                                                                                                                                                                                                                                                                  cli (>= 3.1.0), tools, utils
    ## shiny                                                                                   utils, grDevices, httpuv (>= 1.5.2), mime (>= 0.3), jsonlite\n(>= 0.9.16), xtable, fontawesome (>= 0.2.1), htmltools (>=\n0.5.2), R6 (>= 2.0), sourcetools, later (>= 1.0.0), promises\n(>= 1.1.0), tools, crayon, rlang (>= 0.4.10), fastmap (>=\n1.1.0), withr, commonmark (>= 1.7), glue (>= 1.3.2), bslib (>=\n0.3.0), cachem, ellipsis, lifecycle (>= 0.2.0)
    ## sourcetools                                                                                                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## spatial                                                                                                                                                                                                                                                                                                                                                                                                                                              <NA>
    ## spec                                                                                                                                                                                                                                                                                                                                                                                                                         encode, csv, magrittr, utils
    ## splines                                                                                                                                                                                                                                                                                                                                                                                                                                   graphics, stats
    ## stats                                                                                                                                                                                                                                                                                                                                                                                                                          utils, grDevices, graphics
    ## stats4                                                                                                                                                                                                                                                                                                                                                                                                                           graphics, methods, stats
    ## stringi                                                                                                                                                                                                                                                                                                                                                                                                                               tools, utils, stats
    ## stringr                                                                                                                                                                                                                                                                                                                                                                                                     glue (>= 1.2.0), magrittr, stringi (>= 1.1.7)
    ## survival                                                                                                                                                                                                                                                                                                                                                                                                 graphics, Matrix, methods, splines, stats, utils
    ## sys                                                                                                                                                                                                                                                                                                                                                                                                                                                  <NA>
    ## systemfonts                                                                                                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## tcltk                                                                                                                                                                                                                                                                                                                                                                                                                                               utils
    ## testthat                                                                                                                                                                         brio, callr (>= 3.5.1), cli (>= 3.3.0), crayon (>= 1.3.4),\ndesc, digest, ellipsis (>= 0.2.0), evaluate, jsonlite,\nlifecycle, magrittr, methods, pkgload, praise, processx, ps (>=\n1.3.4), R6 (>= 2.2.0), rlang (>= 1.0.1), utils, waldo (>=\n0.4.0), withr (>= 2.4.3)
    ## textshaping                                                                                                                                                                                                                                                                                                                                                                                                                        systemfonts (>= 1.0.0)
    ## tibble                                                                                                                                                                                                                                                                                                               fansi (>= 0.4.0), lifecycle (>= 1.0.0), magrittr, methods,\npillar (>= 1.7.0), pkgconfig, rlang (>= 1.0.2), utils, vctrs\n(>= 0.3.8)
    ## tidyr                                                                                                                                                                                                                                                                                                 dplyr (>= 1.0.0), ellipsis (>= 0.1.0), glue, lifecycle,\nmagrittr, purrr, rlang, tibble (>= 2.1.1), tidyselect (>=\n1.1.0), utils, vctrs (>= 0.3.7)
    ## tidyselect                                                                                                                                                                                                                                                                                                                                                               ellipsis, glue (>= 1.3.0), purrr (>= 0.3.2), rlang (>= 1.0.1),\nvctrs (>= 0.3.0)
    ## tinytex                                                                                                                                                                                                                                                                                                                                                                                                                                    xfun (>= 0.29)
    ## tools                                                                                                                                                                                                                                                                                                                                                                                                                                                <NA>
    ## tzdb                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## urlchecker                                                                                                                                                                                                                                                                                                                                                                                                                         cli, curl, tools, xml2
    ## usethis                                                                                                                                                    cli (>= 3.0.1), clipr (>= 0.3.0), crayon, curl (>= 2.7), desc\n(>= 1.4.0), fs (>= 1.3.0), gert (>= 1.4.1), gh (>= 1.2.1), glue\n(>= 1.3.0), jsonlite, lifecycle (>= 1.0.0), purrr, rappdirs,\nrlang (>= 1.0.0), rprojroot (>= 1.2), rstudioapi, stats, utils,\nwhisker, withr (>= 2.3.0), yaml
    ## utf8                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## utils                                                                                                                                                                                                                                                                                                                                                                                                                                                <NA>
    ## vctrs                                                                                                                                                                                                                                                                                                                                                                                                              cli (>= 3.2.0), glue, rlang (>= 1.0.2)
    ## viridisLite                                                                                                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## vroom                                                                                                                                                                                                                                                                                               bit64, crayon, cli, glue, hms, lifecycle, methods, rlang (>=\n0.4.2), stats, tibble (>= 2.0.0), tzdb (>= 0.1.1), vctrs (>=\n0.2.0), tidyselect, withr
    ## waldo                                                                                                                                                                                                                                                                                                                                                                  cli, diffobj (>= 0.3.4), fansi, glue, methods, rematch2, rlang\n(>= 1.0.0), tibble
    ## whisker                                                                                                                                                                                                                                                                                                                                                                                                                                              <NA>
    ## withr                                                                                                                                                                                                                                                                                                                                                                                                                          graphics, grDevices, stats
    ## xfun                                                                                                                                                                                                                                                                                                                                                                                                                                         stats, tools
    ## xml2                                                                                                                                                                                                                                                                                                                                                                                                                                              methods
    ## xopen                                                                                                                                                                                                                                                                                                                                                                                                                                            processx
    ## xtable                                                                                                                                                                                                                                                                                                                                                                                                                                       stats, utils
    ## yaml                                                                                                                                                                                                                                                                                                                                                                                                                                                 <NA>
    ## zip                                                                                                                                                                                                                                                                                                                                                                                                                                                  <NA>
    ##                                                            LinkingTo
    ## askpass                                                         <NA>
    ## aws.s3                                                          <NA>
    ## aws.signature                                                   <NA>
    ## base                                                            <NA>
    ## base64enc                                                       <NA>
    ## bit                                                             <NA>
    ## bit64                                                           <NA>
    ## blob                                                            <NA>
    ## boot                                                            <NA>
    ## brew                                                            <NA>
    ## brio                                                            <NA>
    ## bslib                                                           <NA>
    ## cachem                                                          <NA>
    ## callr                                                           <NA>
    ## class                                                           <NA>
    ## cli                                                             <NA>
    ## clipr                                                           <NA>
    ## cluster                                                         <NA>
    ## codetools                                                       <NA>
    ## colorspace                                                      <NA>
    ## commonmark                                                      <NA>
    ## compiler                                                        <NA>
    ## cpp11                                                           <NA>
    ## crayon                                                          <NA>
    ## credentials                                                     <NA>
    ## csv                                                             <NA>
    ## curl                                                            <NA>
    ## data.table                                                      <NA>
    ## datasets                                                        <NA>
    ## DBI                                                             <NA>
    ## desc                                                            <NA>
    ## devtools                                                        <NA>
    ## diffobj                                                         <NA>
    ## digest                                                          <NA>
    ## downlit                                                         <NA>
    ## dplyr                                                           <NA>
    ## ellipsis                                                        <NA>
    ## encode                                                          <NA>
    ## evaluate                                                        <NA>
    ## fansi                                                           <NA>
    ## farver                                                          <NA>
    ## fastmap                                                         <NA>
    ## fontawesome                                                     <NA>
    ## foreign                                                         <NA>
    ## fs                                                              <NA>
    ## generics                                                        <NA>
    ## gert                                                            <NA>
    ## ggplot2                                                         <NA>
    ## gh                                                              <NA>
    ## gitcreds                                                        <NA>
    ## glue                                                            <NA>
    ## graphics                                                        <NA>
    ## grDevices                                                       <NA>
    ## grid                                                            <NA>
    ## gtable                                                          <NA>
    ## here                                                            <NA>
    ## highr                                                           <NA>
    ## hms                                                             <NA>
    ## htmltools                                                       <NA>
    ## htmlwidgets                                                     <NA>
    ## httpuv                                                   Rcpp, later
    ## httr                                                            <NA>
    ## ini                                                             <NA>
    ## isoband                                                         <NA>
    ## jquerylib                                                       <NA>
    ## jsonlite                                                        <NA>
    ## KernSmooth                                                      <NA>
    ## knitr                                                           <NA>
    ## labeling                                                        <NA>
    ## later                                                           Rcpp
    ## lattice                                                         <NA>
    ## lifecycle                                                       <NA>
    ## lubridate                                           cpp11 (>= 0.2.7)
    ## magrittr                                                        <NA>
    ## markdown                                                        <NA>
    ## MASS                                                            <NA>
    ## Matrix                                                          <NA>
    ## memoise                                                         <NA>
    ## methods                                                         <NA>
    ## mgcv                                                            <NA>
    ## mime                                                            <NA>
    ## miniUI                                                          <NA>
    ## munsell                                                         <NA>
    ## nlme                                                            <NA>
    ## nnet                                                            <NA>
    ## openssl                                                         <NA>
    ## parallel                                                        <NA>
    ## pillar                                                          <NA>
    ## pkgbuild                                                        <NA>
    ## pkgconfig                                                       <NA>
    ## pkgdown                                                         <NA>
    ## pkgload                                                         <NA>
    ## plogr                                                           <NA>
    ## praise                                                          <NA>
    ## prettyunits                                                     <NA>
    ## processx                                                        <NA>
    ## profvis                                                         <NA>
    ## progress                                                        <NA>
    ## promises                                                 later, Rcpp
    ## ps                                                              <NA>
    ## purrr                                                           <NA>
    ## R6                                                              <NA>
    ## ragg                                        systemfonts, textshaping
    ## rappdirs                                                        <NA>
    ## rcmdcheck                                                       <NA>
    ## RColorBrewer                                                    <NA>
    ## Rcpp                                                            <NA>
    ## readr                                         cpp11, tzdb (>= 0.1.1)
    ## rematch2                                                        <NA>
    ## remotes                                                         <NA>
    ## rlang                                                           <NA>
    ## RMariaDB                                                 plogr, Rcpp
    ## rmarkdown                                                       <NA>
    ## roxygen2                                                       cpp11
    ## rpart                                                           <NA>
    ## rprojroot                                                       <NA>
    ## rstudioapi                                                      <NA>
    ## rversions                                                       <NA>
    ## sass                                                            <NA>
    ## scales                                                          <NA>
    ## sessioninfo                                                     <NA>
    ## shiny                                                           <NA>
    ## sourcetools                                                     <NA>
    ## spatial                                                         <NA>
    ## spec                                                            <NA>
    ## splines                                                         <NA>
    ## stats                                                           <NA>
    ## stats4                                                          <NA>
    ## stringi                                                         <NA>
    ## stringr                                                         <NA>
    ## survival                                                        <NA>
    ## sys                                                             <NA>
    ## systemfonts                                         cpp11 (>= 0.2.1)
    ## tcltk                                                           <NA>
    ## testthat                                                        <NA>
    ## textshaping                 cpp11 (>= 0.2.1), systemfonts (>= 1.0.0)
    ## tibble                                                          <NA>
    ## tidyr                                               cpp11 (>= 0.4.0)
    ## tidyselect                                                      <NA>
    ## tinytex                                                         <NA>
    ## tools                                                           <NA>
    ## tzdb                                                cpp11 (>= 0.4.2)
    ## urlchecker                                                      <NA>
    ## usethis                                                         <NA>
    ## utf8                                                            <NA>
    ## utils                                                           <NA>
    ## vctrs                                                           <NA>
    ## viridisLite                                                     <NA>
    ## vroom         progress (>= 1.2.1), cpp11 (>= 0.2.0), tzdb (>= 0.1.1)
    ## waldo                                                           <NA>
    ## whisker                                                         <NA>
    ## withr                                                           <NA>
    ## xfun                                                            <NA>
    ## xml2                                                            <NA>
    ## xopen                                                           <NA>
    ## xtable                                                          <NA>
    ## yaml                                                            <NA>
    ## zip                                                             <NA>
    ##                                                                                                                                                                                                                                                                                                                                                               Suggests
    ## askpass                                                                                                                                                                                                                                                                                                                                                       testthat
    ## aws.s3                                                                                                                                                                                                                                                                                                                                              testthat, datasets
    ## aws.signature                                                                                                                                                                                                                                                                                                          testthat (>= 2.1.0), aws.ec2metadata (>= 0.1.6)
    ## base                                                                                                                                                                                                                                                                                                                                                           methods
    ## base64enc                                                                                                                                                                                                                                                                                                                                                         <NA>
    ## bit                                                                                                                                                                                                                                                                 testthat (>= 0.11.0), roxygen2, knitr, rmarkdown,\nmicrobenchmark, bit64 (>= 4.0.0), ff (>= 4.0.0)
    ## bit64                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## blob                                                                                                                                                                                                                                                                                                                         covr, crayon, pillar (>= 1.2.1), testthat
    ## boot                                                                                                                                                                                                                                                                                                                                                    MASS, survival
    ## brew                                                                                                                                                                                                                                                                                                                                                          testthat
    ## brio                                                                                                                                                                                                                                                                                                                                         covr, testthat (>= 2.1.0)
    ## bslib                                                                                                                                                                                                                                                                shiny (>= 1.6.0), rmarkdown (>= 2.7), thematic, knitr,\ntestthat, withr, rappdirs, curl, magrittr
    ## cachem                                                                                                                                                                                                                                                                                                                                                        testthat
    ## callr                                                                                                                                                                                                                                                                   cli (>= 1.1.0), covr, mockery, ps, rprojroot, spelling,\ntestthat (>= 3.0.0), withr (>= 2.3.0)
    ## class                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## cli                                                                                                                                                                  asciicast, callr, covr, digest, grDevices, htmltools,\nhtmlwidgets, knitr, methods, mockery, processx, ps (>=\n1.3.4.9000), rlang, rmarkdown, rstudioapi, shiny, testthat,\ntibble, whoami, withr
    ## clipr                                                                                                                                                                                                                                                                                                covr, knitr, rmarkdown, rstudioapi (>= 0.5), testthat (>=\n2.0.0)
    ## cluster                                                                                                                                                                                                                                                                                                                                                   MASS, Matrix
    ## codetools                                                                                                                                                                                                                                                                                                                                                         <NA>
    ## colorspace                                                                                                                                                       datasets, utils, KernSmooth, MASS, kernlab, mvtnorm, vcd,\ntcltk, shiny, shinyjs, ggplot2, dplyr, scales, grid, png, jpeg,\nknitr, rmarkdown, RColorBrewer, rcartocolor, scico, viridis,\nwesanderson
    ## commonmark                                                                                                                                                                                                                                                                                                                                        curl, testthat, xml2
    ## compiler                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## cpp11                                                                                                                                                                                                    bench, brio, callr, cli, covr, decor, desc, ggplot2, glue,\nknitr, lobstr, mockery, progress, rmarkdown, scales, Rcpp,\ntestthat, tibble, utils, vctrs, withr
    ## crayon                                                                                                                                                                                                                                                                                                                            mockery, rstudioapi, testthat, withr
    ## credentials                                                                                                                                                                                                                                                                                                                                 testthat, knitr, rmarkdown
    ## csv                                                                                                                                                                                                                                                                                                                                                                   
    ## curl                                                                                                                                                                                                                                                                 spelling, testthat (>= 1.0.0), knitr, jsonlite, rmarkdown,\nmagrittr, httpuv (>= 1.4.4), webutils
    ## data.table                                                                                                                                                                                                                                                     bit64 (>= 4.0.0), bit (>= 4.0.4), curl, R.utils, xts,\nnanotime, zoo (>= 1.8-1), yaml, knitr, rmarkdown
    ## datasets                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## DBI                                                                                                                                                                                                                      blob, covr, DBItest, dbplyr, downlit, dplyr, glue, hms,\nknitr, magrittr, RMariaDB, rmarkdown, rprojroot, RSQLite (>=\n1.1-2), testthat, xml2
    ## desc                                                                                                                                                                                                                                                                                                                callr, covr, gh, spelling, testthat, whoami, withr
    ## devtools      BiocManager (>= 1.30.18), callr (>= 3.7.1), covr (>= 3.5.1),\ncurl (>= 4.3.2), digest (>= 0.6.29), DT (>= 0.23), foghorn (>=\n1.4.2), gh (>= 1.3.0), gmailr (>= 1.0.1), httr (>= 1.4.3),\nknitr (>= 1.39), lintr (>= 3.0.0), MASS, mockery (>= 0.4.3),\npingr (>= 2.0.1), rhub (>= 1.1.1), rmarkdown (>= 2.14),\nrstudioapi (>= 0.13), spelling (>= 2.2)
    ## diffobj                                                                                                                                                                                                                                                                                                                                               knitr, rmarkdown
    ## digest                                                                                                                                                                                                                                                                                                                                       tinytest, simplermarkdown
    ## downlit                                                                                                                                                                                                                                                               covr, htmltools, jsonlite, MASS, MassSpecWavelet, pkgload,\nrmarkdown, testthat (>= 3.0.0), xml2
    ## dplyr                                                                                                                                                            bench, broom, callr, covr, DBI, dbplyr (>= 1.4.3), ggplot2,\nknitr, Lahman, lobstr, microbenchmark, nycflights13, purrr,\nrmarkdown, RMySQL, RPostgreSQL, RSQLite, testthat (>= 3.1.1),\ntidyr, withr
    ## ellipsis                                                                                                                                                                                                                                                                                                                                                covr, testthat
    ## encode                                                                                                                                                                                                                                                                                                                                                        magrittr
    ## evaluate                                                                                                                                                                                                                                                                                                                              covr, ggplot2, lattice, testthat
    ## fansi                                                                                                                                                                                                                                                                                                                                       unitizer, knitr, rmarkdown
    ## farver                                                                                                                                                                                                                                                                                                                                       covr, testthat (>= 3.0.0)
    ## fastmap                                                                                                                                                                                                                                                                                                                                            testthat (>= 2.1.1)
    ## fontawesome                                                                                                                                                                                                                                                                                        covr, dplyr (>= 1.0.8), knitr (>= 1.31), testthat (>= 3.0.0),\nrsvg
    ## foreign                                                                                                                                                                                                                                                                                                                                                           <NA>
    ## fs                                                                                                                                                                                                                                                  testthat, covr, pillar (>= 1.0.0), tibble (>= 1.1.0), crayon,\nrmarkdown, knitr, withr, spelling, vctrs (>= 0.3.0)
    ## generics                                                                                                                                                                                                                                                                                                             covr, pkgload, testthat (>= 3.0.0), tibble, withr
    ## gert                                                                                                                                                                                                                                                                                                                              spelling, knitr, rmarkdown, testthat
    ## ggplot2                                                                                  covr, ragg, dplyr, ggplot2movies, hexbin, Hmisc, interp,\nknitr, lattice, mapproj, maps, maptools, multcomp, munsell,\nnlme, profvis, quantreg, RColorBrewer, rgeos, rmarkdown, rpart,\nsf (>= 0.7-3), svglite (>= 1.2.0.9001), testthat (>= 2.1.0),\nvdiffr (>= 1.0.0), xml2
    ## gh                                                                                                                                                                                                                                                                                   covr, knitr, mockery, rmarkdown, rprojroot, spelling,\ntestthat (>= 2.3.2), withr
    ## gitcreds                                                                                                                                                                                                                                                                                             codetools, testthat, knitr, mockery, oskeyring, rmarkdown,\nwithr
    ## glue                                                                                                                                                                      covr, crayon, DBI, dplyr, forcats, ggplot2, knitr, magrittr,\nmicrobenchmark, R.utils, rmarkdown, rprintf, RSQLite, stringr,\ntestthat (>= 3.0.0), vctrs (>= 0.3.0), waldo (>= 0.3.0), withr
    ## graphics                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## grDevices                                                                                                                                                                                                                                                                                                                                                   KernSmooth
    ## grid                                                                                                                                                                                                                                                                                                                                                              <NA>
    ## gtable                                                                                                                                                                                                                                                                                                              covr, testthat, knitr, rmarkdown, ggplot2, profvis
    ## here                                                                                                                                                                                                                                                                conflicted, covr, fs, knitr, palmerpenguins, plyr, readr,\nrlang, rmarkdown, testthat, uuid, withr
    ## highr                                                                                                                                                                                                                                                                                                                                          knitr, markdown, testit
    ## hms                                                                                                                                                                                                                                                                                                          crayon, lubridate, pillar (>= 1.1.0), testthat (>= 3.0.0)
    ## htmltools                                                                                                                                                                                                                                                                                                                markdown, testthat, withr, Cairo, ragg, shiny
    ## htmlwidgets                                                                                                                                                                                                                                                                                                                        knitr (>= 1.8), rmarkdown, testthat
    ## httpuv                                                                                                                                                                                                                                                                                                                                testthat, callr, curl, websocket
    ## httr                                                                                                                                                                                                                                                                                      covr, httpuv, jpeg, knitr, png, readr, rmarkdown, testthat\n(>= 0.8.0), xml2
    ## ini                                                                                                                                                                                                                                                                                                                                                           testthat
    ## isoband                                                                                                                                                                                                                                                                                   covr, ggplot2, knitr, magick, microbenchmark, rmarkdown, sf,\ntestthat, xml2
    ## jquerylib                                                                                                                                                                                                                                                                                                                                                     testthat
    ## jsonlite                                                                                                                                                                                                                                                                                                      httr, curl, vctrs, testthat, knitr, rmarkdown, R.rsp, sf
    ## KernSmooth                                                                                                                                                                                                                                                                                                                                               MASS, carData
    ## knitr                         markdown, formatR, testit, digest, rgl (>= 0.95.1201),\ncodetools, rmarkdown, htmlwidgets (>= 0.7), webshot, tikzDevice\n(>= 0.10), tinytex, reticulate (>= 1.4), JuliaCall (>= 0.11.1),\nmagick, png, jpeg, gifski, xml2 (>= 1.2.0), httr, DBI (>=\n0.4-1), showtext, tibble, sass, bslib, ragg, styler (>= 1.2.0),\ntargets (>= 0.6.0)
    ## labeling                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## later                                                                                                                                                                                                                                                                                                                            knitr, rmarkdown, testthat (>= 2.1.0)
    ## lattice                                                                                                                                                                                                                                                                                                                                 KernSmooth, MASS, latticeExtra
    ## lifecycle                                                                                                                                                                                                                                                                 covr, crayon, lintr, tidyverse, knitr, rmarkdown, testthat\n(>= 3.0.1), tools, tibble, vctrs
    ## lubridate                                                                                                                                                                                                                                                                                                covr, knitr, testthat (>= 2.1.0), vctrs (>= 0.3.0), rmarkdown
    ## magrittr                                                                                                                                                                                                                                                                                                                       covr, knitr, rlang, rmarkdown, testthat
    ## markdown                                                                                                                                                                                                                                                                                                                                                  knitr, RCurl
    ## MASS                                                                                                                                                                                                                                                                                                                                     lattice, nlme, nnet, survival
    ## Matrix                                                                                                                                                                                                                                                                                                                                                      expm, MASS
    ## memoise                                                                                                                                                                                                                                                                                        digest, aws.s3, covr, googleAuthR, googleCloudStorageR, httr,\ntestthat
    ## methods                                                                                                                                                                                                                                                                                                                                                      codetools
    ## mgcv                                                                                                                                                                                                                                                                                                                                          parallel, survival, MASS
    ## mime                                                                                                                                                                                                                                                                                                                                                              <NA>
    ## miniUI                                                                                                                                                                                                                                                                                                                                                            <NA>
    ## munsell                                                                                                                                                                                                                                                                                                                                              ggplot2, testthat
    ## nlme                                                                                                                                                                                                                                                                                                                                             Hmisc, MASS, SASmixed
    ## nnet                                                                                                                                                                                                                                                                                                                                                              MASS
    ## openssl                                                                                                                                                                                                                                                                                   curl, testthat (>= 2.1.0), digest, knitr, rmarkdown,\njsonlite, jose, sodium
    ## parallel                                                                                                                                                                                                                                                                                                                                                       methods
    ## pillar                                                                                                                                        bit64, debugme, DiagrammeR, dplyr, formattable, ggplot2,\nknitr, lubridate, nanotime, nycflights13, palmerpenguins,\nrmarkdown, scales, stringi, survival, testthat (>= 3.1.1),\ntibble, units (>= 0.7.2), vdiffr, withr
    ## pkgbuild                                                                                                                                                                                                                                                                                                                                   Rcpp, cpp11, testthat, covr
    ## pkgconfig                                                                                                                                                                                                                                                                                                                       covr, testthat, disposables (>= 1.0.3)
    ## pkgdown                                                                                                                                                                                 covr, diffviewer, evaluate, htmltools, htmlwidgets, knitr,\nlifecycle, methods, openssl, pkgload (>= 1.0.2), rsconnect,\nrstudioapi, rticles, sass, testthat (>= 3.1.3), tools
    ## pkgload                                                                                                                                                                                                                                                                         bitops, covr, mathjaxr, pak, pkgbuild, Rcpp, remotes,\nrstudioapi, testthat (>= 3.1.0)
    ## plogr                                                                                                                                                                                                                                                                                                                                                             Rcpp
    ## praise                                                                                                                                                                                                                                                                                                                                                        testthat
    ## prettyunits                                                                                                                                                                                                                                                                                                                                  codetools, covr, testthat
    ## processx                                                                                                                                                                                                                                     callr (>= 3.7.0), cli (>= 3.3.0), codetools, covr, curl,\ndebugme, parallel, rlang (>= 1.0.2), testthat (>= 3.0.0), withr
    ## profvis                                                                                                                                                                                                                                                                                               knitr, ggplot2, rmarkdown, testthat, devtools, shiny,\nhtmltools
    ## progress                                                                                                                                                                                                                                                                                                                                         Rcpp, testthat, withr
    ## promises                                                                                                                                                                                                                                                                 testthat, future (>= 1.21.0), fastmap (>= 1.1.0), purrr,\nknitr, rmarkdown, vembedr, spelling
    ## ps                                                                                                                                                                                                                                                                             callr, covr, curl, pillar, pingr, processx (>= 3.1.0), R6,\nrlang, testthat (>= 3.0.0),
    ## purrr                                                                                                                                                                                                                                                                                  covr, crayon, dplyr (>= 0.7.8), knitr, rmarkdown, testthat,\ntibble, tidyselect
    ## R6                                                                                                                                                                                                                                                                                                                                                      testthat, pryr
    ## ragg                                                                                                                                                                                                                                                                                                                                    covr, testthat, grid, graphics
    ## rappdirs                                                                                                                                                                                                                                                                                                                    roxygen2, testthat (>= 3.0.0), covr, withr
    ## rcmdcheck                                                                                                                                                                                                                                                                                  covr, knitr, mockery, processx, ps, rmarkdown, svglite,\ntestthat, webfakes
    ## RColorBrewer                                                                                                                                                                                                                                                                                                                                                      <NA>
    ## Rcpp                                                                                                                                                                                                                                                                                                                tinytest, inline, rbenchmark, pkgKitten (>= 0.1.2)
    ## readr                                                                                                                                                                                                                                             covr, curl, datasets, knitr, rmarkdown, spelling, stringi,\ntestthat (>= 3.1.2), tzdb (>= 0.1.1), waldo, withr, xml2
    ## rematch2                                                                                                                                                                                                                                                                                                                                                covr, testthat
    ## remotes                                                                                                                                                                                                           brew, callr, codetools, curl, covr, git2r (>= 0.23.0), knitr,\nmockery, pkgbuild (>= 1.0.1), pingr, rmarkdown, rprojroot,\ntestthat, webfakes, withr
    ## rlang                                                                                                                                                                                                      cli (>= 3.1.0), covr, crayon, fs, glue, knitr, magrittr,\nmethods, pillar, rmarkdown, stats, testthat (>= 3.0.0), tibble,\nusethis, vctrs (>= 0.2.3), withr
    ## RMariaDB                                                                                                                                                                                                                                                                                                         DBItest (>= 1.7.0), readr, rprojroot, testthat, withr
    ## rmarkdown                                                                                                                                                                                      digest, dygraphs, fs, rsconnect, downlit (>= 0.4.0), katex\n(>= 1.4.0), sass (>= 0.4.0), shiny (>= 1.6.0), testthat (>=\n3.0.3), tibble, tufte, vctrs, withr (>= 2.4.2)
    ## roxygen2                                                                                                                                                                                                                                                                                                 covr, R.methodsS3, R.oo, rmarkdown, testthat (>= 3.1.2), yaml
    ## rpart                                                                                                                                                                                                                                                                                                                                                         survival
    ## rprojroot                                                                                                                                                                                                                                                                                        covr, knitr, lifecycle, mockr, rmarkdown, testthat (>=\n3.0.0), withr
    ## rstudioapi                                                                                                                                                                                                                                                                                                                           testthat, knitr, rmarkdown, clipr
    ## rversions                                                                                                                                                                                                                                                                                                                                            mockery, testthat
    ## sass                                                                                                                                                                                                                                                                                                                    testthat, knitr, rmarkdown, withr, shiny, curl
    ## scales                                                                                                                                                                                                                                                                bit64, covr, dichromat, ggplot2, hms (>= 0.5.0), stringi,\ntestthat (>= 3.0.0), waldo (>= 0.4.0)
    ## sessioninfo                                                                                                                                                                                                                                                                                               callr, covr, mockery, reticulate, rmarkdown, testthat, withr
    ## shiny                                                                                                                                                                                     datasets, Cairo (>= 1.5-5), testthat (>= 3.0.0), knitr (>=\n1.6), markdown, rmarkdown, ggplot2, reactlog (>= 1.0.0),\nmagrittr, yaml, future, dygraphs, ragg, showtext, sass
    ## sourcetools                                                                                                                                                                                                                                                                                                                                                   testthat
    ## spatial                                                                                                                                                                                                                                                                                                                                                           MASS
    ## spec                                                                                                                                                                                                                                                                                                                                                              <NA>
    ## splines                                                                                                                                                                                                                                                                                                                                                Matrix, methods
    ## stats                                                                                                                                                                                                                                                                                                                         MASS, Matrix, SuppDists, methods, stats4
    ## stats4                                                                                                                                                                                                                                                                                                                                                            <NA>
    ## stringi                                                                                                                                                                                                                                                                                                                                                           <NA>
    ## stringr                                                                                                                                                                                                                                                                                                       covr, htmltools, htmlwidgets, knitr, rmarkdown, testthat
    ## survival                                                                                                                                                                                                                                                                                                                                                          <NA>
    ## sys                                                                                                                                                                                                                                                                                                                                  unix (>= 1.4), spelling, testthat
    ## systemfonts                                                                                                                                                                                                                                                                                                         testthat (>= 2.1.0), covr, knitr, rmarkdown, tools
    ## tcltk                                                                                                                                                                                                                                                                                                                                                             <NA>
    ## testthat                                                                                                                                                                                                                                  covr, curl (>= 0.9.5), diffviewer (>= 0.1.0), knitr, mockery,\nrmarkdown, rstudioapi, shiny, usethis, vctrs (>= 0.1.0), xml2
    ## textshaping                                                                                                                                                                                                                                                                                                                                     covr, knitr, rmarkdown
    ## tibble                                                                                                    bench, bit64, blob, brio, callr, cli, covr, crayon (>=\n1.3.4), DiagrammeR, dplyr, evaluate, formattable, ggplot2, hms,\nhtmltools, knitr, lubridate, mockr, nycflights13, pkgbuild,\npkgload, purrr, rmarkdown, stringi, testthat (>= 3.0.2), tidyr,\nwithr
    ## tidyr                                                                                                                                                                                                                                                                covr, data.table, jsonlite, knitr, readr, repurrrsive (>=\n1.0.0), rmarkdown, testthat (>= 3.0.0)
    ## tidyselect                                                                                                                                                                                                                                                             covr, crayon, dplyr, knitr, magrittr, rmarkdown, testthat (>=\n3.1.1), tibble (>= 2.1.3), withr
    ## tinytex                                                                                                                                                                                                                                                                                                                                             testit, rstudioapi
    ## tools                                                                                                                                                                                                                                                                                                codetools, methods, xml2, curl, commonmark, knitr, xfun, mathjaxr
    ## tzdb                                                                                                                                                                                                                                                                                                                                         covr, testthat (>= 3.0.0)
    ## urlchecker                                                                                                                                                                                                                                                                                                                                                        covr
    ## usethis                                                                                                                                                                                                                               covr, knitr, magick, mockr, pkgload, rmarkdown, roxygen2 (>=\n7.1.2), spelling (>= 1.2), styler (>= 1.2.0), testthat (>=\n3.1.0)
    ## utf8                                                                                                                                                                                                                                                                                                   cli, covr, knitr, rlang, rmarkdown, testthat (>= 3.0.0),\nwithr
    ## utils                                                                                                                                                                                                                                                                                                                                 methods, xml2, commonmark, knitr
    ## vctrs                                                                                                                                                                      bit64, covr, crayon, dplyr (>= 0.8.5), generics, knitr,\npillar (>= 1.4.4), pkgdown (>= 2.0.1), rmarkdown, testthat (>=\n3.0.0), tibble (>= 3.1.3), withr, xml2, waldo (>= 0.2.0),\nzeallot
    ## viridisLite                                                                                                                                                                                                                                                                                                     hexbin (>= 1.27.0), ggplot2 (>= 1.0.1), testthat, covr
    ## vroom                                                                                                                                                             archive, bench (>= 1.1.0), covr, curl, dplyr, forcats, fs,\nggplot2, knitr, patchwork, prettyunits, purrr, rmarkdown,\nrstudioapi, scales, spelling, testthat (>= 2.1.0), tidyr,\nutils, waldo, xml2
    ## waldo                                                                                                                                                                                                                                                                                                                       covr, R6, testthat (>= 3.0.0), withr, xml2
    ## whisker                                                                                                                                                                                                                                                                                                                                                       markdown
    ## withr                                                                                                                                                                                                                                                             callr, covr, DBI, knitr, lattice, methods, rlang, rmarkdown\n(>= 2.12), RSQLite, testthat (>= 3.0.0)
    ## xfun                                                                                                                                                                                                               testit, parallel, codetools, rstudioapi, tinytex (>= 0.30),\nmime, markdown, knitr, htmltools, remotes, pak, rhub, renv,\ncurl, jsonlite, rmarkdown
    ## xml2                                                                                                                                                                                                                                                                                       covr, curl, httr, knitr, magrittr, mockery, rmarkdown,\ntestthat (>= 2.1.0)
    ## xopen                                                                                                                                                                                                                                                                                                                                                     ps, testthat
    ## xtable                                                                                                                                                                                                                                                                                                                                       knitr, plm, zoo, survival
    ## yaml                                                                                                                                                                                                                                                                                                                                                             RUnit
    ## zip                                                                                                                                                                                                                                                                                                                                covr, processx, R6, testthat, withr
    ##                                                                          Enhances
    ## askpass                                                                      <NA>
    ## aws.s3                                                                       <NA>
    ## aws.signature                                                                <NA>
    ## base                                                                         <NA>
    ## base64enc                                                                     png
    ## bit                                                                          <NA>
    ## bit64                                                                        <NA>
    ## blob                                                                         <NA>
    ## boot                                                                         <NA>
    ## brew                                                                         <NA>
    ## brio                                                                         <NA>
    ## bslib                                                                        <NA>
    ## cachem                                                                       <NA>
    ## callr                                                                        <NA>
    ## class                                                                        <NA>
    ## cli                                                                          <NA>
    ## clipr                                                                        <NA>
    ## cluster                                                                      <NA>
    ## codetools                                                                    <NA>
    ## colorspace                                                                   <NA>
    ## commonmark                                                                   <NA>
    ## compiler                                                                     <NA>
    ## cpp11                                                                        <NA>
    ## crayon                                                                       <NA>
    ## credentials                                                                  <NA>
    ## csv                                                                          <NA>
    ## curl                                                                         <NA>
    ## data.table                                                                   <NA>
    ## datasets                                                                     <NA>
    ## DBI                                                                          <NA>
    ## desc                                                                         <NA>
    ## devtools                                                                     <NA>
    ## diffobj                                                                      <NA>
    ## digest                                                                       <NA>
    ## downlit                                                                      <NA>
    ## dplyr                                                                        <NA>
    ## ellipsis                                                                     <NA>
    ## encode                                                                       <NA>
    ## evaluate                                                                     <NA>
    ## fansi                                                                        <NA>
    ## farver                                                                       <NA>
    ## fastmap                                                                      <NA>
    ## fontawesome                                                                  <NA>
    ## foreign                                                                      <NA>
    ## fs                                                                           <NA>
    ## generics                                                                     <NA>
    ## gert                                                                         <NA>
    ## ggplot2                                                                        sp
    ## gh                                                                           <NA>
    ## gitcreds                                                                     <NA>
    ## glue                                                                         <NA>
    ## graphics                                                                     <NA>
    ## grDevices                                                                    <NA>
    ## grid                                                                         <NA>
    ## gtable                                                                       <NA>
    ## here                                                                         <NA>
    ## highr                                                                        <NA>
    ## hms                                                                          <NA>
    ## htmltools                                                                   knitr
    ## htmlwidgets                                                        shiny (>= 1.1)
    ## httpuv                                                                       <NA>
    ## httr                                                                         <NA>
    ## ini                                                                          <NA>
    ## isoband                                                                      <NA>
    ## jquerylib                                                                    <NA>
    ## jsonlite                                                                     <NA>
    ## KernSmooth                                                                   <NA>
    ## knitr                                                                        <NA>
    ## labeling                                                                     <NA>
    ## later                                                                        <NA>
    ## lattice                                                                     chron
    ## lifecycle                                                                    <NA>
    ## lubridate                                               chron, timeDate, tis, zoo
    ## magrittr                                                                     <NA>
    ## markdown                                                                     <NA>
    ## MASS                                                                         <NA>
    ## Matrix        MatrixModels, graph, SparseM, sfsmisc, igraph, maptools, sp,\nspdep
    ## memoise                                                                      <NA>
    ## methods                                                                      <NA>
    ## mgcv                                                                         <NA>
    ## mime                                                                         <NA>
    ## miniUI                                                                       <NA>
    ## munsell                                                                      <NA>
    ## nlme                                                                         <NA>
    ## nnet                                                                         <NA>
    ## openssl                                                                      <NA>
    ## parallel                                                          snow, nws, Rmpi
    ## pillar                                                                       <NA>
    ## pkgbuild                                                                     <NA>
    ## pkgconfig                                                                    <NA>
    ## pkgdown                                                                      <NA>
    ## pkgload                                                                      <NA>
    ## plogr                                                                        <NA>
    ## praise                                                                       <NA>
    ## prettyunits                                                                  <NA>
    ## processx                                                                     <NA>
    ## profvis                                                                      <NA>
    ## progress                                                                     <NA>
    ## promises                                                                     <NA>
    ## ps                                                                           <NA>
    ## purrr                                                                        <NA>
    ## R6                                                                           <NA>
    ## ragg                                                                         <NA>
    ## rappdirs                                                                     <NA>
    ## rcmdcheck                                                                    <NA>
    ## RColorBrewer                                                                 <NA>
    ## Rcpp                                                                         <NA>
    ## readr                                                                        <NA>
    ## rematch2                                                                     <NA>
    ## remotes                                                                      <NA>
    ## rlang                                                                       winch
    ## RMariaDB                                                                     <NA>
    ## rmarkdown                                                                    <NA>
    ## roxygen2                                                                     <NA>
    ## rpart                                                                        <NA>
    ## rprojroot                                                                    <NA>
    ## rstudioapi                                                                   <NA>
    ## rversions                                                                    <NA>
    ## sass                                                                         <NA>
    ## scales                                                                       <NA>
    ## sessioninfo                                                                  <NA>
    ## shiny                                                                        <NA>
    ## sourcetools                                                                  <NA>
    ## spatial                                                                      <NA>
    ## spec                                                                         <NA>
    ## splines                                                                      <NA>
    ## stats                                                                        <NA>
    ## stats4                                                                       <NA>
    ## stringi                                                                      <NA>
    ## stringr                                                                      <NA>
    ## survival                                                                     <NA>
    ## sys                                                                          <NA>
    ## systemfonts                                                                  <NA>
    ## tcltk                                                                        <NA>
    ## testthat                                                                     <NA>
    ## textshaping                                                                  <NA>
    ## tibble                                                                       <NA>
    ## tidyr                                                                        <NA>
    ## tidyselect                                                                   <NA>
    ## tinytex                                                                      <NA>
    ## tools                                                                        <NA>
    ## tzdb                                                                         <NA>
    ## urlchecker                                                                   <NA>
    ## usethis                                                                      <NA>
    ## utf8                                                                         <NA>
    ## utils                                                                        <NA>
    ## vctrs                                                                        <NA>
    ## viridisLite                                                                  <NA>
    ## vroom                                                                        <NA>
    ## waldo                                                                        <NA>
    ## whisker                                                                      <NA>
    ## withr                                                                        <NA>
    ## xfun                                                                         <NA>
    ## xml2                                                                         <NA>
    ## xopen                                                                        <NA>
    ## xtable                                                                       <NA>
    ## yaml                                                                         <NA>
    ## zip                                                                          <NA>
    ##                                              License License_is_FOSS
    ## askpass                           MIT + file LICENSE            <NA>
    ## aws.s3                                    GPL (>= 2)            <NA>
    ## aws.signature                             GPL (>= 2)            <NA>
    ## base                                 Part of R 4.2.1            <NA>
    ## base64enc                              GPL-2 | GPL-3            <NA>
    ## bit                                    GPL-2 | GPL-3            <NA>
    ## bit64                                  GPL-2 | GPL-3            <NA>
    ## blob                              MIT + file LICENSE            <NA>
    ## boot                                       Unlimited            <NA>
    ## brew                                           GPL-2            <NA>
    ## brio                              MIT + file LICENSE            <NA>
    ## bslib                             MIT + file LICENSE            <NA>
    ## cachem                            MIT + file LICENSE            <NA>
    ## callr                             MIT + file LICENSE            <NA>
    ## class                                  GPL-2 | GPL-3            <NA>
    ## cli                               MIT + file LICENSE            <NA>
    ## clipr                                          GPL-3            <NA>
    ## cluster                                   GPL (>= 2)            <NA>
    ## codetools                                        GPL            <NA>
    ## colorspace               BSD_3_clause + file LICENSE            <NA>
    ## commonmark               BSD_2_clause + file LICENSE            <NA>
    ## compiler                             Part of R 4.2.1            <NA>
    ## cpp11                             MIT + file LICENSE            <NA>
    ## crayon                            MIT + file LICENSE            <NA>
    ## credentials                       MIT + file LICENSE            <NA>
    ## csv                                            GPL-3            <NA>
    ## curl                              MIT + file LICENSE            <NA>
    ## data.table                    MPL-2.0 | file LICENSE            <NA>
    ## datasets                             Part of R 4.2.1            <NA>
    ## DBI                                    LGPL (>= 2.1)            <NA>
    ## desc                              MIT + file LICENSE            <NA>
    ## devtools                          MIT + file LICENSE            <NA>
    ## diffobj                                GPL-2 | GPL-3            <NA>
    ## digest                                    GPL (>= 2)            <NA>
    ## downlit                           MIT + file LICENSE            <NA>
    ## dplyr                             MIT + file LICENSE            <NA>
    ## ellipsis                          MIT + file LICENSE            <NA>
    ## encode                                         GPL-3            <NA>
    ## evaluate                          MIT + file LICENSE            <NA>
    ## fansi                                  GPL-2 | GPL-3            <NA>
    ## farver                            MIT + file LICENSE            <NA>
    ## fastmap                           MIT + file LICENSE            <NA>
    ## fontawesome                       MIT + file LICENSE            <NA>
    ## foreign                                   GPL (>= 2)            <NA>
    ## fs                                MIT + file LICENSE            <NA>
    ## generics                          MIT + file LICENSE            <NA>
    ## gert                              MIT + file LICENSE            <NA>
    ## ggplot2                           MIT + file LICENSE            <NA>
    ## gh                                MIT + file LICENSE            <NA>
    ## gitcreds                          MIT + file LICENSE            <NA>
    ## glue                              MIT + file LICENSE            <NA>
    ## graphics                             Part of R 4.2.1            <NA>
    ## grDevices                            Part of R 4.2.1            <NA>
    ## grid                                 Part of R 4.2.1            <NA>
    ## gtable                                         GPL-2            <NA>
    ## here                              MIT + file LICENSE            <NA>
    ## highr                                            GPL            <NA>
    ## hms                               MIT + file LICENSE            <NA>
    ## htmltools                                 GPL (>= 2)            <NA>
    ## htmlwidgets                       MIT + file LICENSE            <NA>
    ## httpuv                     GPL (>= 2) | file LICENSE            <NA>
    ## httr                              MIT + file LICENSE            <NA>
    ## ini                                            GPL-3            <NA>
    ## isoband                           MIT + file LICENSE            <NA>
    ## jquerylib                         MIT + file LICENSE            <NA>
    ## jsonlite                          MIT + file LICENSE            <NA>
    ## KernSmooth                                 Unlimited            <NA>
    ## knitr                                            GPL            <NA>
    ## labeling              MIT + file LICENSE | Unlimited            <NA>
    ## later                             MIT + file LICENSE            <NA>
    ## lattice                                   GPL (>= 2)            <NA>
    ## lifecycle                         MIT + file LICENSE            <NA>
    ## lubridate                                 GPL (>= 2)            <NA>
    ## magrittr                          MIT + file LICENSE            <NA>
    ## markdown                                       GPL-2            <NA>
    ## MASS                                   GPL-2 | GPL-3            <NA>
    ## Matrix                     GPL (>= 2) | file LICENCE            <NA>
    ## memoise                           MIT + file LICENSE            <NA>
    ## methods                              Part of R 4.2.1            <NA>
    ## mgcv                                      GPL (>= 2)            <NA>
    ## mime                                             GPL            <NA>
    ## miniUI                                         GPL-3            <NA>
    ## munsell                           MIT + file LICENSE            <NA>
    ## nlme                                      GPL (>= 2)            <NA>
    ## nnet                                   GPL-2 | GPL-3            <NA>
    ## openssl                           MIT + file LICENSE            <NA>
    ## parallel                             Part of R 4.2.1            <NA>
    ## pillar                            MIT + file LICENSE            <NA>
    ## pkgbuild                          MIT + file LICENSE            <NA>
    ## pkgconfig                         MIT + file LICENSE            <NA>
    ## pkgdown                           MIT + file LICENSE            <NA>
    ## pkgload                                        GPL-3            <NA>
    ## plogr                             MIT + file LICENSE            <NA>
    ## praise                            MIT + file LICENSE            <NA>
    ## prettyunits                       MIT + file LICENSE            <NA>
    ## processx                          MIT + file LICENSE            <NA>
    ## profvis                         GPL-3 | file LICENSE            <NA>
    ## progress                          MIT + file LICENSE            <NA>
    ## promises                          MIT + file LICENSE            <NA>
    ## ps                                MIT + file LICENSE            <NA>
    ## purrr                           GPL-3 | file LICENSE            <NA>
    ## R6                                MIT + file LICENSE            <NA>
    ## ragg                              MIT + file LICENSE            <NA>
    ## rappdirs                          MIT + file LICENSE            <NA>
    ## rcmdcheck                         MIT + file LICENSE            <NA>
    ## RColorBrewer                      Apache License 2.0            <NA>
    ## Rcpp                                      GPL (>= 2)            <NA>
    ## readr                             MIT + file LICENSE            <NA>
    ## rematch2                          MIT + file LICENSE            <NA>
    ## remotes                           MIT + file LICENSE            <NA>
    ## rlang                             MIT + file LICENSE            <NA>
    ## RMariaDB                          MIT + file LICENSE            <NA>
    ## rmarkdown                                      GPL-3            <NA>
    ## roxygen2                          MIT + file LICENSE            <NA>
    ## rpart                                  GPL-2 | GPL-3            <NA>
    ## rprojroot                         MIT + file LICENSE            <NA>
    ## rstudioapi                        MIT + file LICENSE            <NA>
    ## rversions                         MIT + file LICENSE            <NA>
    ## sass                              MIT + file LICENSE            <NA>
    ## scales                            MIT + file LICENSE            <NA>
    ## sessioninfo                                    GPL-2            <NA>
    ## shiny                           GPL-3 | file LICENSE            <NA>
    ## sourcetools                       MIT + file LICENSE            <NA>
    ## spatial                                GPL-2 | GPL-3            <NA>
    ## spec                                           GPL-3            <NA>
    ## splines                              Part of R 4.2.1            <NA>
    ## stats                                Part of R 4.2.1            <NA>
    ## stats4                               Part of R 4.2.1            <NA>
    ## stringi                                 file LICENSE            <NA>
    ## stringr                         GPL-2 | file LICENSE            <NA>
    ## survival                                 LGPL (>= 2)            <NA>
    ## sys                               MIT + file LICENSE            <NA>
    ## systemfonts                       MIT + file LICENSE            <NA>
    ## tcltk                                Part of R 4.2.1            <NA>
    ## testthat                          MIT + file LICENSE            <NA>
    ## textshaping                       MIT + file LICENSE            <NA>
    ## tibble                            MIT + file LICENSE            <NA>
    ## tidyr                             MIT + file LICENSE            <NA>
    ## tidyselect                        MIT + file LICENSE            <NA>
    ## tinytex                           MIT + file LICENSE            <NA>
    ## tools                                Part of R 4.2.1            <NA>
    ## tzdb                              MIT + file LICENSE            <NA>
    ## urlchecker                                     GPL-3            <NA>
    ## usethis                           MIT + file LICENSE            <NA>
    ## utf8          Apache License (== 2.0) | file LICENSE            <NA>
    ## utils                                Part of R 4.2.1            <NA>
    ## vctrs                             MIT + file LICENSE            <NA>
    ## viridisLite                       MIT + file LICENSE            <NA>
    ## vroom                             MIT + file LICENSE            <NA>
    ## waldo                             MIT + file LICENSE            <NA>
    ## whisker                                        GPL-3            <NA>
    ## withr                             MIT + file LICENSE            <NA>
    ## xfun                              MIT + file LICENSE            <NA>
    ## xml2                              MIT + file LICENSE            <NA>
    ## xopen                             MIT + file LICENSE            <NA>
    ## xtable                                    GPL (>= 2)            <NA>
    ## yaml                     BSD_3_clause + file LICENSE            <NA>
    ## zip                               MIT + file LICENSE            <NA>
    ##               License_restricts_use OS_type MD5sum NeedsCompilation Built
    ## askpass                        <NA>    <NA>   <NA>              yes 4.2.0
    ## aws.s3                         <NA>    <NA>   <NA>               no 4.2.0
    ## aws.signature                  <NA>    <NA>   <NA>               no 4.2.0
    ## base                           <NA>    <NA>   <NA>             <NA> 4.2.1
    ## base64enc                      <NA>    <NA>   <NA>              yes 4.2.0
    ## bit                            <NA>    <NA>   <NA>              yes 4.2.0
    ## bit64                          <NA>    <NA>   <NA>              yes 4.2.0
    ## blob                           <NA>    <NA>   <NA>               no 4.2.0
    ## boot                           <NA>    <NA>   <NA>               no 4.2.1
    ## brew                           <NA>    <NA>   <NA>               no 4.2.0
    ## brio                           <NA>    <NA>   <NA>              yes 4.2.0
    ## bslib                          <NA>    <NA>   <NA>               no 4.2.0
    ## cachem                         <NA>    <NA>   <NA>              yes 4.2.0
    ## callr                          <NA>    <NA>   <NA>               no 4.2.0
    ## class                          <NA>    <NA>   <NA>              yes 4.2.1
    ## cli                            <NA>    <NA>   <NA>              yes 4.2.0
    ## clipr                          <NA>    <NA>   <NA>               no 4.2.0
    ## cluster                        <NA>    <NA>   <NA>              yes 4.2.1
    ## codetools                      <NA>    <NA>   <NA>               no 4.2.1
    ## colorspace                     <NA>    <NA>   <NA>              yes 4.2.0
    ## commonmark                     <NA>    <NA>   <NA>              yes 4.2.0
    ## compiler                       <NA>    <NA>   <NA>             <NA> 4.2.1
    ## cpp11                          <NA>    <NA>   <NA>               no 4.2.0
    ## crayon                         <NA>    <NA>   <NA>               no 4.2.0
    ## credentials                    <NA>    <NA>   <NA>               no 4.2.0
    ## csv                            <NA>    <NA>   <NA>               no 4.2.0
    ## curl                           <NA>    <NA>   <NA>              yes 4.2.0
    ## data.table                     <NA>    <NA>   <NA>              yes 4.2.0
    ## datasets                       <NA>    <NA>   <NA>             <NA> 4.2.1
    ## DBI                            <NA>    <NA>   <NA>               no 4.2.0
    ## desc                           <NA>    <NA>   <NA>               no 4.2.0
    ## devtools                       <NA>    <NA>   <NA>               no 4.2.0
    ## diffobj                        <NA>    <NA>   <NA>              yes 4.2.0
    ## digest                         <NA>    <NA>   <NA>              yes 4.2.0
    ## downlit                        <NA>    <NA>   <NA>               no 4.2.0
    ## dplyr                          <NA>    <NA>   <NA>              yes 4.2.0
    ## ellipsis                       <NA>    <NA>   <NA>              yes 4.2.0
    ## encode                         <NA>    <NA>   <NA>               no 4.2.0
    ## evaluate                       <NA>    <NA>   <NA>               no 4.2.0
    ## fansi                          <NA>    <NA>   <NA>              yes 4.2.0
    ## farver                         <NA>    <NA>   <NA>              yes 4.2.0
    ## fastmap                        <NA>    <NA>   <NA>              yes 4.2.0
    ## fontawesome                    <NA>    <NA>   <NA>               no 4.2.0
    ## foreign                        <NA>    <NA>   <NA>              yes 4.2.1
    ## fs                             <NA>    <NA>   <NA>              yes 4.2.0
    ## generics                       <NA>    <NA>   <NA>               no 4.2.0
    ## gert                           <NA>    <NA>   <NA>              yes 4.2.0
    ## ggplot2                        <NA>    <NA>   <NA>               no 4.2.0
    ## gh                             <NA>    <NA>   <NA>               no 4.2.0
    ## gitcreds                       <NA>    <NA>   <NA>               no 4.2.0
    ## glue                           <NA>    <NA>   <NA>              yes 4.2.0
    ## graphics                       <NA>    <NA>   <NA>              yes 4.2.1
    ## grDevices                      <NA>    <NA>   <NA>              yes 4.2.1
    ## grid                           <NA>    <NA>   <NA>              yes 4.2.1
    ## gtable                         <NA>    <NA>   <NA>               no 4.2.0
    ## here                           <NA>    <NA>   <NA>               no 4.2.0
    ## highr                          <NA>    <NA>   <NA>               no 4.2.0
    ## hms                            <NA>    <NA>   <NA>               no 4.2.0
    ## htmltools                      <NA>    <NA>   <NA>              yes 4.2.0
    ## htmlwidgets                    <NA>    <NA>   <NA>               no 4.2.0
    ## httpuv                         <NA>    <NA>   <NA>              yes 4.2.0
    ## httr                           <NA>    <NA>   <NA>               no 4.2.0
    ## ini                            <NA>    <NA>   <NA>               no 4.2.0
    ## isoband                        <NA>    <NA>   <NA>              yes 4.2.0
    ## jquerylib                      <NA>    <NA>   <NA>               no 4.2.0
    ## jsonlite                       <NA>    <NA>   <NA>              yes 4.2.0
    ## KernSmooth                     <NA>    <NA>   <NA>              yes 4.2.1
    ## knitr                          <NA>    <NA>   <NA>               no 4.2.0
    ## labeling                       <NA>    <NA>   <NA>               no 4.2.0
    ## later                          <NA>    <NA>   <NA>              yes 4.2.0
    ## lattice                        <NA>    <NA>   <NA>              yes 4.2.1
    ## lifecycle                      <NA>    <NA>   <NA>               no 4.2.0
    ## lubridate                      <NA>    <NA>   <NA>              yes 4.2.0
    ## magrittr                       <NA>    <NA>   <NA>              yes 4.2.0
    ## markdown                       <NA>    <NA>   <NA>              yes 4.2.0
    ## MASS                           <NA>    <NA>   <NA>              yes 4.2.1
    ## Matrix                         <NA>    <NA>   <NA>              yes 4.2.1
    ## memoise                        <NA>    <NA>   <NA>               no 4.2.0
    ## methods                        <NA>    <NA>   <NA>              yes 4.2.1
    ## mgcv                           <NA>    <NA>   <NA>              yes 4.2.1
    ## mime                           <NA>    <NA>   <NA>              yes 4.2.0
    ## miniUI                         <NA>    <NA>   <NA>               no 4.2.0
    ## munsell                        <NA>    <NA>   <NA>               no 4.2.0
    ## nlme                           <NA>    <NA>   <NA>              yes 4.2.1
    ## nnet                           <NA>    <NA>   <NA>              yes 4.2.1
    ## openssl                        <NA>    <NA>   <NA>              yes 4.2.0
    ## parallel                       <NA>    <NA>   <NA>              yes 4.2.1
    ## pillar                         <NA>    <NA>   <NA>               no 4.2.0
    ## pkgbuild                       <NA>    <NA>   <NA>               no 4.2.0
    ## pkgconfig                      <NA>    <NA>   <NA>               no 4.2.0
    ## pkgdown                        <NA>    <NA>   <NA>               no 4.2.0
    ## pkgload                        <NA>    <NA>   <NA>               no 4.2.0
    ## plogr                          <NA>    <NA>   <NA>               no 4.2.0
    ## praise                         <NA>    <NA>   <NA>               no 4.2.0
    ## prettyunits                    <NA>    <NA>   <NA>               no 4.2.0
    ## processx                       <NA>    <NA>   <NA>              yes 4.2.0
    ## profvis                        <NA>    <NA>   <NA>              yes 4.2.0
    ## progress                       <NA>    <NA>   <NA>               no 4.2.0
    ## promises                       <NA>    <NA>   <NA>              yes 4.2.0
    ## ps                             <NA>    <NA>   <NA>              yes 4.2.0
    ## purrr                          <NA>    <NA>   <NA>              yes 4.2.0
    ## R6                             <NA>    <NA>   <NA>               no 4.2.0
    ## ragg                           <NA>    <NA>   <NA>              yes 4.2.0
    ## rappdirs                       <NA>    <NA>   <NA>              yes 4.2.0
    ## rcmdcheck                      <NA>    <NA>   <NA>               no 4.2.0
    ## RColorBrewer                   <NA>    <NA>   <NA>               no 4.2.0
    ## Rcpp                           <NA>    <NA>   <NA>              yes 4.2.0
    ## readr                          <NA>    <NA>   <NA>              yes 4.2.0
    ## rematch2                       <NA>    <NA>   <NA>               no 4.2.0
    ## remotes                        <NA>    <NA>   <NA>               no 4.2.0
    ## rlang                          <NA>    <NA>   <NA>              yes 4.2.0
    ## RMariaDB                       <NA>    <NA>   <NA>              yes 4.2.0
    ## rmarkdown                      <NA>    <NA>   <NA>               no 4.2.0
    ## roxygen2                       <NA>    <NA>   <NA>              yes 4.2.0
    ## rpart                          <NA>    <NA>   <NA>              yes 4.2.1
    ## rprojroot                      <NA>    <NA>   <NA>               no 4.2.0
    ## rstudioapi                     <NA>    <NA>   <NA>               no 4.2.0
    ## rversions                      <NA>    <NA>   <NA>               no 4.2.0
    ## sass                           <NA>    <NA>   <NA>              yes 4.2.0
    ## scales                         <NA>    <NA>   <NA>               no 4.2.0
    ## sessioninfo                    <NA>    <NA>   <NA>               no 4.2.0
    ## shiny                          <NA>    <NA>   <NA>               no 4.2.0
    ## sourcetools                    <NA>    <NA>   <NA>              yes 4.2.0
    ## spatial                        <NA>    <NA>   <NA>              yes 4.2.1
    ## spec                           <NA>    <NA>   <NA>               no 4.2.0
    ## splines                        <NA>    <NA>   <NA>              yes 4.2.1
    ## stats                          <NA>    <NA>   <NA>              yes 4.2.1
    ## stats4                         <NA>    <NA>   <NA>             <NA> 4.2.1
    ## stringi                        <NA>    <NA>   <NA>              yes 4.2.0
    ## stringr                        <NA>    <NA>   <NA>               no 4.2.0
    ## survival                       <NA>    <NA>   <NA>              yes 4.2.1
    ## sys                            <NA>    <NA>   <NA>              yes 4.2.0
    ## systemfonts                    <NA>    <NA>   <NA>              yes 4.2.0
    ## tcltk                          <NA>    <NA>   <NA>              yes 4.2.1
    ## testthat                       <NA>    <NA>   <NA>              yes 4.2.0
    ## textshaping                    <NA>    <NA>   <NA>              yes 4.2.0
    ## tibble                         <NA>    <NA>   <NA>              yes 4.2.0
    ## tidyr                          <NA>    <NA>   <NA>              yes 4.2.0
    ## tidyselect                     <NA>    <NA>   <NA>              yes 4.2.0
    ## tinytex                        <NA>    <NA>   <NA>               no 4.2.0
    ## tools                          <NA>    <NA>   <NA>              yes 4.2.1
    ## tzdb                           <NA>    <NA>   <NA>              yes 4.2.0
    ## urlchecker                     <NA>    <NA>   <NA>               no 4.2.0
    ## usethis                        <NA>    <NA>   <NA>               no 4.2.0
    ## utf8                           <NA>    <NA>   <NA>              yes 4.2.0
    ## utils                          <NA>    <NA>   <NA>              yes 4.2.1
    ## vctrs                          <NA>    <NA>   <NA>              yes 4.2.0
    ## viridisLite                    <NA>    <NA>   <NA>               no 4.2.0
    ## vroom                          <NA>    <NA>   <NA>              yes 4.2.0
    ## waldo                          <NA>    <NA>   <NA>               no 4.2.0
    ## whisker                        <NA>    <NA>   <NA>               no 4.2.0
    ## withr                          <NA>    <NA>   <NA>               no 4.2.0
    ## xfun                           <NA>    <NA>   <NA>              yes 4.2.0
    ## xml2                           <NA>    <NA>   <NA>              yes 4.2.0
    ## xopen                          <NA>    <NA>   <NA>               no 4.2.0
    ## xtable                         <NA>    <NA>   <NA>               no 4.2.0
    ## yaml                           <NA>    <NA>   <NA>              yes 4.2.0
    ## zip                            <NA>    <NA>   <NA>              yes 4.2.0
