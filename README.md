# Dropbox project

## Automation tests using Postman

This repository was created for functional test automation of Dropbox project.

Technologies used:
- [Postman](https://www.postman.com/)
- [Newnam](https://www.npmjs.com/package/newman)
- [Newman reporter htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)

## Setup
1. Clone this repository
2. Install the dependencies of this project with `npm install`.

## Running test suite
1. Open terminal
2. Navigate to the path of the project that was cloned in
3. Run `npm run tests`

## Open report
After test completed check creared report in /newman



# Jenkins_Postman
## JS test automatiom using JENKINS

Technologies used:
- [Jenkins](https://get.jenkins.io/war-stable/2.361.2/jenkins.war).

## Setup
1. [Download jenkins.war file](https://get.jenkins.io/war-stable/2.361.2/jenkins.war)
2. Open terminal
3. Switch to the directory with downloaded file
4. To start server run `java -Dfile.encoding=UTF8 -jar jenkins.war`
5. [open localhost](http://localhost:8080/)
6. Clone this repository
7. Copy config.xml from HT3\jenkins to the \.jenkins\jobs\jobs_name
	webroot: $user.home/.jenkins
8. Install HTML_Publisher plugin in Jenkins (Dashboard/Manage Jenkins/Manage Pugins/Available/HTML Publisher)
9. Restart Jenkins local server

## Running test suite
1. Open terminal
2. To start server run `java -Dfile.encoding=UTF8 -jar jenkins.war`
3. Open added Item.
4. Run build.
