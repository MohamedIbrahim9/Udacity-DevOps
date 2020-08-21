# Udacity DevOps Nanodegree Project2 - CloudFormation

## Overview
This project focuses on creating infrastructure for application like instagram called Udagram along with the necessary supporting software into its matching infrastructure

## Developoment Stratgey 
the developement was divdied into three steps, firstly, creating the application Architecture which located in Diagram folder. 
secondly, creating the network infra structure. thirdly, creating server layer and exporting the Load Balancer URL 

## Project Environment 
the Project is developed with scripts in YAML Format 

## Depenedices 
the main dependices are aws-cli and using any code editor like VSCode 

## Running the project

To get started with network Layer run: `./Helpers/create.sh networklayer network.yml networkparams.json`

start the server layer : `./Helpers/create.sh serverlayer server.yml serverparams.json`

to delete the stack run : 
`./Helpers/delete.sh networklayer`

`./Helpers/delete.sh serverlayer`

**You can test the application via this link** : [http://serve-WebAp-2414K7W11HTS-946754465.us-west-2.elb.amazonaws.com](http://serve-WebAp-2414K7W11HTS-946754465.us-west-2.elb.amazonaws.com)

