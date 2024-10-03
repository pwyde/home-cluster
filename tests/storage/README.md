# Storage Tests

## Speedtest - `truenas-ssd-iscsi`

Test the provisioning, mounting, and performance of using `truenas-ssd-iscsi` storage class.
```sh
kubectl apply -f ./tests/storage/speedtest-truenas-ssd-iscsi.yaml
```

Pod logs for **read** test:
```sh
kubectl logs -l app=speedtest,job=read
```

Pod logs for **write** test:
```sh
kubectl logs -l app=speedtest,job=write
```

Delete the artifacts created from the speedtest.
```sh
kubectl delete -f ./tests/storage/speedtest-truenas-ssd-iscsi.yaml
```

## Speedtest - `truenas-ssd-nfs`

Test the provisioning, mounting, and performance of using `truenas-ssd-nfs` storage class.
```sh
kubectl apply -f ./tests/storage/speedtest-truenas-ssd-nfs.yaml
```
Pod logs for **read** test:
```sh
kubectl logs -l app=speedtest,job=read
```

Pod logs for **write** test:
```sh
kubectl logs -l app=speedtest,job=write
```

Delete the artifacts created from the speedtest.
```sh
kubectl delete -f ./tests/storage/speedtest-truenas-ssd-nfs.yaml
```
