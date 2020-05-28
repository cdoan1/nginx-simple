# nginx-simple

This repo is an example of a simple nginx application.

```
oc apply -k subscription
```

```
(base) ➜  nginx-simple git:(master) oc apply -k subscription                                       (default/api-south-demo-red-chesterfield-com:6443/kube:admin)
namespace/nginx-simple created
application.app.k8s.io/nginx-simple created
channel.apps.open-cluster-management.io/nginx-simple created
placementrule.apps.open-cluster-management.io/nginx-simple created
subscription.apps.open-cluster-management.io/nginx-simple-subscription created
```

