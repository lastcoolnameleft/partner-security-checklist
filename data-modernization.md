# Data Moderization

* Are you implementing least privledged access?
* Are you using Azure Managed Identity?
* Are you storing your secrets in Key Vault?
* Is your storage encrypted using Azure key or custom managed key?
* Is "allow to Azure services" turned off?
* Are client machines using the lastest TLS version?
* Are Private Enpoints being used?
* Is Azure Defender for SQL being used?
* Do you have public access disabled?
* If supported, are you using Managed Identity to authenticate to your database from the application? 
* If not using Managed Identity, are you storing your credentials in Azure Key Vault? 
* [Is Transparent Data Encryption (TDE) turned on?](https://docs.microsoft.com/en-us/azure/postgresql/concepts-data-encryption-postgresql)
* Auditing/Logging/Monitoriong/Alerting?
* Advanced Threat Protection?
