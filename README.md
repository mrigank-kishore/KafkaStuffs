Step 1: Download kafka - https://www.apache.org/dyn/closer.cgi?path=/kafka/2.3.1/kafka_2.12-2.3.1.tgz
Step 2: Unzip kafka in a directory
Step 3: go to extracted kafka folder in powershell or command prompt
Step 4: Start Zookeeper using command "bin\windows\zookeeper-server-start.bat config\zookeeper.properties"
Step 5: Once zookeeper running, start kafka broker using command "bin\windows\kafka-server-start.bat config\server.properties"
Step 6: for running kafka connect code, checkout the connect folder from git and go to that folder and the run following command "C:\Softwares\kafka\bin\windows\connect-standalone.bat .\worker.properties .\file-stream-demo-standalone.propertie". Make sure to change kafka directory in tha command.
