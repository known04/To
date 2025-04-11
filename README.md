CASSANDRA INSTALLATION
java version higher than jdk-11 1.8.0
python27/latest C:
3.11.17/4.0.15 in C:
CASSANDRA_HOME in system var
go to bin folder run cassandra>cqlsh

Install Hadoop 3.3.1
HADOOP_HOME in user var
javahome in user and till bin
hadoop bin,sbin both var

<property>
    <name>fs.defaultFS</name>
    <value>hdfs://localhost:9000</value>
</property>

<property>
    <name>dfs.replication</name>
    <value>1</value>
</property>
<property>
    <name>dfs.namenode.name.dir</name>
    <value>file:///C:/hadoop/tmp/dfs/name</value>
</property>
<property>
    <name>dfs.datanode.data.dir</name>
    <value>file:///C:/hadoop/tmp/dfs/data</value>
</property>



<property>
    <name>mapreduce.framework.name</name>
    <value>yarn</value>
</property>

<property>
    <name>yarn.resourcemanager.address</name>
    <value>localhost:8032</value>
</property>
<property>
    <name>yarn.nodemanager.aux-services</name>
    <value>mapreduce_shuffle</value>
</property>










