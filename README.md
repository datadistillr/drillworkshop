# Apache Drill Workshop
Welcome to the Apache Drill workshop by Charles Givre!  This 180 minute workshop will cover:
* Overview of Apache Drill
* Querying simple data
* Querying nested data
* Connecting external data sources
* Using Python to interact with Drill

If you have any questions, please contact me at: charles@datadistillr.com.  
Don't forget to check out my blog at http://thedataist.com

## Setting up Drill
For this class we will be using Drill 1.18. You can either download and install Drill locally on your machine or use docker.  If you are setting this up on your local machine, go to https://drill.apache.org and follow the instructions here for installating in embedded mode: https://drill.apache.org/docs/installing-drill-in-embedded-mode/

If you would like to use Docker, simply start Docker and run the following command:
```
docker run -i --name drill-latest  -p 8047:8047  -t apache/drill /bin/bash
```
