#Get base image from the official docker hub R repository 
FROM r-base:latest
#Heading to the working directory
WORKDIR /usr/src/app
#Install shiny package with Rscript
RUN Rscript -e "install.packages('shiny', repos='https://cloud.r-project.org')"
#Run Application with Rscript sourcing Github repo
RUN Rscript -e "shiny::runGitHub('shiny-examples', 'rstudio', subdir = '001-hello')
