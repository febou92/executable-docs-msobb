---
title: 'msobb'
description: In this quickstart, you learn how to use the Azure CLI to create a Linux virtual machine
author: felix msobb
ms.service: azure-virtual-machines
ms.collection: linux
ms.topic: quickstart
ms.date: 03/11/2024
ms.author: felix msobb
ms.custom: mvc, devx-track-azurecli, mode-api, innovation-engine, linux-related-content
---

# Quickstart: Create a Linux virtual machine with the Azure CLI on Azure

```bash
export RANDOM_ID="$(openssl rand -hex 3)"
export MY_RESOURCE_GROUP_NAME="myVMResourceGroup$RANDOM_ID"
export REGION=EastUS
az group create --name $MY_RESOURCE_GROUP_NAME --location $REGION
```
