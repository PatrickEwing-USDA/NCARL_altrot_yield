# Diversified rotations can be highly and reliably productive in unstable climates

Analysis from:

Ewing, P.M., Chim, B.K., Lehman, R.M., and Osborne, S.L. *in revision*. Diversified rotations can be highly and reliably productive in unstable climates. *Field Crops Research*. [Journal](link); [Preprint](https://www.cabidigitallibrary.org/doi/10.31220/agriRxiv.2023.00202)

Data was collected from the "Alternative Rotation" managed by [Dr. Shannon Osborne](https://www.ars.usda.gov/people-locations/person/?person-id=12527)
at the USDA-ARS North Central Agricultural Research Laboratory in Brookings, SD USA. The study is still running. 

This is an R repository. Requirements:  
- [R](https://cran.r-project.org/)
- [RTools](https://cran.r-project.org/bin/windows/Rtools/)
- [RStudio](https://posit.co/download/rstudio-desktop/)
- [`renv`](https://rstudio.github.io/renv/articles/renv.html) will manage libraries. Run (in R) `install.packages('renv')`.

To reproduce the analysis:  
1. Clone the repository.
2. Download and install R, RTools, and RStudio.
3. Open the .RProj file in RStudio. Install `renv`.
5. Run `renv::restore()`.
6. Run (knit!) in order, starting with 1a. Note that 1a is pretty slow. 

Or you can just view results that I generated with these notebooks:
- [1a - Process Field Data](https://htmlpreview.github.io/?https://github.com/PatrickEwing-USDA/NCARL_altrot_yield/blob/main/Results/1a---Process-Field-Data.html)
- [1b - Weather Data](https://htmlpreview.github.io/?https://github.com/PatrickEwing-USDA/NCARL_altrot_yield/blob/main/Results/1b---weather-data.html)
- [2 - Productivity and Stability of Rotations](https://htmlpreview.github.io/?https://github.com/PatrickEwing-USDA/NCARL_altrot_yield/blob/main/Results/2---productivity-and-stability-of-rotations.html)
- [3 - Overyielding](https://htmlpreview.github.io/?https://github.com/PatrickEwing-USDA/NCARL_altrot_yield/blob/main/Results/3---overyielding.html)
- [4 - Niche Complementarity](https://htmlpreview.github.io/?https://github.com/PatrickEwing-USDA/NCARL_altrot_yield/blob/main/Results/4---niche-complimentarity.html)

Raw data is in ./Data/Inputs - all other tables are generated. See ./Data/meta.txt for descriptions. Figure code is embedded within each notebook. 

Issues? Ideas? I'd love to hear from you!

**Contact**:  
Patrick Ewing  
Research Agronomist  
USDA-ARS Food Systems Research Unit  
Burlington, VT USA  
patrick.ewing@usda.gov  
[Scholar](https://scholar.google.com/citations?user=ukiVGLsAAAAJ&hl=en)