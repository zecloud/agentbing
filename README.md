# Minimal Streamlit application with a Langchain Agent using Bing Search to host on Azure Container Apps

My minimalist Template to experiment with Langchain with Azure Open Ai Service and bing. 

Bing tool with langchain and you reproduce somethin similar to the new Bing ChatGpt with less than 40 lines of python 

There is a devcontainer to use locally or with github codespace

You just need to provide an Azure Open Ai Key as named environment variable OPENAIAPIKEY
you also need to provide the url suffix or your azure Open Ai service as named environment variable RESOURCE_NAME 
and the deployment name as named environment variable DEPLOYMENT_NAME.

A dockerfile and a script to deploy it on Azure Container app is provided too. 
To deploy it you need to have the classical azure cli just change the following variables :

Azure resource group  : RESOURCE_GROUP  
desired deployment location : LOCATION
Desired Name of your container apps environment : CONTAINERAPPS_ENVIRONMENT
Desired container app name : APP_NAME
Name of the registry server to push the docker image : REGISTRY_SERVER 
Bing api key : BING_SUBSCRIPTION_KEY
Bing endpoint : BING_ENDPOINT
Azure OpenAI resource name : RESOURCE_NAME
azure openAI deployment name : DEPLOYMENT_NAME
an environment variable OPENAIAPIKEY should exist or put it in the deploy.sh too.

Have fun !


