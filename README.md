

## pkr Shiny 

<div align="center">
  <a href="https://opensource.org/licenses/mit-license.php">
    <img alt="MIT Licence" src="https://badges.frapsoft.com/os/mit/mit.svg?v=103" />
  </a>
  <a href="https://github.com/ellerbrock/open-source-badge/">
    <img alt="Open Source Love" src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" />
  </a>
</div>

- `pkr Shiny` <https://asan.shinyapps.io/pkrshiny>
- `pkr Shiny` is open to everyone. We are happy to take your input. Please fork the repo, modify the codes and submit a pull request. <https://github.com/asancpt/pkrshiny>
- We are actively developing R pacakges, Shiny Apps, and Edison Science Apps regarding clinical pharmacology and pharmacometrics. Please check here. <https://asancpt.github.io/softwares>

### Installation of pkr R Package

```r
install.packages("pkr")
library(pkr)
NCA(Theoph, "Subject", "Time", "conc", dose=320, uConc="mg/L")
```

### Help

- `pkr` package help <https://cran.r-project.org/web/packages/pkr/pkr.pdf>

### Dataset

- `Theoph`: Oral 320 mg (N=12) <http://stat.ethz.ch/R-manual/R-devel/library/datasets/html/Theoph.html>
- `Indometh`: IV 25 mg (N=6) <http://stat.ethz.ch/R-manual/R-devel/library/datasets/html/Indometh.html>
- `sd_oral_richpk`: Oral 5000mg (N=50) <https://github.com/dpastoor/PKPDdatasets>
- `sd_iv_rich_pkpd`: IV diverse dosing (N=60) <https://github.com/dpastoor/PKPDdatasets>

### CDISC materials

