Requirement：
- JDK 1.8+
- Apache-tomcat-8.5.69+
- Apache Flink 1.13+
- MongoDB 5.0.0+

Deployment：
- Download all compressed files from '/resource' into the same folder, and extract them to obtain 'RECARS.war'.
- Put RECARS.war to the directory webapps of the Tomcat
- Set configuration: modify /conf/context.xml by setting <Resources cachingAllowed="true" cacheMaxSize="100000" />
- Start the server and run the demo

Presentation:
- We use a video to illustrate the core concepts and techniques of this work, its innovations, advantages over existing approaches, and the content of the demo presentation.
- Download all compressed files from '/RecordedVideo' into the same folder, and extract them to obtain 'DemoVideo.mp4'.
