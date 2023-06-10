# Learning-rabbitMQ-with-NodeJS
RabbitMQ is the most widely deployed open source message broker.
With tens of thousands of users, RabbitMQ is one of the most popular open source message brokers. From T-Mobile to Runtastic, RabbitMQ is used worldwide at small startups and large enterprises.

RabbitMQ is lightweight and easy to deploy on premises and in the cloud. It supports multiple messaging protocols. RabbitMQ can be deployed in distributed and federated configurations to meet high-scale, high-availability requirements.

RabbitMQ runs on many operating systems and cloud environments, and provides


Asynchronous Messaging

Supports multiple messaging protocols, message queuing, delivery acknowledgement, flexible routing to queues, multiple exchange type.


Developer Experience

Deploy with Kubernetes, BOSH, Chef, Docker and Puppet. Develop cross-language messaging with favorite programming languages such as: Java, .NET, PHP, Python, JavaScript, Ruby, Go, and many others.


Distributed Deployment

Deploy as clusters for high availability and throughput; federate across multiple availability zones and regions.

Enterprise & Cloud Ready

Pluggable authentication, authorisation, supports TLS and LDAP. Lightweight and easy to deploy in public and private clouds.


Tools & Plugins

Diverse array of tools and plugins supporting continuous integration, operational metrics, and integration to other enterprise systems. Flexible plug-in approach for extending RabbitMQ functionality.


Management & Monitoring

HTTP-API, command line tool, and UI for managing and monitoring RabbitMQ

Spin rabbitmq server docker
docker run --name rabbitmq -p 5672:5672 -d rabbitmq

Spin rabbitmq server HTTP server docker
docker run --name rabbitmq -p 5672:5672 -p 15672:15672 -d rabbitmq:3-management

Then build.a publisher
Create a publisher.js file and initialise npm

It creates the package.json file and install the required dependencies

Install amqplib via npm which is a major dependency

Then create the consumer.js file and initiatize via npm

To punish a message
Npm run publish
To consume a message
Npm run consume

Npm run publish x
Npm run consume y
Will show x and y
