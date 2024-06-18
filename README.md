# AzureFunction
This repo contains a sample python function in FunctionApp/ directory and ci/cd pipeline to deploy it to azure functions app.

# If you want to make the function to be accessed by autherization then change this line in function.json
"authLevel": "anonymous",  ------>>>  "authLevel": "Function",

# Once the function is deployed then test it using hitting function URL with parameter ( I would suggest from postman)
https://myfunction.azurewebsites.net/api/HttpTrigger1?name=saquib

