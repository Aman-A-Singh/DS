idlj -fall HelloModule.idl

javac *.java HelloModule/*.java

orbd -ORBInitialPort 1050&

java Server -ORBInitialPort 1050& -ORBInitialHost localhost&

java Client -ORBInitialPort 1050 -ORBInitialHost localhost