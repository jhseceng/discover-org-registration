# Discover Org Registration Templates

## Overview

Creates resources that help with Discover account registration in an AWS Organization. 

Creates a Service Managed Stackset in an account 
Autodeployment is currently set to false but may be enabled

AutoDeployment =

{'Enabled': False,
'RetainStacksOnAccountRemoval': False}

## Instructions

1) Upload the files from the s3 bucket folder to an S3 bucket and make the files **PUBLIC READ ONLY** in the region where you perform stackset operations.  You can achieve this using bucket ACLs or a bucket policy.
https://aws.amazon.com/premiumsupport/knowledge-center/read-access-objects-s3-bucket/


2) Load the CFT from the "cft" folder and apply the settings. 

