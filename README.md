# This repository
- list of bicep files to test various network architecture on Azure

# How to deploy resources
1. login azure with `az login`
2. create resourece group with bellow command

```
$ az group create --name "test-rg" --location "Central US"
```
3. deploy resource with bellow command

```
$ az deployment group create --resource-group "test-rg" --template-file main.bicep
```

# Sample reference
https://zenn.dev/zukako/articles/85d7d2c044c4a8