# Minikube Commands.





## Contents at a Glance.
* [About.](#about)
* [Documentation.](#documentation)
* [minikube delete](#minikube-delete)
* [minikube start](#minikube-start)
* [minikube stop](#minikube-stop)
* [minikube ssh](#minikube-ssh)
* [minikube version](#minikube-version)
* [minikube addons](#minikube-addons)
* [Help.](#help)





## About.





## Documentation.





## General Commands.

| Key/Command                                                        | Description                                                                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| minikube service [name] --url                                      |                                                                                                                    |
|                                                                    |                                                                                                                    |





## minikube start 

| Key/Command                                                        | Description                                                                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| minikube start                                                     | Create and run VM instance with K8s Mini Cluster with default parameters.                                          |
| minikube start -p nameCluster                                      | Create and run VM instance with K8s Mini Cluster with default parameters and with the defined "nameCluster".       |
| minikube start --vm=true                                           |                                                                                                                    |
| minikube start --vm=true --addons ingress                          |                                                                                                                    |
|                                                                    |                                                                                                                    |

* Not Work
`minikube start --vm=true --cpus=4 --memory=6144`
`minikube start --cps=4 --memory=8gb --disk-size=25gb`
`minikube start --cps=4 --memory=8000mb --disk-size=25gb`





## minikube stop

| Key/Command                                                        | Description                                                             |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| minikube stop                                                      | Stop VM instance with K8s Mini Cluster.                                 |





## minikube delete

| Key/Command                                                        | Description                                                             |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| minikube delete                                                    | Delete VM instance with K8s Mini Cluster.                               |



## minikube ssh

| Key/Command                                                        | Description                                                             |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| minikube config set cpus [amountCPUs]                              |                                                                         |
| minikube config set memory [amountMemory]                          |                                                                         |
| minikube delete                                                    |                                                                         |
| minikube config get cpus                                           |                                                                         |
| minikube config get memory                                         |                                                                         |
|                                                                    |                                                                         |


## minikube ssh

| Key/Command                                                        | Description                                                             |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| minikube ssh                                                       | Login in to the VM instance with K8s Mini Cluster.                      |




## minikube version

| Key/Command                                                        | Description                                                             |
| ------------------------------------------------------------------ | ----------------------------------------------------------------------- |
| minikube version                                                   | Show version of minikube.                                               |





## minikube addons.

| Key/Command                                                        | Description                                                                                                        |
| ------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------ |
| minikube addons list                                               |                                                                                                                    |
| minikube addons enable [ADDONS_NAME]                               |                                                                                                                    |
| minikube addons disable [ADDONS_NAME]                              |                                                                                                                    |
| minikube addons open   [ADDONS_NAME]                               |                                                                                                                    |
|                                                                    |                                                                                                                    |





## Help.
