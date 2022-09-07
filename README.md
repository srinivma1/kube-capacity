# kube-capacity
This will show how to use kube-capacity to show the capacity and utilization of pods and nodes in the kubernetes cluster.


Refer to the below URL:

https://medium.com/@able8/check-kubernetes-resource-reqeusts-limits-and-utilization-with-kube-capacity-cli-b00bf2f4acc9


```
 wget https://github.com/robscott/kube-capacity/releases/download/v0.7.1/kube-capacity_0.7.1_Linux_x86_64.tar.gz
 tar -xf kube-capacity_0.7.1_Linux_x86_64.tar.gz
 ls -la
 cd kube-capacity
 mv kube-capacity /usr/bin/
 chmod +x kube-capacity
 sudo mv kube-capacity /usr/bin/
 kube-capacity --pods
 
 ```
