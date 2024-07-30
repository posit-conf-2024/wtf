What They Forgot To Teach You About R
================

### posit::conf(2024)

by E. David Aja + Shannon Pileggi

[rstats.wtf](https://rstats.wtf)

-----

:spiral_calendar: August 12, 2024  
:alarm_clock:     09:00 - 17:00  
:hotel:           ROOM TBD  
:writing_hand:    [pos.it/conf](http://pos.it/conf)

-----

# Description

This 1 day What They Forgot (WTF) To Teach You About R workshop is for experienced R and RStudio users who want to better understand R execution via debugging and personal R administration. At the conclusion of the workshop you will have distinct strategies for debugging your own code versus someone else's code, as well as strategies for maintaining your R installation through the lens of reproducibility.

# Audience

This course is for you if you:

-   Have you been using R for a while and you want a deeper understanding of what code is executing when and where it is coming from.
-   Want strategies for overcoming roadblocks when when all else has failed in function execution or package installation.
-   Are willing to get into the weeds of your R installation, project organization, error messages, and source code.

## Prework

1. Please have two recent versions of R installed, as well as a recent version of RStudio: 
- one version of R >= 4.1 & R < 4.4
- one version of R >= 4.4
- [RStudio >= 2024.04.1+748](https://posit.co/download/rstudio-desktop/)

You can find older versions of R [at this link for Windows](https://cran.r-project.org/bin/windows/base/old/) (click on the `.exe` file to install), at [this link for Intel Macs](https://cran.r-project.org/bin/macosx/big-sur-x86_64/base/), and at [this link for M-series Macs.](https://cran.r-project.org/bin/macosx/big-sur-arm64/base/)

See the discussion in Install or upgrade R and RStudio: https://happygitwithr.com/install-r-rstudio.html#install-r-rstudio

2. Install the following packages: `install.packages(c("tidyverse", "rmarkdown", "usethis", "fs", "here", "renv", "devtools"))`

3. Install `rig`: https://github.com/r-lib/rig

4. Please make sure your system is ready to build packages. You can 
confirm this by checking if `devtools::has_devel()` returns `Your system is ready to build packages!`. 
If this returns `Could not find tools necessary to compile a package` this indicates
your system needs additional tools - please see https://rstats-wtf.github.io/wtf-personal-radmin-slides/#/how-to-get-the-tools
to identify what to install for your OS.

## Schedule

| Time          | Activity                                        | Instructor      |
|:--------------|:------------------------------------------------|:----------------|
| 09:00 - 10:30 | [Introduction](https://rstats-wtf.github.io/wtf-introduction), [Debugging](https://rstats-wtf.github.io/wtf-debugging-slides/#/title-slide) | Shannon Pileggi |
| 10:30 - 11:00 | *Coffee break*                                  |                 |
| 11:00 - 12:30 | [Debugging](https://rstats-wtf.github.io/wtf-debugging-slides/#/title-slide) | Shannon Pileggi |
| 12:30 - 13:30 | *Lunch break*                                   |                 |
| 13:30 - 15:00 | [Personal R Administration](https://rstats-wtf.github.io/wtf-personal-radmin-slides)                | E. David Aja  |
| 15:00 - 15:30 | *Coffee break*                                  |                 |
| 15:30 - 17:00 | [Personal R Administration](https://rstats-wtf.github.io/wtf-personal-radmin-slides)                | E. David Aja      |

## Instructor(s)

[Shannon Pileggi](https://www.pipinghotdata.com/) (she/her) is a Lead Data Scientist at The Prostate Cancer Clinical Trials Consortium, a frequent blogger, and a member of the R-Ladies Global leadership team. She enjoys automating data wrangling and data outputs, and making both data insights and learning new material digestible.

[E. David Aja](https://edavidaja.com/) is a Solutions Engineer at Posit. Before joining Posit, he worked as a data scientist in the public sector.


## Completion survey

At the conclusion of the workshop, please submit <https://pos.it/conf-workshop-survey>.

Your feedback is crucial! Data from the survey informs curriculum and format decisions for future conf workshops, and we really appreciate you taking the time to provide it.

-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).
