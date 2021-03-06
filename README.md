# Description

Docker image with all the commonly used tools to build Java applications on Jenkins slaves.

We have decided to bundle many tools in the same image to cover as many Java use cases as possible. In a second iteration, we plan to offer granularity in the tools installed on the image, maybe using a `Dockerfile` generator.

# Supported tags and respective `Dockerfile` links

-   [`latest` (*latest/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/master/Dockerfile)
-   [`1.0.1` (*1.0.1/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/1.0.1/Dockerfile)
-   [`1.0.0` (*1.0.0/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/1.0.0/Dockerfile)
-   [`0.0.7.1` (*0.0.7.1/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/0.0.7.1/Dockerfile)
-   [`0.0.6` (*0.0.6/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/0.0.6/Dockerfile)
-   [`0.0.5` (*0.0.5/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/0.0.5/Dockerfile)
-   [`0.0.4` (*0.0.4/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/0.0.4/Dockerfile)
-   [`0.0.3` (*0.0.3/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/0.0.3/Dockerfile)
-   [`0.0.2` (*0.0.2/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/0.0.2/Dockerfile)
-   [`0.0.1` (*0.0.1/Dockerfile*)](https://github.com/cloudbees/java-build-tools-dockerfile/blob/0.0.1/Dockerfile)

# How to use this Docker image

This Docker image is intended to be used with the [Jenkins CloudBees Docker Custom Build Environment Plugin](https://wiki.jenkins-ci.org/display/JENKINS/CloudBees+Docker+Custom+Build+Environment+Plugin) and the [Jenkins Docker Workflow Plugin](https://wiki.jenkins-ci.org/display/JENKINS/CloudBees+Docker+Workflow+Plugin).
# Version latest
-   OS: Ubuntu 15.04
-   Common tools: openssh-client, unzip, wget, curl, git
-   AWS CLI: aws-cli/1.11.360.10.8
-   Azure CLI: 0.10.8
-   Bower: 1.8.0
-   Cloud Foundry CLI (latest) at `/usr/local/bin/cf`: 6.23.1
-   Firefox (latest) at `/usr/bin/firefox`: Mozilla Firefox 44.0
-   Firefox Geckodriver v0.13.0 at `/usr/bin/geckodriver`
-   gcc (latest): 4.9.2-10ubuntu13
-   Grunt CLI: 1.2.0
-   Gulp: 3.9.1
-   Java: OpenJDK 8 (latest): 1.8.0_45
-   JMeter (3.1) located in `/opt/jmeter/`
-   Kubernetes CLI at `/usr/local/bin/kubectl`: 1.5.2
-   Make (latest): 4.0
-   Maven located in `/usr/share/maven/`: 3.3.9
-   MySQL Client: 5.6.28
-   Node.js at `/usr/bin/nodejs`: 4.4.2
-   Npm at `/usr/bin/npm`: 2.15.0
-   Open Shift V3 CLI at `/usr/local/bin/oc`: 1.3.0
-   Python/2.7.9
-   Selenium at `/opt/selenium/selenium-server-standalone.jar`: 2.53
-   Web Browser tests: XVFB (latest)

# Version 1.0.1
-   OS: Ubuntu 15.04
-   Common tools: openssh-client, unzip, wget, curl, git
-   AWS CLI: aws-cli/1.11.360.10.8
-   Azure CLI: 0.10.8
-   Bower: 1.8.0
-   Cloud Foundry CLI (latest) at `/usr/local/bin/cf`: 6.23.1
-   Firefox (latest) at `/usr/bin/firefox`: Mozilla Firefox 44.0
-   gcc (latest): 4.9.2-10ubuntu13
-   Grunt CLI: 1.2.0
-   Gulp: 3.9.1
-   Java: OpenJDK 8 (latest): 1.8.0_45
-   JMeter (3.1) located in `/opt/jmeter/`
-   Kubernetes CLI at `/usr/local/bin/kubectl`: 1.5.2
-   Make (latest): 4.0
-   Maven located in `/usr/share/maven/`: 3.3.9
-   MySQL Client: 5.6.28
-   Node.js at `/usr/bin/nodejs`: 4.4.2
-   Npm at `/usr/bin/npm`: 2.15.0
-   Open Shift V3 CLI at `/usr/local/bin/oc`: 1.3.0
-   Python/2.7.9
-   Selenium at `/opt/selenium/selenium-server-standalone.jar`: 2.53
-   Web Browser tests: XVFB (latest)

# Version 1.0.0
-   OS: Ubuntu 15.04
-   Common tools: openssh-client, unzip, wget, curl, git
-   AWS CLI: aws-cli/1.10.0
-   Azure CLI: 0.10.1
-   Bower: 1.7.9
-   Cloud Foundry CLI (latest) at `/usr/local/bin/cf`: 6.15.0
-   Firefox (latest) at `/usr/bin/firefox`: Mozilla Firefox 43.0.4
-   gcc (latest): 4.9.2-10ubuntu13
-   Grunt CLI: 0.1.2
-   Gulp: 3.9.1
-   Java: OpenJDK 8 (latest): 1.8.0_45
-   JMeter (3.0) located in `/opt/jmeter/`
-   Kubernetes CLI at `/usr/local/bin/kubectl`: 1.2.3
-   Make (latest): 4.0
-   Maven located in `/usr/share/maven/`: 3.3.9
-   MySQL Client: 5.6.27
-   Node.js at `/usr/bin/nodejs`: 4.4.2
-   Npm at `/usr/bin/npm`: 2.14.20
-   Open Shift V3 CLI at `/usr/local/bin/oc`: 1.2.0
-   Selenium at `/opt/selenium/selenium-server-standalone.jar`: 2.53
-   Web Browser tests: XVFB (latest)

# Version 0.0.7.1
-   OS: Ubuntu 15.04
-   Common tools: openssh-client, unzip, wget, curl, git
-   AWS CLI: aws-cli/1.10.35
-   Azure CLI: 0.9.14
-   Bower: 1.7.2
-   Cloud Foundry CLI (latest) at `/usr/local/bin/cf`: 6.18.1
-   Firefox (latest) at `/usr/bin/firefox`: Mozilla Firefox 44
-   gcc (latest): 4.9.2-10ubuntu13
-   Grunt CLI: 0.1.13
-   Gulp: 3.9.0
-   Java: OpenJDK 8 (latest): 1.8.0_45
-   JMeter (3.0) located in `/opt/jmeter/`
-   Kubernetes CLI at `/usr/local/bin/kubectl`: 1.2.3
-   Make (latest): 4.0
-   Maven located in `/usr/share/maven/`: 3.3.9
-   MySQL Client (latest): 5.6.28
-   Node.js: 4.4.2
-   Open Shift V3 CLI at `/usr/local/bin/oc`: 1.2.0
-   Selenium at `/opt/selenium/selenium-server-standalone.jar`: 2.49.1
-   Web Browser tests: XVFB (latest)

# Version 0.0.6

This version has been tested with Docker 1.9.1

-   OS: Ubuntu 15.04
-   Common tools: unzip, wget, curl, git
-   Make (latest): 4.0
-   gcc (latest): 4.9.2-10ubuntu13
-   Java: OpenJDK 8 (latest): 1.8.0_45
-   Maven located in `/usr/share/maven/`: 3.3.9
-   Node.js: 4.2.4
-   Bower: 1.7.2
-   Grunt CLI: 0.1.13
-   Gulp: 3.9.0
-   Web Browser tests: XVFB (latest)
-   Firefox (latest) at `/usr/bin/firefox`: Mozilla Firefox 43.0.4
-   Selenium at `/opt/selenium/selenium-server-standalone.jar`: 2.48.2
-   AWS CLI: 1.9.17
-   Azure CLI: 0.9.13
-   Cloud Foundry CLI (latest) at `/usr/local/bin/cf`
-   Open Shift V3 CLI at `/usr/local/bin/oc`: 1.1.0.1
-   JMeter (2.13) located in `/opt/jmeter/`
-   Kubernetes CLI at `/usr/local/bin/kubectl`: 1.1.3
-   MySQL Client (latest): 5.6.27

# Release Notes

See the [GitHub release notes](https://github.com/cloudbees/java-build-tools-dockerfile/releases).

# About this repository

This repository is available on [github.com/cloudbees/java-build-tools-dockerfile/](https://github.com/cloudbees/java-build-tools-dockerfile), and the automated build is on the [Docker Hub](https://hub.docker.com/r/cloudbees/java-build-tools/).

# User Feedback

## Issues

If you have any problems with or questions about this image, please submit a [GitHub issue](https://github.com/cloudbees/java-build-tools-dockerfile/issues).

## Contributing

If you have a contribution for this repository, please send a pull request.

If you want to contribute to Jenkins CI, see the [Contributing to Jenkins](https://wiki.jenkins-ci.org/display/JENKINS/contributing).

# License

The cloudbees/java-build-tools image is licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0), and this repository is too:

```
Copyright 2015 CloudBees, Inc


Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
