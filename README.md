## To make changes to the labels in your config-file.yaml, follow these steps:	
- Open the config-file.yaml file in your editor.
- Modify the labels under the metadata section as needed. For example: 
- Save the changes to the file.
- Apply the changes to your Kubernetes cluster

kubectl apply -f config-file.yaml
- Verify the changes by listing the pods and their labels:
kubectl get pods --show-labels


