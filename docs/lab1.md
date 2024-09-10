# Lab 1

Проверка текущуй конфигурации `kubectl`.

```shell script
kubectl config view
```

Проверка соединения к кластеру:

```
kubectl cluster-info
```

Подключение к `minikube`:

```shell script
minikube ssh
```

Просмотр системых подов кластера k8s:

```shell script
kubectl get pods -n kube-system
```

Удаленине всех системных подов:

```shell script
kubectl delete pod --all -n kube-system
```