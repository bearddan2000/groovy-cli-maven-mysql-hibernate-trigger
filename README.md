# groovy-cli-maven-mysql-hibernate-trigger

## Description
Creates a small database table
called `dog` and populates with hql.

Added an insert trigger to `dog`.

## Tech stack
- groovy
- maven
  - hibernate
  - hql
  - log4j
  - mysql driver

## Docker stack
- maven:3-openjdk-17
- mariadb

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
