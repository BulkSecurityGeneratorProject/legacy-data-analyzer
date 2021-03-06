# Legacy data analyzer [![Build Status](https://travis-ci.org/aaradhanas/legacy-data-analyzer.svg?branch=master)](https://travis-ci.org/aaradhanas/legacy-data-analyzer) [![Waffle.io - Columns and their card count](https://badge.waffle.io/aaradhanas/legacy-data-analyzer.svg?columns=all)](https://waffle.io/aaradhanas/legacy-data-analyzer)

If you have built an application in the era of relational databases, you would have stored data in a relational form. As NOSQL databases started taking speed, it would have been difficult to migrate since the data volume would have been huge.

If we do not keep track of our customers trends and reactions to our product, it is very likely that we will lose our customers. To analyze such trends when the data is relational and huge, the legacy data analysis tool comes to your rescue. Give us your relational database and the kind of analysis you want make, we will do the job for you.

## Features

- Login as an admin and view admin specific dashboards
- Admin should be able to sync data and view updated dashboard
- Login as a user and view user specific dashboards
- User should be able to customize the dashboards

## Technologies/Tools

- [Elasticsearch][]
- [Kibana][]
- [Angular][]
- [Logstash][]
- [JHipster][]
- [MySQL Workbench][]
- [Docker][]

## Project tracking tools

- [waffle.io](https://waffle.io/)

## The Team

- [@vidhya03](https://github.com/vidhya03) : The Tech Enthusiast
- [@aaradhanas](https://github.com/aaradhanas): The Zealous Explorer
- [@rgopi2win](https://github.com/rgopi2win): The Biz Expert

## Prerequisites to project setup

Before you can build this project, you must install and configure the following dependencies on your machine:

1. [Node.js](https://nodejs.org/en/): We use Node to run a development web server and build the project.
   Depending on your system, you can install Node either from source or as a pre-packaged bundle.
2. [Yarn](https://yarnpkg.com/en/): We use Yarn to manage Node dependencies.
   Depending on your system, you can install Yarn either from source or as a pre-packaged bundle.
   

After installing Node, you should be able to run the following command to install development tools.
You will only need to run this command when dependencies change in [package.json](package.json).   

    yarn install

We use yarn scripts and [Webpack][] as our build system.


## How to setup the project

- git clone https://github.com/aaradhanas/legacy-data-analyzer into a directory.
- Import as a Maven project in IntelliJ.
- Once all the dependencies have been resolved, you can run the app.
- If you are not using any IDE and would like to run using Command prompt, run the following commands in two separate   terminals:

    `./mvnw`
	
    `yarn start`

## Minutes
  [Minutes](https://github.com/aaradhanas/legacy-data-analyzer/blob/master/MINUTES.md)
  
## Nice to have
 - Add angular material support - [Documentation](https://material.angular.io/)
 
## Spotbugs 
 [SpotBugs](https://spotbugs.github.io/) is a program which uses static analysis to look for bugs in Java code.

  Spotbugs can be triggred via compile time.
```
  mvn -Pspotbugs compile
``` 

  Spotbugs can also be check by using the below command.
```
  mvn -Pspotbugs spotbugs:check
```

  `Debug` the spotbugs error via the following command.
```
  mvn -Pspotbugs spotbugs:gui
```  
  The above command will popup spotbugs errors in GUI like this
  ![spotbugs error view in GUI](src/test/resources/spotbugs-viewer-gui.png)  


[Node.js]: https://nodejs.org/
[Yarn]: https://yarnpkg.org/
[Webpack]: https://webpack.github.io/
[Angular CLI]: https://cli.angular.io/
[BrowserSync]: http://www.browsersync.io/
[Karma]: http://karma-runner.github.io/
[Jasmine]: http://jasmine.github.io/2.0/introduction.html
[Protractor]: https://angular.github.io/protractor/
[Leaflet]: http://leafletjs.com/
[DefinitelyTyped]: http://definitelytyped.org/

[Elasticsearch]: https://www.elastic.co/
[Kibana]: https://www.elastic.co/products/kibana
[Angular]: https://angular.io/
[Logstash]: https://www.elastic.co/products/logstash
[JHipster]: http://www.jhipster.tech/
[MySQL Workbench]: https://www.mysql.com/products/workbench/
[Docker]: https://www.docker.com/
