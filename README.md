# Quarto Blog Template

This is the code that creates the Quarto Blog Template for Dr. Petersen's fantasy football course.
The Quarto Blog Template is located here: **https://isaactpetersen.github.io/QuartoBlogFantasyFootball**

For more information on how to customize your blog, see here: https://quarto.org/docs/websites/website-blog.html

To install all the `R` packages that the textbook uses, run the following code in the console:

```r
install.packages(
  c("petersenlab","remotes","knitr","rmarkdown","dplyr",
    "ggplot2","tidyverse","psych","xfun","downlit","xml2",
    "nflreadr","nflplotR","nflfastR","nflseedR","nfl4th",
    "gsisdecoder","progressr","DescTools","pwr","pwrss",
    "WebPower","XICOR","dagitty","ggdag","lubridate",
    "ggtext","gghighlight","ggExtra","grid","patchwork",
    "pROC","lme4","lmerTest","MuMIn","emmeans","pbkrtest",
    "sjstats","AICcmodavg","rstan","brms","bbmle",
    "fitdistrplus","mclust","magrittr","viridis","viridisLite",
    "msir","plotly","webshot2","quantmod","fPortfolio",
    "xts","zoo","forecast","stringi","parallel","parallelly",
    "doParallel","missRanger","powerjoin","caret","gpboost",
    "ggridges","corrplot","rms","car","caret","performance",
    "correlation","interactions","lavaan","mice","miceadds",
    "robustbase","see"))
```

Some necessary packages, including the [`ffanalytics` package](https://github.com/FantasyFootballAnalytics/ffanalytics), are hosted in GitHub (and are not hosted on the Comprehensive R Archive Network [CRAN]) and thus need to be installed using the following code (after installing the `remotes` package above)[^petersenlabPackageGitHub]:

```r
remotes::install_github("DevPsyLab/petersenlab")
remotes::install_github("FantasyFootballAnalytics/ffanalytics")
remotes::install_github("stan-dev/cmdstanr")
```

[^petersenlabPackageGitHub]: Although the [`petersenlab`](https://cran.r-project.org/web/packages/petersenlab/index.html) package is hosted on CRAN, installing from GitHub will ensure you have the latest version.

# License

[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: https://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg