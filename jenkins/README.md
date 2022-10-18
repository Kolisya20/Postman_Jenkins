# Jenkins_Postman
## Create Jenkins local  server 
	1. [download jenkins.war file](https://get.jenkins.io/war-stable/2.361.2/jenkins.war)
	2. open terminal
	3. swith to the directory with downloaded file
	4. to start server run `java -Dfile.encoding=UTF8 -jar jenkins.war`
	5. [open http://localhost:8080/] (http://localhost:8080/)
	6. Clone this repository
	7. Copy config.xml from HT3\jenkins to the \.jenkins\jobs\jobs_name
		webroot: $user.home/.jenkins
	8. Install HTML_Publisher plugin in Jenkins (Dashboard/Manage Jenkins/Manage Pugins/Available/HTML Publisher)
	9. Restart Jenkins local server
	10. Open added Item
	11. Run build
