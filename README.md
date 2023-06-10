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

<img width="736" alt="Screenshot 2023-06-10 at 11 40 59" src="https://github.com/Mamiololo01/Learning-rabbitMQ-with-NodeJS/assets/67044030/faab112a-0416-4b21-b2f6-1fe6e715bdb0">

<img width="721" alt="Screenshot 2023-06-10 at 16 04 13" src="https://github.com/Mamiololo01/Learning-rabbitMQ-with-NodeJS/assets/67044030/4489f084-e033-4c22-9025-cb1f7b58aa6a">

Initiatize the project

<img width="794" alt="Screenshot 2023-06-10 at 11 47 25" src="https://github.com/Mamiololo01/Learning-rabbitMQ-with-NodeJS/assets/67044030/b5c4592a-adac-4598-a93a-da92f6bc117f">

Then build.a publisher
Create a publisher.js file and initialise npm

It creates the package.json file and install the required dependencies

Install amqplib via npm which is a major dependency

<img width="793" alt="Screenshot 2023-06-10 at 12 16 35" src="https://github.com/Mamiololo01/Learning-rabbitMQ-with-NodeJS/assets/67044030/b220b8f3-9473-4de3-a395-8f0b7077a02a">

Then create the consumer.js file and initiatize via npm

To punish a message

npm run publish

To consume a message

npm run consume

npm run publish x

npm run consume y


<img width="841" alt="Screenshot 2023-06-10 at 16 09 57" src="https://github.com/Mamiololo01/Learning-rabbitMQ-with-NodeJS/assets/67044030/337d007b-47db-493d-b76b-9adc77e22b4a">

<img width="920" alt="Screenshot 2023-06-10 at 16 10 35" src="https://github.com/Mamiololo01/Learning-rabbitMQ-with-NodeJS/assets/67044030/a78af191-927c-433d-a825-4c7c8d921d66">

<img width="737" alt="Screenshot 2023-06-10 at 16 11 19" src="https://github.com/Mamiololo01/Learning-rabbitMQ-with-NodeJS/assets/67044030/3b92e2df-17a1-4279-8daf-7df38d5e94e8">
