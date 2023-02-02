# Scalable-Event-Based-GCP-Data-Pipeline-using-DataFlow


## Business Overview
There is a continual need to give huge volumes of data to teams in a data-driven
company. Many tools are available to assist you with your requirements and wants.
Choosing the appropriate mechanism may be complicated and overwhelming at
times. The key idea to remember is that there is no one-size-fits-all tool or
architecture, and it all depends on your needs.

For data ingestion, many businesses are opting for Event-Driven Architecture (EDA).
EDA is a software design paradigm used in application development. It enables
enterprises to track and recognize significant business moments and then act on
them immediately. EDA differs from a conventional request-driven system in that
services must wait for a response before moving on to the next job.

Many application architectures are increasingly event-driven in a modern economy
fuelled by high digital transaction volume.

These pipelines can provide the agility, scalability, context, and responsiveness
required for performant digital business applications. The event-driven design also
needs low coupling, making it a suitable match for distributed application
architectures.

There are producers and consumers in event-driven architecture. Producers unearth
events and craft a message. The event is subsequently transmitted to event
consumers through an event channel, where it is processed. An event processing
system then performs a response to the event message, which results in creating an
activity downstream.

This project will create an event-driven data pipeline using the Google Cloud
Platform's serverless features. It will be based on some of the development methods
that are frequently used in businesses.



## Tech Stack:
Tech Stack
- Language: Python3.7
-  Services: Cloud Composer, Google Cloud Storage (GCS), Pub-Sub, Cloud Functions, BigQuery, BigTable

## Architecture
<img width="699" alt="Screen Shot 2023-02-02 at 11 49 59 AM" src="https://user-images.githubusercontent.com/68578215/216435061-a7b6f29f-8bf7-4a99-be60-29bf04c0fb28.png">
