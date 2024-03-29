#Get base image which already has R and Shiny installed
FROM rocker/shiny
#Heading to the working directory
WORKDIR /usr/src/app
#Run Application with Rscript sourcing Github repo
RUN Rscript -e "shiny::runGitHub('vazome', 'appsilon-homework', subdir = 'shiny-app/hello')"
