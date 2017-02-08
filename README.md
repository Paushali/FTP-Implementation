# FTP-Implementation
This project demonstrates FTP without using any Java FTP Library. It has all the basic commands of FTP including File Upload and Download.  This application supports multiple concurrent users and was implemented using multiple thread creation and locks.
## Important points to be noted for running the application:
* Create an EC2 instance and edit the EC2 url in OFTPClient.java.
* Create a local directory on the local machine and change the path at appropriate places in OFTPClient.java and OFTPServer.java
* First run OFTPServer.java and then run OFTPClient.java. You can run multiple OFTPClient.java apps simultaneously from different machines which can interact with OFTPServer.java
