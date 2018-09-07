notes :

I modified camel examples from github, camel-example-servlet-tomcat to create this project
This version does nothing more than send back a greeting when hit from a web browser.

build :

mvn clean
mvn package
cp target/ecg-rest1.war <tomcat's webapps directory>

browse to :

http://localhost:8080/ecg-rest1/camel/hello?name=john
