

# Technical notes {-}

The entire book was written in R Markdown, using the **bookdown**, **rmarkdown**, and **knitr** packages. All figures were made with **ggplot2**, with the help of add-on packages **cowplot**, **egg**, **ggforce**, **ggrepel**, **ggridges**, **sf**, and **treemapify**. Color manipulations were done with the **colorspace** and **colorblindr** packages. For many of these packages, the current development version is required to compile all parts of the book.

The source code for the book is available here: https://github.com/clauswilke/dataviz. The book also requires a supporting R package, **dviz.supp**, whose code is available here: https://github.com/clauswilke/dviz.supp.

The book was last compiled using the following environment:

```
## R version 3.5.0 (2018-04-23)
## Platform: x86_64-apple-darwin15.6.0 (64-bit)
## Running under: macOS Sierra 10.12.6
## 
## Matrix products: default
## BLAS: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRblas.0.dylib
## LAPACK: /Library/Frameworks/R.framework/Versions/3.5/Resources/lib/libRlapack.dylib
## 
## locale:
## [1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8
## 
## attached base packages:
## [1] stats     graphics  grDevices utils     datasets  methods   base     
## 
## other attached packages:
##  [1] nycflights13_0.2.2  gapminder_0.3.0     RColorBrewer_1.1-2 
##  [4] maps_3.2.0          sf_0.6-3            maptools_0.9-2     
##  [7] sp_1.3-1            rgeos_0.3-28        plot3D_1.1.1       
## [10] magick_1.9          hexbin_1.27.2       treemapify_2.4.0   
## [13] gridExtra_2.3       ggthemes_3.4.0      ggridges_0.5.0.9000
## [16] ggrepel_0.8.0       ggforce_0.1.1       patchwork_0.0.1    
## [19] lubridate_1.7.3     forcats_0.3.0       stringr_1.3.1      
## [22] purrr_0.2.5         readr_1.1.1         tidyr_0.8.0        
## [25] tibble_1.4.2        tidyverse_1.2.1     dviz.supp_0.1.0    
## [28] dplyr_0.7.99.9000   colorblindr_0.1.0   ggplot2_3.0.0.9000 
## [31] colorspace_1.4-0    cowplot_0.9.99     
## 
## loaded via a namespace (and not attached):
##  [1] httr_1.3.1        jsonlite_1.5      modelr_0.1.1     
##  [4] assertthat_0.2.0  cellranger_1.1.0  yaml_2.1.18      
##  [7] pillar_1.2.1      backports_1.1.2   lattice_0.20-35  
## [10] glue_1.3.0        digest_0.6.16     polyclip_1.6-1   
## [13] rvest_0.3.2       htmltools_0.3.6   plyr_1.8.4       
## [16] pkgconfig_2.0.2   broom_0.5.0       misc3d_0.8-4     
## [19] haven_1.1.1       bookdown_0.7      scales_1.0.0     
## [22] tweenr_0.1.5.9999 farver_1.0        withr_2.1.2      
## [25] lazyeval_0.2.1    cli_1.0.0         magrittr_1.5     
## [28] crayon_1.3.4      readxl_1.1.0      deldir_0.1-14    
## [31] evaluate_0.10.1   nlme_3.1-137      MASS_7.3-49      
## [34] class_7.3-14      xml2_1.2.0        foreign_0.8-70   
## [37] tools_3.5.0       hms_0.4.2         munsell_0.5.0    
## [40] e1071_1.6-8       compiler_3.5.0    concaveman_1.0.0 
## [43] rlang_0.2.2.9001  classInt_0.2-3    units_0.6-0      
## [46] grid_3.5.0        rstudioapi_0.7    rmarkdown_1.9    
## [49] gtable_0.2.0      DBI_1.0.0         R6_2.2.2         
## [52] knitr_1.20        rprojroot_1.3-2   stringi_1.2.4    
## [55] Rcpp_0.12.18      ggfittext_0.5.0   spData_0.2.8.3   
## [58] tidyselect_0.2.4  xfun_0.1
```
