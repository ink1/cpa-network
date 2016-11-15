#TSI Cloud Portal - network deployment
Deploy a private network in the Cloud


## Required variables for Google Cloud Platform

`project` The ID of the Google Cloud project  
`network_name` An arbitrary name that will be assigned to your network, it has to be unique in your Google Cloud project  
`region` The Google region where the network should be created  

You can obtain a list of all the available region using the `gcloud` CLI with:

```
gcloud compute regions list
```
At the moment of writing this are the available regions:  
`asia-east`, `asia-northeast`, `europe-west1`, `us-central1`, `us-east1`, `us-west1`

