# maads-viper

VIPER is an Apache Kafka source and sink connector for TML solutions. 

VIPER is currently the only Kafka connector (https://www.confluent.io/hub/oticsinc/maads-viper), integrated with AutoML (HPDE) and [MAADSTML python library](https://pypi.org/project/maadstml/) to create powerful TML solutions, fast!  

To start VIPER run the command: [VIPER executable] [host] [port]
1) Run in Windows/Linux/MacOS environments
2) Create unlimited number of VIPER instances for massive scale - fully compatible with microservices architecture for load shedding
3) VIPER can be accessed via MAADSTML python library or REST API using HTTP or HTTPS connections
4) If using VIPER with ON-PREM version of Kafka then set ONPREM=1 in Viper.env 

NOTE: You can also force the producer to compress data by setting the COMPRESSIONTYPE option in VIPER.ENV to SNAPPY, LZ4, GZIP or NONE.
