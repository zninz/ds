javac *.java
rmic AddServerImpl
Server Folder: AddServerIntf.class,AddServerImpl_Stub.class,AddServerImpl.class,AddServer.class
Client Folder: AddServerIntf.class,AddServerImpl_Stub.class,AddClient.class
Create 3 Terminals:
Main: rmiregistry
Server: java AddServer
Client: java AddClient 127.0.0.3 8 9