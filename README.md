# Oracle Java (s6-overlay) Docker Image

[![Docker Pulls](https://img.shields.io/docker/pulls/frekele/java.svg)](https://hub.docker.com/r/frekele/java/)
[![Docker Stars](https://img.shields.io/docker/stars/frekele/java.svg)](https://hub.docker.com/r/frekele/java/)
[![GitHub issues](https://img.shields.io/github/issues/frekele/docker-java.svg)](https://github.com/frekele/docker-java/issues)
[![GitHub forks](https://img.shields.io/github/forks/frekele/docker-java.svg)](https://github.com/frekele/docker-java/network)
[![GitHub stars](https://img.shields.io/github/stars/frekele/docker-java.svg)](https://github.com/frekele/docker-java/stargazers)
[![Website](https://img.shields.io/website-up-down-green-red/http/shields.io.svg)](https://frekele.github.io/docker-java/)

[![Java Image][JavaImage]][JavaWebsite]

| [Website]  | [GitHub]  | [DockerHub]  |


#### Oracle JDK Branches:
| Branch                | From                     | Usage        | Tag Names                                      |
| --------------------- | ------------------------ | ------------ | ---------------------------------------------- |
| [jdk8u102] - latest   | frekele/debian:stable    | Production   | jdk8u102, 8u102, jdk8, 8, latest               |
| [jdk8u101]            | frekele/debian:stable    | Production   | jdk8u101, 8u101                                |
| [jdk8u92]             | frekele/debian:stable    | Production   | jdk8u92, 8u92                                  |
| [jdk8u91]             | frekele/debian:stable    | Production   | jdk8u91, 8u91                                  |
| [jdk8u77]             | frekele/debian:stable    | Production   | jdk8u77, 8u77                                  |
| [jdk8u74]             | frekele/debian:stable    | Production   | jdk8u74, 8u74                                  |
| [jdk8u73]             | frekele/debian:stable    | Production   | jdk8u73, 8u73                                  |
| [jdk8u72]             | frekele/debian:stable    | Production   | jdk8u72, 8u72                                  |
| [jdk8u71]             | frekele/debian:stable    | Production   | jdk8u71, 8u71                                  |
| [jdk8u66]             | frekele/debian:stable    | Production   | jdk8u66, 8u66                                  |
| [jdk8u65]             | frekele/debian:stable    | Production   | jdk8u65, 8u65                                  |
| [jdk8u60]             | frekele/debian:stable    | Production   | jdk8u60, 8u60                                  |
| [jdk8u51]             | frekele/debian:stable    | Production   | jdk8u51, 8u51                                  |
| [jdk7u80]             | frekele/debian:stable    | Production   | jdk7u80, 7u80, jdk7, 7                         |
| [jdk7u79]             | frekele/debian:stable    | Production   | jdk7u79, 7u79                                  |
| [jdk7u76]             | frekele/debian:stable    | Production   | jdk7u76, 7u76                                  |
| [jdk7u75]             | frekele/debian:stable    | Production   | jdk7u75, 7u75                                  |
| [jdk7u72]             | frekele/debian:stable    | Production   | jdk7u72, 7u72                                  |
| [jdk7u71]             | frekele/debian:stable    | Production   | jdk7u71, 7u71                                  |
| [jdk8dev]             | frekele/debian:stable    | Development  | jdk7dev                                        |
| [jdk7dev]             | frekele/debian:stable    | Development  | jdk8dev                                        |

# Dockerfile extends From:
- https://github.com/frekele/docker-debian
- https://hub.docker.com/r/frekele/debian

## Relations:
 - https://github.com/just-containers/s6-overlay


## Run Java container with the trusted SSL certificates:
````
docker run --rm -v /mnt/vol-ssl/trusted:/opt/ssl/trusted --name java frekele/java
````


### License:
See [ORACLE LICENSE]

frekele/docker-java is **licensed** under the **[MIT License]**. The terms of the license are as follows:

    The MIT License (MIT)

    Copyright (c) 2016 Leandro Kersting de Freitas

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.


[JavaImage]: https://raw.githubusercontent.com/frekele/docker-java/jdk8dev/java-logo.png
[JavaWebsite]: http://www.oracle.com/technetwork/pt/java/javase/downloads/index.html
[Website]: https://frekele.github.io/docker-java
[GitHub]: https://github.com/frekele/docker-java
[DockerHub]: https://hub.docker.com/r/frekele/java
[ORACLE LICENSE]: http://www.oracle.com/technetwork/java/javase/terms/license/index.html
[MIT LICENSE]: https://github.com/frekele/docker-java/blob/jdk8dev/LICENSE

[jdk8u102]: https://github.com/frekele/docker-java/blob/jdk8u102/Dockerfile
[jdk8u101]: https://github.com/frekele/docker-java/blob/jdk8u101/Dockerfile
[jdk8u92]: https://github.com/frekele/docker-java/blob/jdk8u92/Dockerfile
[jdk8u91]: https://github.com/frekele/docker-java/blob/jdk8u91/Dockerfile
[jdk8u77]: https://github.com/frekele/docker-java/blob/jdk8u77/Dockerfile
[jdk8u74]: https://github.com/frekele/docker-java/blob/jdk8u74/Dockerfile
[jdk8u73]: https://github.com/frekele/docker-java/blob/jdk8u73/Dockerfile
[jdk8u72]: https://github.com/frekele/docker-java/blob/jdk8u72/Dockerfile
[jdk8u71]: https://github.com/frekele/docker-java/blob/jdk8u71/Dockerfile
[jdk8u66]: https://github.com/frekele/docker-java/blob/jdk8u66/Dockerfile
[jdk8u65]: https://github.com/frekele/docker-java/blob/jdk8u65/Dockerfile
[jdk8u60]: https://github.com/frekele/docker-java/blob/jdk8u60/Dockerfile
[jdk8u51]: https://github.com/frekele/docker-java/blob/jdk8u51/Dockerfile
[jdk7u80]: https://github.com/frekele/docker-java/blob/jdk7u80/Dockerfile
[jdk7u79]: https://github.com/frekele/docker-java/blob/jdk7u79/Dockerfile
[jdk7u76]: https://github.com/frekele/docker-java/blob/jdk7u76/Dockerfile
[jdk7u75]: https://github.com/frekele/docker-java/blob/jdk7u75/Dockerfile
[jdk7u72]: https://github.com/frekele/docker-java/blob/jdk7u72/Dockerfile
[jdk7u71]: https://github.com/frekele/docker-java/blob/jdk7u71/Dockerfile
[jdk8dev]: https://github.com/frekele/docker-java/blob/jdk8dev/Dockerfile
[jdk7dev]: https://github.com/frekele/docker-java/blob/jdk7dev/Dockerfile
