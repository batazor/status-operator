# status-operator
Service (CRD) for reviwing the status of public services run in K8S

### How does it work?

1. Create CRD

```
version: status.v1
kind: status-page
spec:
  title: go-auth
  description: Serive JWT-authentication
```

2. Aggregate all `status-page` in one page

### Prototype UI

![Prototype UI](https://raw.githubusercontent.com/batazor/status-operator/master/1.1-Screen%201.png)
