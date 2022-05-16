# Discover Org Registration Templates

The template is supported in the following regions

eu-west-1

us-east-1

us-east-2

us-west-2

ap-southeast-2


## Overview

Creates resources that help with Discover account registration in an AWS Organization. 

Creates a Service Managed Stackset in an account 
Autodeployment is currently set to false but may be enabled

AutoDeployment =

{'Enabled': False,
'RetainStacksOnAccountRemoval': False}

## Instructions

1) Load the CFT from the "cft" folder and apply the settings. 


The cloudformation template is titled 'Discover_setup_delegated_account.yaml'

The cloudformation template will create a stackset that can be applied to all accounts. 


## StackSet Details

The above cft creates the Stackset using values from a mapping file.  The following mappings apply 

|  CSCloud 	|  us1 	|   us2	|   eu	|   	
|---	|---	|---	|---	|
|  CSAssumingRoleName 	| CS-Prod-HG-CsCloudconnectaws  	|   mav-gyr-main-s001-cs-cloudconnectaws	| lion-lanner-main-s001-cs-cloudconnectaws  	|   	
|  CSAccountNumber 	| 292230061137   	|  292230061137 	|  292230061137  	|   






