# Appsilon Homework
Homework project for Appsilon

## Assignment 1: R Shiny App [![Build Shiny Docker Image](https://github.com/vazome/appsilon-homework/actions/workflows/build_shiny_docker.yml/badge.svg)](https://github.com/vazome/appsilon-homework/actions/workflows/build_shiny_docker.yml)

Per assignment, the environment has been created to build an R Shiny application with Docker and GitHub CI/CD. The image could have been sourced from either [r-base](https://hub.docker.com/_/r-base) or [rocker/shiny](https://hub.docker.com/r/rocker/shiny) up to one's compliance requirement in regards to official image usage. I sticked with latter due to no requirement while keeping default build platform linux/amd64.

Related configurations available at [shiny-app](./shiny-app) and [build_shiny_docker.yml](.github/workflows/build_shiny_docker.yml).


## Assignment 1: R Shiny App [![Build Shiny Docker Image]
``` yaml
ansible-playbook playbook.yml -i ansible_hosts 
```