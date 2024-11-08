# CMD

### READY
- run dashboard
```bash
$ minikube addons list
$ minikube addons enable metrics-server
$ minikube addons enable dashboard
$ minikube addons list
$ minikube dashboard --url
```

```bash
# 배포 적용
$ kubectl apply -f httpd-deployment.yaml
```

```bash
$ helm install cnp ngpd
$ helm list
$ helm status cnp
$ helm delete cnp
$ helm upgrade cnp ngpd
$ helm rollback cnp
$ helm rollback cnp 2
$ helm history cnp
```
