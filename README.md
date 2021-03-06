# AzureKubernetesService-ELK

# PART 1:

This is the sample source code for setting up Elasticsearch, Logstash and Kibana cluster in Azure Kubernetes Service (AKS) and consume messages from Event Hub.

A sample client App (e.g. IOT device) will be publishing messages to Event Hub and these messages will be ingested into Elasticsearch using 'Azure Event Hub' plugin of Logstash. The dev tools used to develop these components are Visual Studio for Mac/Visual Studio 2017, AKS Dashboard as well as kubectl commands are used to create/manager Kubernetes resources in AKS.

You can read details @ https://blogs.msdn.microsoft.com/atverma/2018/09/24/azure-kubernetes-service-aks-deploying-elasticsearch-logstash-and-kibana-elk-and-consume-messages-from-azure-event-hub/

# PART 2: 

Code samples for second part of the series on deploying Elasticsearch, Logstash and Kibana (ELK) to Azure Kubernetes Service cluster under 'AZURE AD SAML SSO' folder. These samples are created to enable Azure AD SAML based single sign on to secure Elasticsearch and Kibana cluster hosted in AKS. I will also cover the steps needed to encrypt communications in ELK cluster.

Using SAML SSO for Elasticsearch with AAD means that Elasticsearch does not need to be seeded with any user accounts from the directory. Instead, Elasticsearch is able to rely on the claims sent within a SAML token in response to successful authentication to determine identity and privileges.

You can read details @ https://blogs.msdn.microsoft.com/atverma/2018/10/09/azure-kubernetes-service-aks-azure-ad-saml-based-single-sign-on-to-secure-elasticsearch-and-kibana-and-securing-communications-in-elk/

