## XMD

XMD stands for e<b>X</b>tended R <b>M</b>ark<b>D</b>own.  XMD extends the reach of R and RMarkdown scripts beyond the domain of R experts and closer to business users.  It also provides a convenient infrastructure to deploy RMarkdown scripts for repeated execution and scheduling.

[RMarkdown](http://rmarkdown.rstudio.com/) powered by [knitr](http://yihui.name/knitr/) are very cool tools for data scientists working in [R](http://www.r-project.org/) - and in particular [R Studio](http://www.rstudio.com/).

In the words of it's creators:

_"R Markdown is an authoring format that enables easy creation of dynamic documents, presentations, and reports from R. It combines the core syntax of markdown (an easy-to-write plain text format) with embedded R code chunks that are run so their output can be included in the final document. R Markdown documents are fully reproducible (they can be automatically regenerated whenever underlying R code or data changes)."_

XMD is the server infrastructure that supports the following User Stories:

* As a data scientist I would like to enable colleagues and collaborators with limited or no experience of R to be able to rerun my RMarkdown scripts (which generate HTML output) so that they can self serve and run parameterised analytic processes without my help 
* As a data scientist I would like to be able to schedule any data munging, statistical modelling or visualisation process in the language in which I created it (R obviously!) so that I can be more productive and not have to rework and revalidate code in the languages of production
* As a data scientist I produce lots of RMarkdown scripts and I want to publish them to XMD as quickly as seamlessly as possible without having to log in to the server or execute any manual process - one command to deploy!I might be a good data scientist but my Unix / Ubuntu admin skills and web development skills are limited and whilst I can do it these tasks waste a lot of my time
* As a data scientist who works with big data my analysis processes often take a long time to run - when a user runs an XMD process I want to provide users with email updates as the job executes so they can start the job and forget about it confident in the knowledge that it is running
* Since users do not always want to log into the XMD web site to start an XMD job they should be able to start a job by calling a RESTful API so they can control the execution of XMD jobs from their own tools or processes

XMD is not:

* An interactive reporting tool like RShiny or Tableau
* A tool for writing RMarkdown code
* A business intelligence tool 
* A replacement for R, RMarkdown or knitr
* Anything to do with XML

Hope that explains what XMD is - I have a working prototype running - this project is about rewriting it and sharing it with the wider community.  There were too many hacks in XMD1.0 ;-)

I also want to rewrite the entire server using Python - I chose Perl first time round but my trendy colleagues don't have experience in that - Python is more  cool from a data science point of view than Perl!  

Cheers,
Matt


