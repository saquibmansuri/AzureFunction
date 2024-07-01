# AzureFunction
This repo contains two sample python functions in FunctionApp/DemoSample directory and ci/cd pipeline to deploy both functions into 1 single azure function app.

# If you want to make the function to be accessed by autherization then change this line in function.json
"authLevel": "anonymous",  ------>>>  "authLevel": "Function",

# Once the function is deployed then test it using hitting function URL with parameter ( I would suggest from postman)
For Function1 -- https://myfunction.azurewebsites.net/api/Function1?name=saquib
For Function2 -- https://myfunction.azurewebsites.net/api/Function2?name=saquib
