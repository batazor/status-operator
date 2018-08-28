# status-operator
Service (CRD) for view status public services run in K8S

### How does it work?

1. Create CRD

```
version: status.v1
kind: status-page
```

2. Aggregate all `status-page` in one page
