Requirement：
-JDK 1.8+
-Apache-tomcat-8.5.69+
-Apache Flink 1.13+
-MongoDB 5.0.0+

Deployment：
-Download RECARS.war
-Put it to the directory webapps of the Tomcat
-Set configuration: modify /conf/context.xml by setting <Resources cachingAllowed="true" cacheMaxSize="100000" />
-Start the server and run the demo
