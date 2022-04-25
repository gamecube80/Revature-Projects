# Project 1

## Project Description
MovieLens data sets were collected by the GroupLens Research Project at the University of Minnesota. This data set consists of: * 100,000 ratings (1-5) from 943 users on 1682 movies. * Each user has rated at least 20 movies. * Simple demographic info for the users (age, gender, occupation, zip) Should Import csv data about movies and their ratings into HDFS, then create tables from the imported files in Hive. Once imported, should create queries to analyze and display data about the movies and their ratings.

Project 1 was a scala project to use the CLI to use different commands to get different queries from a hive database.
Each different querie has at least 1 user defined variable.

This allows the user to get many different search results depeinding on what they want to find.

## Technology Used
* Scala 2.13.8
* Sbt 1.6.2
* Ambari 2.7
* Hortonworks Sandbox 3.0.1
* HDFS
* YARN
* Hive

## Features

### Fatures and TODO for future development

* A useful help feature to show users what commands are available
* 4 different queries each with user input fields to allow the user to narrow down and chose their own parameters for a query

### To-do:

* Create a GUI for the program
* Create more queries

## Getting Started
git clone https://github.com/gamecube80/Revature-Projects/tree/main/Project1

## Usage
Clone and run the project
Type help for list of commands
Input user entered parameter and hit enter to receive query

> Needs sbt and scala installed on your system  
> Need to install and run ambari sandbox and import the dataset into your hive to run queries

## Contributors
* Daniel Hoelzel
* Alex Smith

## License
This project uses the following license: Creative Commons Attribution ShareAlike 4.0 License.
