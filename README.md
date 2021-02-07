k8scloak

---

> Deploy Keycloak to kubernetes cluster

## From Local

```sh
kubectl apply -k keycloak
```

## From CI

Push code will trigger auto deploy by Travis CI, but you need to change the .travis.yml file to update the cluster configurations.