# Jenkins

[Jenkins](https://jenkins.io/) - The leading open source automation server, Jenkins provides hundreds of plugins to support building, deploying and automating any project.

## Configuration

The following table lists the configurable parameters of the jenkins charts and their default values.

| Parameter                   | Description                                                                                   | Default                     |
|-----------------------------|-----------------------------------------------------------------------------------------------|-----------------------------|
| `images.server.repository`  | Jenkins **server** image                                                                        | `furikuri/jenkins-lab`     |
| `images.server.tag`         | Jenkins **server** image tag                                                                    | `2.138`                     |
| `images.server.pullPolicy`  | Jenkins **server** image pull policy                                                            | `IfNotPresent`              |