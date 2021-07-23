# Wordpress Sample App with MySQL

kustomization.yaml은 WordPress 사이트와 MySQL 데이터베이스를 배포하는 모든 리소스를 포함한다. 
다음과 같이 디렉터리를 적용한다. 

```
kubectl apply -k ./
kubectl get svc
kubectl get pod
```

