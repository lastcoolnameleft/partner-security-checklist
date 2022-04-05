# Cloud Native

## Questions

* [Do you externalize and encrypted all of your secrets?](https://docs.microsoft.com/en-us/azure/aks/csi-secrets-store-driver)
* [Do you keep your Kubernetes version up-to-date?](https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-cluster-security#regularly-update-to-the-latest-version-of-kubernetes)
* [Do you keep your Node Images up-to-date?](https://docs.microsoft.com/en-us/azure/aks/node-image-upgrade)
* [Is your Container Registry authenticated with AKS?](https://docs.microsoft.com/en-us/azure/aks/cluster-container-registry-integration)
* [Do you use Ingress for HTTP/HTTPS Traffic?](https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-network#distribute-ingress-traffic)
* [Do you secure pod traffic with network policy?](https://docs.microsoft.com/en-us/azure/aks/use-network-policies)
* [Is your cluster private?](https://docs.microsoft.com/en-us/azure/aks/private-clusters)
* [Do you use policy enforcement? (e.g. Azure Policy)](https://docs.microsoft.com/en-us/azure/aks/use-azure-policy)
* [Do you use separate Kubernetes namespaces to isolate your resources?](https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-cluster-isolation#logically-isolate-clusters)
* [Do you use WAF for protecting workloads from XSS](https://docs.microsoft.com/en-us/azure/developer/terraform/create-k8s-cluster-with-aks-applicationgateway-ingress)
* [Do you lock down AuthZ + AuthN to the Cluster API? ](https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-identity#use-azure-active-directory-azure-ad)
* [Do you use Pod Identity to connect to external resources?](https://docs.microsoft.com/en-us/azure/aks/operator-best-practices-identity#use-pod-managed-identities)
* [Do you use AAD or AAD B2C for user AuthN + AuthZ?](https://docs.microsoft.com/en-us/azure/active-directory-b2c/overview)
* [Do you quarantine vulnerable images?](https://github.com/Azure/acr/tree/main/docs/preview/quarantine)
* [Do you prevent data-leaking with egress lockdown?](https://docs.microsoft.com/en-us/azure/aks/limit-egress-traffic)
* [Do you scan your container images?](https://docs.microsoft.com/en-us/azure/defender-for-cloud/defender-for-container-registries-cicd)
* [Is your ACR inaccessible to the public internet?](https://docs.microsoft.com/en-us/azure/container-registry/container-registry-private-link)
