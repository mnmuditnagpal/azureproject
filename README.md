# azureproject

While running for each loop where we want to run the same pipeline for diff tables we can use an array of dict. like in loop for i in range(1,100): we make use of 'i' variable in ADF we have ref using item variable like item().

Logic Apps (Alerts & Monitoring in Azure Data Factory) : for automation of failed pipelines triggers.
We want to know which pipeline fail as we will be running various pipelines
In Logic Apps we create an API which will be triggered when we will have a failure. We will send a post request to this Api which will send the failure alert.

API : Post API we will attach the API to pipeline when a pipeline is failed only then we have to trigger. For API we will be using Web Activity.