- [CDISC SDTM Implementation Guide 3.2 PDF ](https://www.cdisc.org/sites/default/files/members/standard/foundational/sdtmig/sdtmig_20v3.2_20noportfolio.pdf)
- [CDISC Terminology PDF](https://evs.nci.nih.gov/ftp1/CDISC/SDTM/SDTM%20Terminology.pdf)

### References

Gabrielsson J, Weiner D. Pharmacokinetic and Pharmacodynamic Data Analysis - Concepts and Applications. 5th ed. 2016.

Shargel L, Yu A. Applied Biopharmaceutics and Pharmacokinetics. 7th ed. 2015.

Rowland M, Tozer TN. Clinical Pharmacokinetics and Pharmacodynamics - Concepts and Applications. 4th ed. 2011.

Gibaldi M, Perrier D. Pharmacokinetics. 2nd ed. revised and expanded. 1982.

### Bibliography of R packages

<p>Chang W, Cheng J, Allaire J, Sievert C, Schloerke B, Xie Y, Allen J, McPherson J, Dipert A, Borges B (2022).
<em>shiny: Web Application Framework for R</em>.
R package version 1.7.4, <a href="https://CRAN.R-project.org/package=shiny">https://CRAN.R-project.org/package=shiny</a>. 
</p>
<p>Bae K, Lee JE (2022).
<em>pkr: Pharmacokinetics in R</em>.
R package version 0.1.3, <a href="https://CRAN.R-project.org/package=pkr">https://CRAN.R-project.org/package=pkr</a>. 
</p>
<p>Allaire J, Horner J, Xie Y (2023).
<em>markdown: Render Markdown with 'commonmark'</em>.
R package version 1.5, <a href="https://CRAN.R-project.org/package=markdown">https://CRAN.R-project.org/package=markdown</a>. 
</p>
<p>Grosjean P, Ibanez F (2018).
<em>pastecs: Package for Analysis of Space-Time Ecological Series</em>.
R package version 1.3.21, <a href="https://CRAN.R-project.org/package=pastecs">https://CRAN.R-project.org/package=pastecs</a>. 
</p>
<p>Wickham H (2016).
<em>ggplot2: Elegant Graphics for Data Analysis</em>.
Springer-Verlag New York.
ISBN 978-3-319-24277-4, <a href="https://ggplot2.tidyverse.org">https://ggplot2.tidyverse.org</a>. 
</p>
<p>Wickham H, FranÃ§ois R, Henry L, MÃ¼ller K, Vaughan D (2023).
<em>dplyr: A Grammar of Data Manipulation</em>.
R package version 1.1.0, <a href="https://CRAN.R-project.org/package=dplyr">https://CRAN.R-project.org/package=dplyr</a>. 
</p>
<p>Wickham H, Vaughan D, Girlich M (2023).
<em>tidyr: Tidy Messy Data</em>.
R package version 1.3.0, <a href="https://CRAN.R-project.org/package=tidyr">https://CRAN.R-project.org/package=tidyr</a>. 
</p>
<p>Gohel D, Skintzos P (2023).
<em>ggiraph: Make 'ggplot2' Graphics Interactive</em>.
R package version 0.8.7, <a href="https://CRAN.R-project.org/package=ggiraph">https://CRAN.R-project.org/package=ggiraph</a>. 
</p>
<p>Chang W, Borges Ribeiro B (2021).
<em>shinydashboard: Create Dashboards with 'Shiny'</em>.
R package version 0.7.2, <a href="https://CRAN.R-project.org/package=shinydashboard">https://CRAN.R-project.org/package=shinydashboard</a>. 
</p>
<p>Xie Y (2023).
<em>knitr: A General-Purpose Package for Dynamic Report Generation in R</em>.
R package version 1.42, <a href="https://yihui.org/knitr/">https://yihui.org/knitr/</a>. 
</p>

<p>Xie Y (2015).
<em>Dynamic Documents with R and knitr</em>, 2nd edition.
Chapman and Hall/CRC, Boca Raton, Florida.
ISBN 978-1498716963, <a href="https://yihui.org/knitr/">https://yihui.org/knitr/</a>. 
</p>

<p>Xie Y (2014).
&ldquo;knitr: A Comprehensive Tool for Reproducible Research in R.&rdquo;
In Stodden V, Leisch F, Peng RD (eds.), <em>Implementing Reproducible Computational Research</em>.
Chapman and Hall/CRC.
ISBN 978-1466561595. 
</p>

### Session information


```
## - Session info ------------------------------------------------------------------------------------------
##  setting  value
##  version  R version 4.0.2 (2020-06-22)
##  os       Windows 10 x64 (build 22621)
##  system   x86_64, mingw32
##  ui       RStudio
##  language (EN)
##  collate  English_United States.1252
##  ctype    English_United States.1252
##  tz       America/New_York
##  date     2023-11-18
##  rstudio  2023.03.0+386 Cherry Blossom (desktop)
##  pandoc   2.19.2 @ C:/Program Files/RStudio/resources/app/bin/quarto/bin/tools/ (via rmarkdown)
## 
## - Packages ----------------------------------------------------------------------------------------------
##  package        * version  date (UTC) lib source
##  backports        1.4.1    2021-12-13 [1] CRAN (R 4.0.5)
##  binr           * 1.1.1    2022-06-26 [1] CRAN (R 4.0.2)
##  boot             1.3-25   2020-04-26 [2] CRAN (R 4.0.2)
##  bslib            0.4.2    2022-12-16 [1] CRAN (R 4.0.2)
##  cachem           1.0.7    2023-02-24 [1] CRAN (R 4.0.2)
##  callr            3.7.3    2022-11-02 [1] CRAN (R 4.0.2)
##  checkmate      * 2.2.0    2023-04-27 [1] CRAN (R 4.0.2)
##  cli              3.6.0    2023-01-09 [1] CRAN (R 4.0.2)
##  colorspace       2.1-0    2023-01-23 [1] CRAN (R 4.0.2)
##  commonmark       1.9.0    2023-03-17 [1] CRAN (R 4.0.2)
##  crayon           1.5.2    2022-09-29 [1] CRAN (R 4.0.2)
##  curl             5.0.0    2023-01-12 [1] CRAN (R 4.0.2)
##  desc             1.4.2    2022-09-08 [1] CRAN (R 4.0.2)
##  devtools         2.4.5    2022-10-11 [1] CRAN (R 4.0.2)
##  digest           0.6.31   2022-12-11 [1] CRAN (R 4.0.2)
##  dplyr          * 1.1.0    2023-01-29 [1] CRAN (R 4.0.2)
##  ellipsis         0.3.2    2021-04-29 [1] CRAN (R 4.0.5)
##  evaluate         0.20     2023-01-17 [1] CRAN (R 4.0.2)
##  fansi            1.0.4    2023-01-22 [1] CRAN (R 4.0.2)
##  fastmap          1.1.1    2023-02-24 [1] CRAN (R 4.0.2)
##  foreign        * 0.8-80   2020-05-24 [2] CRAN (R 4.0.2)
##  forestplot     * 2.0.0    2021-08-10 [1] CRAN (R 4.0.2)
##  fs               1.6.1    2023-02-06 [1] CRAN (R 4.0.2)
##  generics         0.1.3    2022-07-05 [1] CRAN (R 4.0.2)
##  ggiraph        * 0.8.7    2023-03-17 [1] CRAN (R 4.0.2)
##  ggplot2        * 3.4.3    2023-08-14 [1] CRAN (R 4.0.2)
##  glue             1.6.2    2022-02-24 [1] CRAN (R 4.0.5)
##  gtable           0.3.1    2022-09-01 [1] CRAN (R 4.0.2)
##  highr            0.10     2022-12-22 [1] CRAN (R 4.0.2)
##  htmltools        0.5.4    2022-12-07 [1] CRAN (R 4.0.2)
##  htmlwidgets      1.6.2    2023-03-17 [1] CRAN (R 4.0.2)
##  httpuv           1.6.9    2023-02-14 [1] CRAN (R 4.0.2)
##  jquerylib        0.1.4    2021-04-26 [1] CRAN (R 4.0.5)
##  jsonlite         1.8.4    2022-12-06 [1] CRAN (R 4.0.2)
##  knitr          * 1.42     2023-01-25 [1] CRAN (R 4.0.2)
##  later            1.3.0    2021-08-18 [1] CRAN (R 4.0.5)
##  lifecycle        1.0.3    2022-10-07 [1] CRAN (R 4.0.2)
##  magrittr       * 2.0.3    2022-03-30 [1] CRAN (R 4.0.5)
##  markdown       * 1.5      2023-01-31 [1] CRAN (R 4.0.2)
##  memoise          2.0.1    2021-11-26 [1] CRAN (R 4.0.5)
##  mime             0.12     2021-09-28 [1] CRAN (R 4.0.5)
##  miniUI           0.1.1.1  2018-05-18 [1] CRAN (R 4.0.5)
##  munsell          0.5.0    2018-06-12 [1] CRAN (R 4.0.5)
##  pastecs        * 1.3.21   2018-03-15 [1] CRAN (R 4.0.5)
##  pillar           1.9.0    2023-03-22 [1] CRAN (R 4.0.2)
##  pkgbuild         1.4.0    2022-11-27 [1] CRAN (R 4.0.2)
##  pkgconfig        2.0.3    2019-09-22 [1] CRAN (R 4.0.5)
##  pkgload          1.3.2    2022-11-16 [1] CRAN (R 4.0.2)
##  pkr            * 0.1.3    2022-06-11 [1] CRAN (R 4.0.2)
##  Polychrome       1.5.1    2022-05-03 [1] CRAN (R 4.0.2)
##  prettyunits      1.1.1    2020-01-24 [1] CRAN (R 4.0.5)
##  processx         3.8.0    2022-10-26 [1] CRAN (R 4.0.2)
##  profvis          0.3.7    2020-11-02 [1] CRAN (R 4.0.5)
##  promises         1.2.0.1  2021-02-11 [1] CRAN (R 4.0.5)
##  ps               1.6.0    2021-02-28 [1] CRAN (R 4.0.5)
##  purrr            1.0.1    2023-01-10 [1] CRAN (R 4.0.2)
##  quickcode      * 0.6      2023-11-15 [1] local
##  R.methodsS3      1.8.2    2022-06-13 [1] CRAN (R 4.0.2)
##  R.oo             1.25.0   2022-06-12 [1] CRAN (R 4.0.2)
##  R6               2.5.1    2021-08-19 [1] CRAN (R 4.0.5)
##  Rcpp             1.0.10   2023-01-22 [1] CRAN (R 4.0.2)
##  remotes          2.4.2    2021-11-30 [1] CRAN (R 4.0.5)
##  rlang            1.1.1    2023-04-28 [1] CRAN (R 4.0.2)
##  rmarkdown        2.20     2023-01-19 [1] CRAN (R 4.0.2)
##  rprojroot        2.0.3    2022-04-02 [1] CRAN (R 4.0.5)
##  rstudioapi       0.14     2022-08-22 [1] CRAN (R 4.0.2)
##  rtf            * 0.4-14.1 2020-03-22 [1] CRAN (R 4.0.5)
##  sass             0.4.5    2023-01-24 [1] CRAN (R 4.0.2)
##  scales           1.2.1    2022-08-20 [1] CRAN (R 4.0.2)
##  scatterplot3d    0.3-44   2023-05-05 [1] CRAN (R 4.0.2)
##  sessioninfo      1.2.2    2021-12-06 [1] CRAN (R 4.0.5)
##  shiny          * 1.7.4    2022-12-15 [1] CRAN (R 4.0.2)
##  shinydashboard * 0.7.2    2021-09-30 [1] CRAN (R 4.0.5)
##  stringi          1.7.12   2023-01-11 [1] CRAN (R 4.0.2)
##  stringr          1.5.0    2022-12-02 [1] CRAN (R 4.0.2)
##  systemfonts      1.0.4    2022-02-11 [1] CRAN (R 4.0.5)
##  tibble           3.2.0    2023-03-08 [1] CRAN (R 4.0.2)
##  tidyr          * 1.3.0    2023-01-24 [1] CRAN (R 4.0.2)
##  tidyselect       1.2.0    2022-10-10 [1] CRAN (R 4.0.2)
##  urlchecker       1.0.1    2021-11-30 [1] CRAN (R 4.0.5)
##  usethis          2.1.6    2022-05-25 [1] CRAN (R 4.0.2)
##  utf8             1.2.3    2023-01-31 [1] CRAN (R 4.0.2)
##  uuid             1.1-0    2022-04-19 [1] CRAN (R 4.0.5)
##  vctrs            0.6.3    2023-06-14 [1] CRAN (R 4.0.2)
##  withr            2.5.0    2022-03-03 [1] CRAN (R 4.0.5)
##  xfun             0.38     2023-03-24 [1] CRAN (R 4.0.2)
##  xtable           1.8-4    2019-04-21 [1] CRAN (R 4.0.5)
##  yaml             2.3.7    2023-01-23 [1] CRAN (R 4.0.2)
## 
##  [1] C:/Users/in198/OneDrive/Documents/R/win-library/4.0
##  [2] C:/Program Files/R/R-4.0.2/library
## 
## ---------------------------------------------------------------------------------------------------------
```

