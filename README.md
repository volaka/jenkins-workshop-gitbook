# Introduction

This guide describes how to deploy Jenkins on IBM Cloud Kubernetes Service with Helm and proper basic configuration.

## Prerequisites

* You should have a standard kubernetes cluster from IBM Cloud. [https://cloud.ibm.com/kubernetes/catalog/about](https://cloud.ibm.com/kubernetes/catalog/about)
* You should have [ibmcloud cli](https://cloud.ibm.com/docs/cli?topic=cli-getting-started) and [helm](https://helm.sh/docs/intro/install/) installed on your workspace or you are using [IBM Cloud Shell](https://www.ibm.com/cloud/cloud-shell).

## Notes

This workshop is tested with the following technologies and versions.

| Technology | Version |
| :--- | :--- |
| IBM Cloud Kubernetes Service | 1.18.8\_1525 |
| Helm | v2.16.7 \(client\) |
| kubectl | 1.16.2 \(client\) |
| ibmcloud cli | 1.2.1+29ade2b |
| volaka/ibm-cloud-cli | 1.2.1 |
| jenkins \(helm-chart\) | 2.5.4 |

## Contribution

If you found errors, please create an issue to [https://github.com/volaka/jenkins-workshop-gitbook](https://github.com/volaka/jenkins-workshop-gitbook) repo.

Thank you!

