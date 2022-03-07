# Gitlab Integration With Jenkins

##### CI with Gitlab & CD with Jenkins

```bash
docker login registry.gitlab.com
```

- username="Name of the token"
- password="Actual Api Token"



```bash
docker build -t registry.gitlab.com/quickbooks2018/gitlab-integration-with-jenkins .
```


```bash
docker push registry.gitlab.com/quickbooks2018/gitlab-integration-with-jenkins:latest
```
