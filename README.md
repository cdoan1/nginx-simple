# nginx-simple

This repo is an example of a simple nginx application. The subscription references a channel to this repo, deploying the nginx/deployment folder to the target managed cluster.

1. apply the subscription

```bash
(base) ➜  nginx-simple git:(master) oc apply -k subscription
namespace/nginx-simple created
application.app.k8s.io/nginx-simple created
channel.apps.open-cluster-management.io/nginx-simple created
placementrule.apps.open-cluster-management.io/nginx-simple created
subscription.apps.open-cluster-management.io/nginx-simple-subscription created
```
