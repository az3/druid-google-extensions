# druid-google-extensions
Uber Jar for druid-google-extensions.

To deploy, create a directory and download artifact.

```
cd /opt/druid # or whatever your installation directory is
cd extensions
mkdir druid-google-extensions
cd druid-google-extensions
wget 0.10.1.jar
```

The folders should look like this;

```
/opt/druid/extensions $ ll
...
drwxr-xr-x. 2 druid druid     86 Aug 22 22:26 mysql-metadata-storage
-rw-rw-r--. 1 druid druid 942807 Aug 23 01:52 mysql-metadata-storage-0.10.1.tar.gz
drwxr-xr-x. 2 druid druid   4096 Sep 18 11:53 druid-avro-extensions
drwxr-xr-x. 2 druid druid     71 Sep 18 11:53 druid-caffeine-cache
drwxr-xr-x. 2 druid druid     98 Sep 18 11:53 druid-datasketches
drwxr-xr-x. 2 druid druid    273 Sep 18 11:53 druid-examples
drwxr-xr-x. 2 druid druid     40 Sep 18 11:53 druid-histogram
drwxr-xr-x. 2 druid druid   4096 Sep 18 11:53 druid-hdfs-storage
drwxr-xr-x. 2 druid druid    249 Sep 18 11:53 druid-kafka-eight
drwxr-xr-x. 2 druid druid   4096 Sep 18 11:53 druid-kafka-extraction-namespace
drwxr-xr-x. 2 druid druid    166 Sep 18 11:53 druid-kafka-indexing-service
drwxr-xr-x. 2 druid druid   4096 Sep 18 11:53 druid-kerberos
drwxr-xr-x. 2 druid druid     52 Sep 18 11:53 druid-lookups-cached-global
drwxr-xr-x. 2 druid druid    128 Sep 18 11:53 druid-lookups-cached-single
drwxr-xr-x. 2 druid druid     50 Sep 18 11:53 druid-protobuf-extensions
drwxr-xr-x. 2 druid druid     36 Sep 18 11:53 druid-stats
drwxr-xr-x. 2 druid druid     44 Sep 18 11:53 druid-s3-extensions
drwxr-xr-x. 2 druid druid     88 Sep 18 11:53 postgresql-metadata-storage
drwxrwxr-x. 2 druid druid     96 Sep 18 15:18 druid-google-extensions
/opt/druid/extensions $ ll druid-google-extensions/
...
-rw-r--r--. 1 druid druid 3625438 Sep 18 15:18 druid-google-extensions.jar
/opt/druid/extensions $ 
```