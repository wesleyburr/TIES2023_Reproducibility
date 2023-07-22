## TIES 2023 Reproducibility Workshop

**Blurb**: This workshop will equip participants with tools (Git/GitHub, R/Rstudio and `renv`- an 
R dependency management tool) and best practices for implementing data analysis workflows that 
promote collaboration and reproducibility. These tools and workflows are integral to creating 
reproducible and transparent research - research where the same result can be reached given the 
same input, computational methods, and conditions, as well as one that has a history which records
how and why decisions were made that shaped the analysis. These tools and principles have also 
transformed the teaching of statistics, facilitating the development of active and experiential learning.

### Some definitions to help us scope the workshop:

**Data science:** process of extracting insight from data through reproducible and auditable methods.

**Reproducible analysis:** reaching the same result given the same input, computational methods, 
and conditions (from National Academy of Sciences, 2019).

**Auditable analysis:** an analysis with a readable record of the steps used to carryout
the analysis (*i.e.*, computer code) 
as well as a record of how the analysis methods evolved 
(*i.e.,* a version controlled project history) (from [Parker, 2017](https://onlinelibrary.wiley.com/doi/10.1111/brv.12013) and [Ram, 2013](https://scfbm.biomedcentral.com/articles/10.1186/1751-0473-8-7))
This history is important for recording how and why decisions to use one method 
or another were made, among other things.  

Thoughts: writing code is important for creating reproducible and auditable analyses, but it is not enough. 
More is needed, including a recorded and shareable compute environment, and a version controlled history of the project.

### Possible workshop topics:

We assume the audience is most likely familiar with the R programming language (as opposed to Python) 
and would prefer to stay in an R-only world as opposed to moving into more *devops* (software 
development + IT operations) like tools for  compute environment managment.

- what is reproducibility and why is it important (~ 15 min)
- the importance of reproducible coding habits (e.g., scripting, *usethis*, *here*) for portability and 're-run-ability' (~ 15 minutes)
- version control (Git, mostly - concepts, understanding the basics using local and remote version control) (~45 minutes)
- integrating version control into your workflow (Git & GitHub via RStudio/Happy Git with R) (~ 60 minutes)
- shareable compute environments (e.g., `renv`) (if time allows, ~ 45 minutes)

### Links

* The [Before Workshop](Before_Workshop.pdf) instructions
* The [slide deck](TIES2023_Reproducibility.html)
