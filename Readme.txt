该工程为H3C DataEngine产品中Spark组件提供样例代码，而且区分kerberos环境和非kerberos环境。该工程的目录结构介绍：


SparkExampleCode/
  |Readme.txt                       --介绍文档
  |scala-example-normal/            --非Kerberos环境下样例代码
     |pom.xml                       --pom文件
     |HiveTOHBase/                  --将hive表内容写入HBase中
     |SimpleExample/                --简单的样例代码
     |SQLScalaExample/              --SQL相关样例代码
     |StreamingToHBase/             --读取流数据，写入HBase中样例代码
     |ThriftServer/                 --JDBC方式操作ThriftServer
  |scala-example-security/          --Kerberos环境下样例代码
     |pom.xml
     |HiveTOHBase/
     |SimpleExample/
     |SQLScalaExample/
     |StreamingToHBase/
     |ThriftServer/


下面介绍下各个场景下的样例工程。
1. HiveTOHBase：。。。。。。


2. SimpleExample
