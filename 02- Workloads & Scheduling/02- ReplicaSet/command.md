#### Documentation Referred:

https://kubernetes.io/docs/concepts/workloads/controllers/replicaset/

```sh
kubectl apply -f replicaset.yaml 
```
#### Step 2: Verify Replicaset Creation
```sh
kubectl get replicaset

kubectl get pods

kubectl get pods --show-labels
```
#### Step 3: Scaling ReplicaSet
```sh
kubectl scale --replicas=5 rs/frontend-replicaset
kubectl scale --replicas=1 rs/frontend-replicaset
```

#### Step 4: Delete Replica Set
```sh
kubectl delete -f replicaset.yaml