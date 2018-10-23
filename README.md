# Shipping-rabbitmq

In order for the `shipping` service to run, a rabbitmq message queue is needed.
The provided deployment files create a database in either a staging or production namespace.

## Usage
Inside either the `dev`, `staging` or `production` folder

```
kubectl create -f .
```
