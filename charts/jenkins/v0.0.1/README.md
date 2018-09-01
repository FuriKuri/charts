# Jenkins

[Jenkins](https://jenkins.io/) - The leading open source automation server, Jenkins provides hundreds of plugins to support building, deploying and automating any project.

## Configuration

The following table lists the configurable parameters of the jenkins charts and their default values.

| Parameter                   | Description                                                                                   | Default                     |
|-----------------------------|-----------------------------------------------------------------------------------------------|-----------------------------|
| `images.server.repository`  | Jenkins **server** image                                                                        | `furikuri/jenkins-lab`      |
| `images.server.tag`         | Jenkins **server** image tag                                                                    | `2.140`                     |
| `images.server.pullPolicy`  | Jenkins **server** image pull policy                                                            | `IfNotPresent`              |
| `helloWorld`                | Jenkins **echo** text in demo job                                                               | `Hello World`               |
| `service.httpPort`          | Jenkins **service** http port                                                                   | `furikuri/jenkins-lab`      |
| `service.type`              | Jenkins **service** type                                                                        | `2.140`                     |
| `ingress.enabled`           | Jenkins **ingress** enabled                                                                     | `furikuri/jenkins-lab`      |
| `persistence.enabled`       | Jenkins home **persistence** enabled                                                            | `2.140`                     |
| `persistence.size`          | Jenkins home **persistence** size                                                               | `IfNotPresent`              |
| `resources.requests.memory` | Jenkins **requests** memory                                                                     | `2.140`                     |
| `resources.requests.cpu`    | Jenkins **requests** cpu                                                                        | `IfNotPresent`              |
