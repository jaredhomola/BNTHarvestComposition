BNTHarvestComposition (Brown trout harvest composition) is a research
compendium that brings together the data and analyses associated with
Homola et al. 2019, Genetic estimates of jurisdictional and strain
contributions to the northeastern Lake Michigan brown trout sportfishing
harvest, Journal of Great Lakes Research. R scripts are provided in
analysis/, human-readable data in extData/, and R-readable data in an
.rda file in data/.

Note: All analyses originally conducted and package built using R
version 3.5.1 in Windows 10

### To get started using the package

    options(repos=structure(c(CRAN="http://cran.r-project.org")))
    install.packages("devtools")
    library(devtools)
    install_github("jaredhomola/BNTHarvestComposition")

### Scripts in /analysis

1.  buildRDA.R: Build RDA file
2.  installPackages.R: Install required packages
3.  checkPopGenAssumptions.R: Checking usual assumptions (H-W, linkage
    disequalibrium, etc.)
4.  DAPC.R: Discriminant analysis of principal components of hatchery
    and creel samples
5.  diversityAndDifferentiation.R: Measure of genetic diversity and
    differentiation
6.  rubiasAnalysis: RUBIAS genetic stock identification analysis

### Contact

Jared J. Homola  
<jaredhomola20@gmail.com>  
www.jaredhomola.com

#### Copyright (c) 2019 Jared J. Homola

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
