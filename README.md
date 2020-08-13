# ACR to ACI with Azure Devops

* This Azure Pipelines example will build a Container
* push it into the Azure Container Registry  
* Automatically restart Azure Container Instances and consume the latest container image available under tag latest.

You will need to put your Azure Service Connection name into the pipeline variable azsubscription.
