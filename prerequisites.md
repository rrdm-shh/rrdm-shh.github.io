Participants should bring a laptop with an up to date Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on. If you have already installed these programs, please make sure you have the most recent versions. If you have questions, please contact us before the workshop.

# Softwares to install

*Generally necessary*

- A **bash terminal**  
    For Ubuntu and Mac users, this comes pre-installed.  
    For windows users, we encourage you to have a look at the [Windows subsytem for linux](https://www.howtogeek.com/249966/how-to-install-and-use-the-linux-bash-shell-on-windows-10/).
- **Git**  
    If git is not yet installed on your system, we encourage to have a look at [this guide](https://www.atlassian.com/git/tutorials/install-git).
- **Github**  
    You need a free account for the Website Github. Please register [here](https://github.com/join).
    
*For "Runtime reproducibility with Conda and Jupyter" and "Make/Snakemake"*
    
- **Conda**
    We recommend you to install **miniconda** on your system. The install guide can be found here for [Windows](https://conda.io/projects/conda/en/latest/user-guide/install/windows.html), [Mac](https://conda.io/projects/conda/en/latest/user-guide/install/macos.html), and [Linux](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html)

*For "Research Compendia with R". If you do not want to install this software, you can also follow this tutorial in an RStudio Cloud session in the browser*

- **R**  
    Windows: Install R by downloading and running [this .exe file](https://cran.r-project.org/bin/windows/base/release.htm) from [CRAN](https://cran.r-project.org/index.html). You will also need to download and install the [Rtools](https://cran.r-project.org/bin/windows/Rtools/Rtools35.exe) software package. 
    Mac: Install R by downloading and running [this .pkg file](https://cran.r-project.org/bin/macosx/R-latest.pkg) from [CRAN](https://cran.r-project.org/index.html).  
    Linux: You can download the binary files for your distribution from [CRAN](https://cran.r-project.org/index.html). Or you can use your package manager (e.g. for Debian/Ubuntu run `sudo apt-get install r-base` and for Fedora run `sudo dnf install R`).

- **RStudio**  
    Rstudio can be downloaded and installed [here](https://www.rstudio.com/products/rstudio/download/#download). For Windows users: If you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.

- **R packages**  
    R contains an own, operating-system agnostic software package management. You should install the following packages:  
    **devtools, tidyverse, evaluate, digest, highr, markdown, stringr, yaml, Rcpp, htmltools, knitr, jsonlite, base64enc, mime, rmarkdown** `install.packages(c("devtools", "tidyverse", "evaluate", "digest", "highr", "markdown", "stringr", "yaml", "Rcpp", "htmltools", "knitr", "jsonlite", "base64enc", "mime", "rmarkdown"))`
    You should finally install the main tool for this tutorial:  
    **rrtools** `devtools::install_github("benmarwick/rrtools")`
    
