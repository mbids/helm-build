#Composite action that can build and push your helmchart to ACR
Inputs are as follows:
	- acr_instance | The URL to your container registry, example: <mbids>.azurecr.io
	- acr_user | The username for your serviceaccount
	- acr_password | The password for your serviceaccount
	- chart_name | The name of your chart, this is also used for foldername
