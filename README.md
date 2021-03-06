
# pact-demo

Demonstrate pact

A full end to end demonstration of consumer driven contract testing using pact framework.

* Ability to run pact broker locally using docker containers
* Run and publish pacts for jvm and js consumers
* Verify against a running microservice

## Pact Broker startup

`docker-compose up --build`

Access at http://localhost:80

[![Join the chat at https://gitter.im/shavo007/pact-demo](https://badges.gitter.im/shavo007/pact-demo.svg)](https://gitter.im/shavo007/pact-demo?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)


Development tracked on waffle.io

https://waffle.io/shavo007/pact-demo

[![Stories in Ready](https://badge.waffle.io/shavo007/pact-demo.png?label=ready&title=Ready)](https://waffle.io/shavo007/pact-demo)

## Elastic beanstalk

http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create_deploy_docker-eblocal.html

http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/applications-sourcebundle.html

### Troubleshooting ebs and docker
http://www.eq8.eu/blogs/25-common-aws-elastic-beanstalk-docker-issues-and-solutions

eb init



### Commands
`eb local run`
`eb local open`
`eb local status`


`eb use Sample-env-1`
`eb deploy eb use Sample-env-1`




## Pact broker postgres docker container

https://store.docker.com/community/images/shanelee007/docker-pact-postgres

## Resources
Blog:  http://shavo007.github.io/2016/07/19/consumer-driven-contract-testing-using-pact/

Docker compose file: https://gist.github.com/shavo007/6660cd3230188a094b5d7d3e0647d769


![pact broker]( http://shavo007.github.io/content/images/2016/07/Screen-Shot-2016-07-30-at-8-18-09-PM.png)
