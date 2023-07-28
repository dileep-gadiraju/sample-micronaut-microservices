## Quick Guide to Microservices with Micronaut Framework [![Twitter](https://img.shields.io/twitter/follow/piotr_minkowski.svg?style=social&logo=twitter&label=Follow%20Me)](https://twitter.com/piotr_minkowski)

[![CircleCI](https://circleci.com/gh/piomin/sample-micronaut-microservices.svg?style=svg)](https://circleci.com/gh/piomin/sample-micronaut-microservices)

[![SonarCloud](https://sonarcloud.io/images/project_badges/sonarcloud-black.svg)](https://sonarcloud.io/dashboard?id=piomin_sample-micronaut-microservices)
[![Bugs](https://sonarcloud.io/api/project_badges/measure?project=piomin_sample-micronaut-microservices&metric=bugs)](https://sonarcloud.io/dashboard?id=piomin_sample-micronaut-microservices)
[![Coverage](https://sonarcloud.io/api/project_badges/measure?project=piomin_sample-micronaut-microservices&metric=coverage)](https://sonarcloud.io/dashboard?id=piomin_sample-micronaut-microservices)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=piomin_sample-micronaut-microservices&metric=ncloc)](https://sonarcloud.io/dashboard?id=piomin_sample-micronaut-microservices)

1. Detailed description can be found here: [Quick Guide to Microservices with Micronaut Framework](https://piotrminkowski.com/2019/01/25/quick-guide-to-microservices-with-micronaut-framework/)

2. Detailed description can be found here: [Microservices with Micronaut, KrakenD and Consul](https://piotrminkowski.com/2021/02/23/microservices-with-micronaut-krakend-and-consul/)

Run Hashicorp consul:

> `docker pull docker.io/consul:1.15.4`

> `docker run -d --name consul -p 8500:8500 consul:1.15.4 `

Open [HashiCorp Consul Dashboard](http://localhost:8500/)

Run Zipkin

>`docker run -d -p 9411:9411 openzipkin/zipkin`

>Open [Zipkin Dashboard](http://localhost:9411/zipkin/)

App Links:

>[http://localhost:62180/swagger/employees-management-1.0.yml](http://localhost:62180/swagger/employees-management-1.0.yml)

>[http://localhost:62142/swagger/organizations-management-1.0.yml](http://localhost:62142/swagger/organizations-management-1.0.yml)

>[http://localhost:62161/swagger/departments-management-1.0.yml](http://localhost:62161/swagger/departments-management-1.0.yml)

>[http://localhost:62180/employees](http://localhost:62180/employees)

>[http://localhost:62180/employees/department/9](http://localhost:62180/employees/department/9)

>[http://localhost:62142/organizations](http://localhost:62142/organizations)