idlj -fall ReverseModule.idl
javac *.java ReverseModule/*.java
orbd -ORBInitialPort 1050&
java ReverseServer -ORBInitialPort 1050& -ORBInitalHost localhost&
Open New Terminal:
java ReverseClient -ORBInitialPort 1050& -ORBInitalHost localhost
