# k6-example
Example k6 load generator to replace default locust loadgenerator for [Online Boutique](https://github.com/GoogleCloudPlatform/microservices-demo/tree/main)

## Environmental variables
|Variable|Description|
|--------|-----------|
|`TOTAL_ARRIVAL_RATE`|Requests per second|
|`DURATION`|Duration of load test|
|`TEST_NAME`|Name label to add on metrics|

## Usage
```sh
kubectl apply -k base
```
