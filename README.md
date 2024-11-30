


To make changes to the labels in your config-file.yaml, follow these steps:
1- Open the config-file.yaml file in your editor.
2- Modify the labels under the metadata section as needed. For example: 
3- Save the changes to the file.
4- Apply the changes to your Kubernetes cluster

kubectl apply -f config-file.yaml
5- Verify the changes by listing the pods and their labels:
kubectl get pods --show-labels


