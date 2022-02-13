# freelist-tutorial

Repository for: 
**Cognitive and cultural models in psychological science: A tutorial on modeling free-list data as a dependent variable in Bayesian regression**

`freelist_tutorial.pdf`: preprint of main manuscript (also available at https://psyarxiv.com/4n2jm)

`freelist_tutorial_appendix.pdf`: preprint of appendices

`FreeList_CERC_V1.0.csv` contains free-list data and `CERC Dataset (Wave 1) Version 6.0.csv`
contains item scale data as well as various demographic information. See main repository for further
details (Wave 1): https://github.com/bgpurzycki/Evolution-of-Religion-and-Morality

`freelist_tutorial.R` reproduces the full main manuscript, including model fits, tables, and figures.

`freelist_tutorial_appendix.Rmd` reproduces the appendices, including model fits, tables, and figures.
Note that the appendix script depends on having fitted all models from the 
main `freelist_tutorial.Rmd` script, which creates the file `all_main_mods.RData`.

`grateful-refs.bib` and `tutorial-bib.bib` contain the bibliographies.

Note that due to the number of models, rendering the `.Rmd` files are quite computationally 
intensive and may take a day or two, depending on hardware.

The `.Rmd` files require the following software and their dependencies:
 - `R`: https://cran.r-project.org/bin/windows/base/
 - `RStudio`: https://www.rstudio.com/products/rstudio/
 - `R Markdown`: https://rmarkdown.rstudio.com/
 - `renv`: https://cran.r-project.org/web/packages/renv/index.html
 - `papaja`: https://crsh.github.io/papaja_man/introduction.html

Appendix D lists all `R` packages, their dependencies, and version number used for this project.

Additional system details:
 - `version  R version 4.1.2 (2021-11-01)`
 - `os       Windows 10 x64 (build 19043)`
 - `system   x86_64, mingw32`
 - `rstudio  2021.09.2+382 Ghost Orchid (desktop)`
 - `pandoc   2.17.1.1 @ C:/PROGRA~1/Pandoc/ (via rmarkdown)`

Feedback is very welcome! Contact: tb@cas.au.dk
