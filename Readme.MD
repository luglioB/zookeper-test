```
task run
kubectl port-forward --namespace default svc/zookeeper 2181:2181
python client/configure.py
python client/listen.py
python client/update.py
```