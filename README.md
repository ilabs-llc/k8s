# k8s
Demo projects for k8s


```sh
 az aks create -n nameOfMyaks -g AKSDemo --network-plugin azure --enable-managed-identity -a ingress-appgw --appgw-name nameOfMyk8sAppGateway --appgw-subnet-cidr "10.2.0.0/16" --generate-ssh-keys
```
