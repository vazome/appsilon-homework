#Get base image which already has R and Shiny installed
FROM rocker/shiny
#Heading to the working directory
WORKDIR /usr/src/app
#Run Application with Rscript sourcing Github repo
RUN Rscript -e "shiny::runGitHub('appsilon-homework', 'vazome', subdir = 'shiny-app/hello')"
