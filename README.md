# Description

[pplenik/sbt-build-tool-dockerfile](https://hub.docker.com/r/pplenik/sbt-build-tool-dockerfile/)

Docker image with all the commonly used tools to build Scala applications on Jenkins slaves.

I decided to extend [cloudbees/java-build-tools-dockerfile](https://hub.docker.com/r/cloudbees/java-build-tools/)
image adding scala support.

# Supported tags and respective `Dockerfile` links


-   [`latest` (*latest/Dockerfile*)](https://github.com/jupeter/sbt-build-tool-dockerfile/blob/master/Dockerfile)
-   [`2.2.0` (*0.0.1/Dockerfile*)](https://github.com/jupeter/sbt-build-tool-dockerfile/blob/1.1.0/Dockerfile)

# How to use this Docker image

This Docker image is intended to be used with the [Jenkins Docker Pipeline Plugin](https://wiki.jenkins-ci.org/display/JENKINS/CloudBees+Docker+Pipeline+Plugin).

# Version 1.1.0

Use cloudbees/java-build-tools-dockerfile - version 2.2.0

-   OS: Ubuntu 16.04
-   Sbt: 1.0.2
-   Common tools: openssh-client, unzip, wget, curl, git, jq
-   AWS CLI: aws-cli/1.11.163
-   Azure CLI: 0.10.8
-   Bower: 1.8.0
-   Cloud Foundry CLI (latest) at `/usr/local/bin/cf`: 6.32.0
-   Firefox at `/usr/bin/firefox`: 56
-   Firefox Geckodriver at `/usr/bin/geckodriver`: v0.19.0
-   gcc (latest): 5.4.0
-   Grunt CLI: 1.2.0.1

-   Java: OpenJDK 8 (latest): 1.8.0_131
-   JMeter (3.3) located in `/opt/jmeter/`
-   Kubernetes CLI at `/usr/local/bin/kubectl`: 1.8.0
-   Make (latest): 4.1
-   Maven located in `/usr/share/maven/`: 3.5.0
-   MySQL Client: 5.7.19
-   Node.js at `/usr/bin/nodejs`: 6.11.3
-   Npm at `/usr/bin/npm`: 3.10.10
-   Open Shift V3 CLI at `/usr/local/bin/oc`: 3.6.0
-   Python/2.7.12
-   Selenium at `/opt/selenium/selenium-server-standalone.jar`: 3.6.0
-   XVFB: 2:1.18.4

# Version 1.0.0

Use cloudbees/java-build-tools-dockerfile - version 2.1.0

-   OS: Ubuntu 16.04
-   Sbt: 1.0.2
-   Common tools: openssh-client, unzip, wget, curl, git, jq
-   AWS CLI: aws-cli/1.11.163
-   Azure CLI: 0.10.8
-   Bower: 1.8.0
-   Cloud Foundry CLI (latest) at `/usr/local/bin/cf`: 6.32.0
-   Firefox at `/usr/bin/firefox`: 56
-   Firefox Geckodriver at `/usr/bin/geckodriver`: v0.19.0
-   gcc (latest): 5.4.0
-   Grunt CLI: 1.2.0.1

-   Java: OpenJDK 8 (latest): 1.8.0_131
-   JMeter (3.3) located in `/opt/jmeter/`
-   Kubernetes CLI at `/usr/local/bin/kubectl`: 1.8.0
-   Make (latest): 4.1
-   Maven located in `/usr/share/maven/`: 3.5.0
-   MySQL Client: 5.7.19
-   Node.js at `/usr/bin/nodejs`: 6.11.3
-   Npm at `/usr/bin/npm`: 3.10.10
-   Open Shift V3 CLI at `/usr/local/bin/oc`: 3.6.0
-   Python/2.7.12
-   Selenium at `/opt/selenium/selenium-server-standalone.jar`: 3.6.0
-   XVFB: 2:1.18.4

# Version 0.0.2

Use cloudbees/java-build-tools-dockerfile - version 2.1.0

-   OS: Ubuntu 16.04
-   Sbt: 0.13.16
-   Common tools: openssh-client, unzip, wget, curl, git, jq
-   AWS CLI: aws-cli/1.11.163
-   Azure CLI: 0.10.8
-   Bower: 1.8.0
-   Cloud Foundry CLI (latest) at `/usr/local/bin/cf`: 6.32.0
-   Firefox at `/usr/bin/firefox`: 56
-   Firefox Geckodriver at `/usr/bin/geckodriver`: v0.19.0
-   gcc (latest): 5.4.0
-   Grunt CLI: 1.2.0.1

-   Java: OpenJDK 8 (latest): 1.8.0_131
-   JMeter (3.3) located in `/opt/jmeter/`
-   Kubernetes CLI at `/usr/local/bin/kubectl`: 1.8.0
-   Make (latest): 4.1
-   Maven located in `/usr/share/maven/`: 3.5.0
-   MySQL Client: 5.7.19
-   Node.js at `/usr/bin/nodejs`: 6.11.3
-   Npm at `/usr/bin/npm`: 3.10.10
-   Open Shift V3 CLI at `/usr/local/bin/oc`: 3.6.0
-   Python/2.7.12
-   Selenium at `/opt/selenium/selenium-server-standalone.jar`: 3.6.0
-   XVFB: 2:1.18.4