# Cleaning Up

In this lab you will delete the compute resources created during this tutorial.

you just need to delete the resource group where all the resource where deployed.

```
az group delete -l westeurope -n k8s-hardway-rg
```

__This will destroy everything__