# Mlops-project-6-Azure-Project

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/86e24ec1-f946-4707-b0ab-9bb091777a26)

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/1b05700d-043c-4a54-8918-5a7252d81d25)

## Step 1: Log on portal.azure.com

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/9aff1573-59ab-4cee-928e-8f999dbb5e4b)


# Three pipeline:

1.Pipeline for infrastructure
2.Building and Training the ML model
3.Deploying the ML model

## Step 2: Open dev.azure.com
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/1b27dd8c-9aab-4860-bd4a-890c97dc1142)

## Project name: mlops-jan24

fork the repository: https://github.com/03sarath/MLOpsPython

## Click Library under pipelines
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/95398bb4-f145-4e89-8422-9b373d8c74ab)

## Create a variable group
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/75fb89e2-9851-49a8-993a-f16fc6878f9e)

Variable group name: devopsforai-aml-vg
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/4f3f240f-4291-4b36-ac51-f31b45e1516c)

Pipeline Permission
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/360c84f2-5ee7-4209-bb61-490b89befc6a)

click Open access button

Go to project settings
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/78f244bf-1931-4716-acef-1d16e3753d05)

select service connections
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/f948d075-0e80-4f90-a572-9c6ba320cbc5)

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/48f07ee3-aae6-4c2c-9939-629081985fe4)

The service connection name is same as AZURE_RM_SVC_CONNECTION
which is azure-resource-connection

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/70237cab-f77c-4798-921b-ccdcf3791212)

Save it

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/d43eabad-9103-4123-8e84-ffdf221ffedb)


# Create pipleline 
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/7099367a-8efa-4f0a-8e4a-675a550362be)

Select GitHub

Select the GitHub repository, then select Existing Azure Piplelines YAML file
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/d0a5ac36-beca-41b2-866e-0b43089c4c79)


![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/ed16082e-3f3d-4853-855c-866819050a91)

# Run
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/273b563f-4745-414f-b4be-1185d120a34e)

# The pipleline wont run due to same name, so change the base name as mlopsnj
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/8cb482ba-29e8-453c-9f74-ca9331bdbcda)

Go to portal and delete the resource group

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/ec03cb70-c559-4ddf-9065-41cfef6bd500)

# Create new service connection
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/8a9c6057-b20f-4019-8e6f-bacecd3574e5)

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/6d044f9f-2f27-4a82-a680-57a7a60cc4f3)

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/85d702ba-75ba-4b67-9f4b-cedfa10c3234)

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/536a32e0-d06e-4be2-bcbb-7e69554a6096)

# Lets rename the pipeline
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/2b0d8ff8-d5ae-4bbe-b5dc-7bd2895bf1a2)

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/a183d426-fad8-4f53-9997-01fb8205aec0)

![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/8b7c576a-6ae2-4a13-b6c1-4f0525684c67)
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/1dd1614c-760c-4fff-9582-f06648c125e6)

# Rename
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/ef1e40fa-1b68-444d-82b7-6b69c1460bc3)

# Run
![image](https://github.com/nibinkjoseph/Mlops-project-6--Azure-Project/assets/63180074/1fd63962-aac8-4ad0-b8dd-2a55c883b855)



