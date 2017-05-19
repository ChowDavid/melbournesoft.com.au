# melbournesoft.com.au

## build on LOCAl
- mvn clean install -P LOCAL
- deploy to tomcat local and restart

## build on Production
- mvn clean install -P PROD
- deploy to cpanel /home/christar/tomcat/webpps/melbourne.com.au/ROOT
- restart the tomcat
