# TwitterData-Analysis-Uisng-Flume
This project Process Twitter Data using Flume and stores it in Hadoop. The data is processed with Apache Flume on Local Machine and then stored in HDFS as Logs.

## Key Features
* Data Engineering: Implement a data pipeline to process twitter data.
* Tech Stack: Twitter API, Apache Flume, Apache Hadoop.
* Error Handling: Handle common errors and provide troubleshooting tips for a smooth workflow.

## Architecture
![twitter_data](https://github.com/Ganesh-Bollapalli/TwitterData-Analysis-using-Flume/assets/131467608/02b77b28-324f-4e3d-9c63-10a8a79795e6)
## Environment SetUp
### Hardware Used
#### Local Machine:

  Windows 11
  4 vCore, 4 GiB Memory, 32 GiB Storage
  
### Prerequisites
* Twitter API
* Apache Flume
* Apache Hadoop

## Project Implementation
1. Download Apache Hadoop and configure on our local machine and check all the demons are running.
2. Download Apache Flume and configure on our Local Machine properly.
3. Get the required Twitter API keys for our twitter account.
4. Create a twitter configuration file and provide source, channel and sink details based on requirement.
## Execution
1. Run all the Hadoop demons on local machine using star-all command.
2. Run the twitter configuration file using flume-ng command.
3. Check for the logs files on hdfs using localhost://hostname and check the result.

## Error Handling and Troubleshooting
The following are common errors and troubleshooting tips for this project:

* Apache Flume Configuration Error : Configure twitter.conf file and check for the flume-ng file configuratio on local manchine accordingly.
* Apache Invalid credentials : Create Twitter API for your account and get all the required properly.
* Apache Hadoop Configuration Error : Configure Hadoop on local machine properly and check whether all Demons (DataNode, NameNode, NodeManager and Resource Manger) are running propelry.

## Conclusion
This project demonstrates the use of Twitter API, Apache Flume and Apache Hadoopto to retrieve and analyze twitter hastag as hdfs logs.
