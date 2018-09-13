# ARM template to deploy multiple Linux or Windows Virtual Machines, while the parameters.json file gets the username and password from an Azure Key Vault

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Frichardspitz%2FARM-Templates%2Fmaster%2Fmulti-vm-vnet.json" target="_blank">
<img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Frichardspitz%2FARM-Templates%2Fmaster%2Fmulti-vm-vnet.json" target="_blank">
<img src="http://armviz.io/visualizebutton.png"/>
</a>

This ARM template shows how to use resource manager template comparison functions for conditional deployment (Linux or Windows) as well as how to reference an Azure Key Vault secret in the parameters.json file for admin username and password.
