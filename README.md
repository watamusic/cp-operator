# cp-operator

A 'fork' of the Confluent Helm Operator with some custom functionality

## Build

To build the operator bundle, you just need to bundle the source with the following command:

```
tar -C . -cvzf confluent-operator-1.6.0-for-
confluent-platform-6.0.0.tar.gz COPYRIGHT helm/ resources/ grafana-dashboard/ IMAGES
```
