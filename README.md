# java-web-maven-quarkus-api-postgres-simple

## Description
A POC for quarkus web api
connecting to a postgresql database.

## Tech stack
- java
- maven
  - quarkus
  - hibernate
  - postgres connector
  - lombok

## Docker stack
- postgres:alpine
- maven:3-openjdk-17
- registry.access.redhat.com/ubi8/openjdk-11:1.11

## To run
`sudo ./install.sh -u`
curl -i localhost/dogs

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
