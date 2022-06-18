# az204


resourceGroup=$(az group list --query "[].{id:name}" -o tsv)
appName=az204app$RANDOM


[
  {
    "id": "/subscriptions/45b351fe-c7e8-4cb4-82e4-ff3615698d8d/resourceGroups/learn-1a655a70-7aa3-4d63-90cf-123e9cf83174",
    "location": "westus",
    "managedBy": null,
    "name": "learn-1a655a70-7aa3-4d63-90cf-123e9cf83174",
    "properties": {
      "provisioningState": "Succeeded"
    },
    "tags": {
      "x-created-by": "freelearning",
      "x-created-for": "49a70c30-cdc0-4e53-86e5-1eb0d4b8c33d",
      "x-module-id": "learn.wwl.introduction-to-azure-app-service"
    },
    "type": "Microsoft.Resources/resourceGroups"
  }
]
