# JMS-messaging-service
http://www.coderpanda.com/jms-tutorial/
eg: http://www.coderpanda.com/jms-tutorial-jms-example/

https://www.youtube.com/watch?v=2_FTyb0MBc4&list=PL4266926E3CA39410&index=2

https://www.youtube.com/watch?v=9WGSVnhlOHE (full example, request (queue) and response() by listener)


JMS is the technique used in J2EE technology  for an application to communicate with other applications.
An application can communicate with any number of applications using JMS.This communication is loosely coupled.
Because the applications needed to communicate are not connecting each other directly . Instead , those applications 
are connecting to a common destination. 

Java Message Service(JMS) API is an important API in J2EE . This API plays an important role in supporting 
other APIs in J2EE.

An application can send messages to the destination and can take messages from the same destination

JMS API supports Point-to-Point and Publish-Subscribe approaches.

JMS API Architecture

The important components are listed here.

JMS Client :- The Java application which produces/consumes message is known as JMS Client.

Service Provider :- A  messaging  system which implements the JMS interfaces.There are numerous service providers are available today.Examples are open JMS , JBoss Messaging . In the coming sections we will be looking into JMS  examples . There ,we will be using OpenJMS as the service provider.

Messages :– Messages are objects using to communicate between clients.

