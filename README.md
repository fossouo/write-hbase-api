JDK 1.8 

Scala 2.11 for Intellij 

Maven plugin in Intellij 

Run from project directory in Shell :

1. HBASE 1 -> 2 : 

java -jar write-to-hbase-1.0-jar-with-dependencies.jar com.dfossouo.scala.hbase.Main -cs ./core-site.xml -hs ./hbase-site.xml -t donald12 -zq c325-node2.squadron-labs.com


2. HBASE 2 -> 1 : 

java -jar write-to-hbase-1.0-jar-with-dependencies.jar com.dfossouo.scala.hbase.Main -cs ./core-site2.xml -hs ./hbase-site2.xml -t donald123300000 -zq c125-node4.squadron-labs.com