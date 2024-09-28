```
az ad sp create-for-rbac --name "<your-service-principal-name>" --sdk-auth --role contributor --scopes /subscriptions/<your-subscription-id>/resourceGroups/<resource-group-name>
```

```
az ad sp create-for-rbac --name "azure-demo00-service" --sdk-auth --role contributor --scopes /subscriptions/c38306d0-f731-429f-8069-7a696317f0d7/resourceGroups/azure-demo-00

```