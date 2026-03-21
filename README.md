# azureproject


Logic Apps (Alerts & Monitoring in Azure Data Factory) : for automation of failed pipelines triggers.
We want to know which pipeline fail as we will be running various pipelines
In Logic Apps we create an API which will be triggered when we will have a failure. We will send a post request to this Api which will send the failure alert.

API : Post API we will attach the API to pipeline when a pipeline is failed only then we have to trigger. For API we will be using Web Activity.
