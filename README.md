# tekton-hello-world

```
kubectl port-forward service/el-hellow-world-eventlistener 8081:8080 &

curl localhost:8081 -d '{"username": "Tekton"}'
```