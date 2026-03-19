
# Replicationcontroller-Replicationset_05-01-26

## Commands:
  kubectl create -f replication-controller.yml /
  kubectl get po /
  kubectl get po -o wide
  kubectl get po --show-labels
  kubectl describe pod podname
  kubectl describe rc myrc
  kubectl delete rc myrc
  
  kubectl create -f service.yml
  kubectl get svc
  
  kubectl create -f replication-set.yml
  kubectl describe rs myrs
  kubectl delete rs myrs
  
  kubectl delete pod --all
