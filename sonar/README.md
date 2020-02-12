# Setting up password for postgress.
- Type the command below from within the cluster along with password to setup the secret
```
kubectl create secret generic postgres --from-literal=password=<password>
```