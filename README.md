# Publishing URL Contents to Kafka
## Step-by-step guide to ingest contents from a HTTP request or REST API response into Kafka

This notebook will walk you through publishing contents of a URL into Kafka. 

[Apache Kafka](https://kafka.apache.org/) is an open-source distributed event streaming platform used for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications.

One often needs to read data from the internet and get it to a platform where they can perform Data Analysis on it. Using Kafka is often a choice for routing data from it's source to platform where you can transform or analyse it. 

This notebook is a walkthrough in publishing contents of a URL to Kafka. Here we will assume the Kafka service was spun up in a docker container. Docker is a platform for developing, shipping, and running applications. You can read more about docker [here](https://docs.docker.com/get-started/overview/). 
