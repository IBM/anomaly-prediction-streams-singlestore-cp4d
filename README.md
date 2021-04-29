# Detect anamolies in streaming IoT data using EventStreams and Singlestore database on Cloud Pak for Data

## Prerequisites
1. [IBM Cloud Account](https://cloud.ibm.com)
1. [IBM Cloud Pak for Data](https://cloud.ibm.com/catalog/content/ibm-cp-datacore-6825cc5d-dbf8-4ba2-ad98-690e6f221701-global)
1. [Install Singlestore database on Cloud Pak for Data](https://docs.singlestore.com/v7.3/reference/memsql-operator-reference/additional-deployment-methods/helm-chart-for-ibm-cloud-pak-for-data/)

## Steps

1. [Create an instance of IBM Event Streams](#1-create-an-instance-of-ibm-event-streams)
1. [Download the SSL certificate from Event Streams](#1-download-the-ssl-certificate-from-event-streams)
1. [Upload the certificate to the Singlestore cluster](#1-upload-the-certificate-to-the-singlestore)
1. [Clone the repo](#1-clone-the-repo)
1. [Build and run the application](#1-build-and-run-the-application)

## 1. Create an instance of IBM Event Streams

Click [here](https://cloud.ibm.com/catalog/services/event-streams) to create an instance of Event Streams.



## 5. Clone the repo

Run the below command to clone the repo:
```
git clone https://github.com/IBM/anamoly-prediction-streams-singlestore-cp4d
```
