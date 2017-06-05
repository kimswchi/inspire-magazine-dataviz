# Session information and packages used
Soo Wan Kim  
June 4, 2017  


```r
##  setting  value                       
##  version  R version 3.4.0 (2017-04-21)
##  system   x86_64, mingw32             
##  ui       RTerm                       
##  language (EN)                        
##  collate  English_United States.1252  
##  tz       America/Chicago             
##  date     2017-06-04                  
## 
##  package     * version    date       source                               
##  assertthat    0.2.0      2017-04-11 CRAN (R 3.4.0)                       
##  backports     1.1.0      2017-05-22 CRAN (R 3.4.0)                       
##  base        * 3.4.0      2017-04-21 local                                
##  broom         0.4.2      2017-02-13 CRAN (R 3.4.0)                       
##  cellranger    1.1.0      2016-07-27 CRAN (R 3.4.0)                       
##  colorspace    1.3-2      2016-12-14 CRAN (R 3.4.0)                       
##  compiler      3.4.0      2017-04-21 local                                
##  crosstalk     1.0.0      2016-12-21 CRAN (R 3.4.0)                       
##  data.table    1.10.4     2017-02-01 CRAN (R 3.4.0)                       
##  datasets    * 3.4.0      2017-04-21 local                                
##  DBI           0.6-1      2017-04-01 CRAN (R 3.4.0)                       
##  devtools      1.13.2     2017-06-02 CRAN (R 3.4.0)                       
##  digest        0.6.12     2017-01-27 CRAN (R 3.4.0)                       
##  dplyr       * 0.5.0      2016-06-24 CRAN (R 3.4.0)                       
##  evaluate      0.10       2016-10-11 CRAN (R 3.4.0)                       
##  forcats       0.2.0      2017-01-23 CRAN (R 3.4.0)                       
##  foreign       0.8-67     2016-09-13 CRAN (R 3.4.0)                       
##  ggplot2     * 2.2.1.9000 2017-06-04 Github (hadley/ggplot2@eedaa81)      
##  ggthemes    * 3.4.0      2017-02-19 CRAN (R 3.4.0)                       
##  graphics    * 3.4.0      2017-04-21 local                                
##  grDevices   * 3.4.0      2017-04-21 local                                
##  grid          3.4.0      2017-04-21 local                                
##  gtable        0.2.0      2016-02-26 CRAN (R 3.4.0)                       
##  haven         1.0.0      2016-09-23 CRAN (R 3.4.0)                       
##  hms           0.3        2016-11-22 CRAN (R 3.4.0)                       
##  htmltools     0.3.6      2017-04-28 CRAN (R 3.4.0)                       
##  htmlwidgets   0.8        2016-11-09 CRAN (R 3.4.0)                       
##  httpuv        1.3.3      2015-08-04 CRAN (R 3.4.0)                       
##  httr          1.2.1      2016-07-03 CRAN (R 3.4.0)                       
##  jsonlite      1.4        2017-04-08 CRAN (R 3.4.0)                       
##  kableExtra  * 0.2.1      2017-05-25 CRAN (R 3.4.0)                       
##  knitr       * 1.16       2017-05-18 CRAN (R 3.4.0)                       
##  lattice       0.20-35    2017-03-25 CRAN (R 3.4.0)                       
##  lazyeval      0.2.0      2016-06-12 CRAN (R 3.4.0)                       
##  lubridate   * 1.6.0      2016-09-13 CRAN (R 3.4.0)                       
##  magrittr      1.5        2014-11-22 CRAN (R 3.4.0)                       
##  memoise       1.1.0      2017-04-21 CRAN (R 3.4.0)                       
##  methods     * 3.4.0      2017-04-21 local                                
##  mime          0.5        2016-07-07 CRAN (R 3.4.0)                       
##  mnormt        1.5-5      2016-10-15 CRAN (R 3.4.0)                       
##  modelr        0.1.0      2016-08-31 CRAN (R 3.4.0)                       
##  munsell       0.4.3      2016-02-13 CRAN (R 3.4.0)                       
##  nlme          3.1-131    2017-02-06 CRAN (R 3.4.0)                       
##  parallel      3.4.0      2017-04-21 local                                
##  plotly      * 4.7.0      2017-05-28 CRAN (R 3.4.0)                       
##  plyr          1.8.4      2016-06-08 CRAN (R 3.4.0)                       
##  psych         1.7.5      2017-05-03 CRAN (R 3.4.0)                       
##  purrr       * 0.2.2.2    2017-05-11 CRAN (R 3.4.0)                       
##  R6            2.2.1      2017-05-10 CRAN (R 3.4.0)                       
##  Rcpp          0.12.11    2017-05-22 CRAN (R 3.4.0)                       
##  readr       * 1.1.1      2017-05-16 CRAN (R 3.4.0)                       
##  readxl        1.0.0      2017-04-18 CRAN (R 3.4.0)                       
##  reshape2      1.4.2      2016-10-22 CRAN (R 3.4.0)                       
##  rlang         0.1.1      2017-05-18 CRAN (R 3.4.0)                       
##  rmarkdown     1.5        2017-04-26 CRAN (R 3.4.0)                       
##  rprojroot     1.2        2017-01-16 CRAN (R 3.4.0)                       
##  rvest         0.3.2      2016-06-17 CRAN (R 3.4.0)                       
##  scales      * 0.4.1      2016-11-09 CRAN (R 3.4.0)                       
##  shiny         1.0.3      2017-04-26 CRAN (R 3.4.0)                       
##  stats       * 3.4.0      2017-04-21 local                                
##  streamgraph * 0.8.1      2017-06-04 Github (hrbrmstr/streamgraph@16aee37)
##  stringi       1.1.5      2017-04-07 CRAN (R 3.4.0)                       
##  stringr     * 1.2.0      2017-02-18 CRAN (R 3.4.0)                       
##  tibble      * 1.3.3      2017-05-28 CRAN (R 3.4.0)                       
##  tidyr       * 0.6.3      2017-05-15 CRAN (R 3.4.0)                       
##  tidyverse   * 1.1.1      2017-01-27 CRAN (R 3.4.0)                       
##  tools         3.4.0      2017-04-21 local                                
##  utils       * 3.4.0      2017-04-21 local                                
##  viridisLite   0.2.0      2017-03-24 CRAN (R 3.4.0)                       
##  withr         1.0.2      2016-06-20 CRAN (R 3.4.0)                       
##  xml2          1.1.1      2017-01-24 CRAN (R 3.4.0)                       
##  xtable        1.8-2      2016-02-05 CRAN (R 3.4.0)                       
##  xts           0.9-7      2014-01-02 CRAN (R 3.4.0)                       
##  yaml          2.1.14     2016-11-12 CRAN (R 3.4.0)                       
##  zoo           1.8-0      2017-04-12 CRAN (R 3.4.0)
```

