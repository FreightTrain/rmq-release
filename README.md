# rmq-release

A [BOSH](http://docs.cloudfoundry.org/bosh/) release for:

* [RabbitMQ](http://www.rabbitmq.com/)
* A [Cloud Foundry RabbitMQ Service Broker (V2)](https://github.com/nimbus-cloud/cf-rabbitmq-broker) 

## Using this release

### BoshLite

1. Grab the [boshlite sample manifest](https://github.com/FreightTrain/rmq-release/blob/master/templates/boshlite-example-manifest.yml)
2. Alter the manifest adding your ```director_uuid```
3. Deploy it!

### AWS

1. Grab the [aws sample manifest](https://github.com/FreightTrain/rmq-release/blob/master/templates/aws-example-manifest.yml)
2. Alter the manifest to meet your needs
3. Deploy it!

### Management

The [RabbitMQ Web management plugin](https://www.rabbitmq.com/management.html) is enabled by default. The credentials are specified in the BOSH manifest.

## Thanks

Thanks to [Michal Jemala ](https://github.com/michaljemala) and [Ryan Grenz](https://github.com/grenzr) for their work on the RabbitMQ Cloud Foundry service broker.




