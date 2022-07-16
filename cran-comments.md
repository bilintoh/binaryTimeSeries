## Resubmission

This is a resubmission. In this version I have:
1. removed all the **dontrun{}** in the examples.
2. made sure all references in the DESCRIPTION file conforms with CRAN
standards.
3. added small files needed for the examples or vignette in the inst/external
sub folder of my package. 
4. added immediate call of on.exit() to **trajPlot** and **presencePlot**  
to reset par parameters when the function is exited.  

## R CMD check results

0 errors | 0 warnings | 1 note

* This is a new release.
