# Overview of Azure Services
This file contains text you can copy and paste for the examples in Cloud Academy's _Overview of Azure Services_ course.  

### Introduction
[Azure Free Trial](https://azure.microsoft.com/free) 

### Using the Azure Portal
[Azure Portal](https://portal.azure.com)

### Using the Azure CLI
```
git clone https://github.com/Azure-Samples/html-docs-hello-world.git
cd html-docs-hello-world
az webapp up --location westus --name [your_name] --html
http://[your_name].azurewebsites.net
az group delete --name [resource_group_name]
```
**Note:** If you're using Cloud Academy's Azure CLI Playground lab, then you'll need to use the following two commands instead of the "az webapp up..." command above. The first command tells you what values to use for [resource_group] and [location] in the second command.
```
az group list --query "[].{resource_group:name, location:location}"
az webapp up -g [resource_group] --location [location] -n [app_name] --sku S1 --html
```

### Service Categories
[Azure Products](https://azure.microsoft.com/services/)

### Designing a Solution
[Azure Architecture Center](https://docs.microsoft.com/azure/architecture/)

### Summary
[Azure documentation](https://docs.microsoft.com/azure/)  
support@cloudacademy.com
