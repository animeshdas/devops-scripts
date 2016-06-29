# Animesh's DevOps Script Collection

#### This repo is the home of my devops script collection. 

All the script here are developed during different projects requirements. 
If you need help, drop me an email at _**jobs4ani ~~[at]~~ gmail ~~[dot]~~ com**_ Or visit my website **<http://animesh.das.net.in>**

##### DevOps Script
- **ttrestart** - In some old version of hadoop, tasktracker suddenly stops working due to JVM killing them due to memory leak. This bash script when used as cron jobs will restart the Hadoop tasktracker service when the tasktracker process reaches certain threshold, i.e check based on percentage of memory consumption OC against allocated memory.  But, this script doesn't restart hadoop tastracker or do anything if the tasktracker is not running at all or the jstat returns unexpected result. This script has not been tested under those exceptions or scenarios. Configuration details are documented inside the script.

- **kafka_mon** - Apache Kafka monitoring script.


### License
GPL3 Licenced. Click [here](blob/master/LICENSE) for licencing details.
