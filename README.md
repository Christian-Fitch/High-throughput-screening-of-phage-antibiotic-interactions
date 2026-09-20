# High-throughput-screening-of-phage-antibiotic-interactions

This is the data and manuscript accompanying Chapter 2 of my PhD thesis; High throughput screening of phage-antibiotic interactions. Please note, so that the manuscript is not published in advance of submission, the quarto document itself will be uploaded when possible - until this time, this repository will only include raw data.

Document creation, data visualisation, and associated data analysis was generated in Quarto using RStudio. All data is located within the /rawdata directory, and organised into folders dependent on where they lie in the manuscript. Should quarto be running correctly, the entire manuscript should be re-creatable.

Session info is auto-generated based on your R session, so I have pasted my session below. Most importantly the R version was R 4.4.1, RStudio version 2023.06.0 Build 421, and Quarto version 1.4.554.

R version 4.4.1 (2024-06-14 ucrt)
Platform: x86_64-w64-mingw32/x64
Running under: Windows 11 x64 (build 26100)

Matrix products: default


locale:
[1] LC_COLLATE=English_United Kingdom.utf8 
[2] LC_CTYPE=English_United Kingdom.utf8   
[3] LC_MONETARY=English_United Kingdom.utf8
[4] LC_NUMERIC=C                           
[5] LC_TIME=English_United Kingdom.utf8    

time zone: Europe/London
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices
[4] utils     datasets  methods  
[7] base     

other attached packages:
 [1] mgcv_1.9-1        
 [2] nlme_3.1-168      
 [3] growthcurver_0.3.1
 [4] car_3.1-3         
 [5] carData_3.0-5     
 [6] ggfortify_0.4.19  
 [7] gt_1.2.0          
 [8] DescTools_0.99.60 
 [9] boot_1.3-30       
[10] cowplot_1.2.0     
[11] lubridate_1.9.4   
[12] forcats_1.0.1     
[13] stringr_1.6.0     
[14] dplyr_1.1.4       
[15] purrr_1.2.1       
[16] readr_2.1.6       
[17] tidyr_1.3.2       
[18] tibble_3.2.1      
[19] ggplot2_3.5.2     
[20] tidyverse_2.0.0   
[21] lmerTest_3.2-1    
[22] lme4_1.1-37       
[23] Matrix_1.7-0      

loaded via a namespace (and not attached):
 [1] Rdpack_2.6.4       
 [2] gridExtra_2.3      
 [3] gld_2.6.8          
 [4] remotes_2.5.0      
 [5] readxl_1.4.5       
 [6] rlang_1.2.0        
 [7] magrittr_2.0.3     
 [8] otel_0.2.0         
 [9] e1071_1.7-17       
[10] compiler_4.4.1     
[11] vctrs_0.6.5        
[12] pkgconfig_2.0.3    
[13] fastmap_1.2.0      
[14] magick_2.9.0       
[15] labeling_0.4.3     
[16] sessioninfo_1.2.3  
[17] tzdb_0.5.0         
[18] haven_2.5.5        
[19] nloptr_2.2.1       
[20] xfun_0.56          
[21] aplot_0.2.9        
[22] jsonlite_2.0.0     
[23] parallel_4.4.1     
[24] R6_2.6.1           
[25] stringi_1.8.7      
[26] RColorBrewer_1.1-3 
[27] cellranger_1.1.0   
[28] numDeriv_2016.8-1.1
[29] Rcpp_1.1.1         
[30] knitr_1.51         
[31] splines_4.4.1      
[32] timechange_0.3.0   
[33] tidyselect_1.2.1   
[34] rstudioapi_0.18.0  
[35] dichromat_2.0-0.1  
[36] abind_1.4-8        
[37] lattice_0.22-6     
[38] treeio_1.30.0      
[39] withr_3.0.2        
[40] S7_0.2.0           
[41] evaluate_1.0.5     
[42] gridGraphics_0.5-1 
[43] proxy_0.4-29       
[44] xml2_1.5.2         
[45] pillar_1.11.1      
[46] ggtree_3.14.0      
[47] reformulas_0.4.3.1 
[48] ggfun_0.2.0        
[49] generics_0.1.4     
[50] hms_1.1.4          
[51] scales_1.4.0       
[52] tidytree_0.4.7     
[53] rootSolve_1.8.2.4  
[54] minqa_1.2.8        
[55] class_7.3-22       
[56] glue_1.7.0         
[57] lmom_3.2           
[58] lazyeval_0.2.2     
[59] tools_4.4.1        
[60] data.table_1.18.0  
[61] Exact_3.3          
[62] fs_1.6.6           
[63] mvtnorm_1.3-3      
[64] grid_4.4.1         
[65] ape_5.8-1          
[66] rbibutils_2.3      
[67] wesanderson_0.3.7  
[68] patchwork_1.3.2    
[69] Formula_1.2-5      
[70] cli_3.6.6          
[71] rappdirs_0.3.4     
[72] expm_1.0-0         
[73] gtable_0.3.6       
[74] yulab.utils_0.2.3  
[75] digest_0.6.39      
[76] ggplotify_0.1.3    
[77] farver_2.1.2       
[78] htmltools_0.5.9    
[79] lifecycle_1.0.5    
[80] httr_1.4.7         
[81] MASS_7.3-65   
