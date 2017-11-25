# HDFS command line interface

There are some main command for using HDFS


1. Transfers file from local file system into HDFS
```
hdfs dfs -put <source location> <HDFS destination> 
```
2. To see the content of a remote file:
```
hdfs dfs -cat <location> 
```
- In HDFS tail utility out the last one kilobyte of a file

3. Transfers file from HDFS into local file system
```
hdfs dfs -get <source location> 
```
- You can start with prefix hdfs_, then all this files with this prefix will be download locally
- If you use -getmerge, then all data will merge in one local file 

### P. S.
You can use usual UNIX commands with little difference
