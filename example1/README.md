



# Task description

- [✔️] 🐧  1  => Create a Jenkins file 
- [✔️] 🐧  2  => Create a Jenkins  pipeline
- [✔️] 🐧  3  => build back-end 
- [✔️] 🐧  4  => Test for back-end 
- [✔️] 🐧  4  => build front end 
- [✔️] 🐧  5  => build front docker  image 
- [✔️] 🐧  6  => build backend docker image
- [✔️] 🐧  7  => run docker compose 
- [✔️] 🐧  8  => run smok test 

##########################################################
api command
image: maven:3-amazoncorretto-17  
build: mvn verify
build: mvn test
#########################################################
for the web 
image: golang:alpine

build : go build dispatcher.go 

##########################################################