# k8s-mysql-backup-automation

Simply K8s cronjob to automate backups of the infamous solution in this case with mariadb in the aks cluster to the storage account.
Firstly we need to initiate a Storage Class, you can create a i.e. azure storage account or it will be created in along the aks cluster resources not where managed AKS cluster it is.

https://sharepointdevelopmentblog.wordpress.com/2022/08/22/k8s-cronjob-backup-of-mariadb-to-storage-account
