# DukeCon

The DukeCon project is going to be a (Java based) Conference App (server/infrastructure + mobile App/s) for
[JavaLand](http://javaland.eu) and other conferences, e.g., 

* [Java Forum Stuttgart](http://java-forum-stuttgart.de),
* DOAG Conferences: [2017](http://2017.doag.org), and [2018](http://2018.doag.org).

This is the _umbrella project_ with general information (documentation, architecture, requirements, issue list etc.).

## Documentation / Bug reporting and requirements

**Important:** Before raising issues, please check the [Wiki](https://github.com/dukecon/dukecon/wiki) and the [Issue
Tracker](https://github.com/dukecon/dukecon/issues) for further information or known problems. There is also a list of
[current and required features](https://github.com/dukecon/dukecon/wiki/Anforderungen) (currently only in German).

_Please submit all problems to the general issue list first, we will sort out their target with the help of [Github Issue Mover](https://github-issue-mover.appspot.com/)_. Of course, you are welcome to submit new requirements as well!

## Sub projects

| Project | Purpose | Issues |
| ------- | ------- | ------ |
| [DukeCon](https://github.com/dukecon/dukecon) | Umbrella project with documentation etc. | [Issues](https://github.com/dukecon/dukecon/issues) |
| [DukeCon_Server](https://github.com/dukecon/dukecon_server) | REST services for most of Dukecon | [Server Issues](https://github.com/dukecon/dukecon_server/issues) |
| [DukeCon_PWA](https://github.com/dukecon/dukecon_pwa) | HTML/Vue.js single page frontend | [PWA Issues](https://github.com/dukecon/dukecon_pwa/issues) |
| [DukeCon_Android](https://github.com/dukecon/dukecon_android) | Native Android frontend | [Android Issues](https://github.com/dukecon/dukecon_android/issues) |
| [DukeCon_Infra](https://github.com/dukecon/dukecon_infra) | Operational runtime and CI infrastructure setup | [Infrastructure Issues](https://github.com/dukecon/dukecon_infra/issues) |
| [DukeCon_Feedback](https://github.com/dukecon/dukecon_feedback) | Optional REST services for speaker feedback | [Feedback Issues](https://github.com/dukecon/dukecon_feeback/issues) |
| [DukeCon_Resources](https://github.com/dukecon/dukecon_resources) | Functional configurations, i.e., conference configurations. | [Resources Issues](https://github.com/dukecon/dukecon_resources/issues) |
| [DukeCon_Admin](https://github.com/dukecon/dukecon_admin) | Administrative frontend | [Admin Issues](https://github.com/dukecon/dukecon_admin/issues) |
| [DukeCon_Docker_Images](https://github.com/dukecon/dukecon_docker_images) | Misc. Docker base images, e.g., for Edge services | [Docker Images Issues](https://github.com/dukecon/dukecon_docker_images/issues) |
| [DukeCon_Webhome](https://github.com/dukecon/dukecon_webhome) | DukeCon web landing page (http://dukecon.org) | [Webhome Issues](https://github.com/dukecon/dukecon_webhome/issues) |
| [DukeCon_Jenkins](https://github.com/dukecon/dukecon_jenkins) | Jenkins Seed jobs | [Jenkins Issues](https://github.com/dukecon/dukecon_jenkins/issues) |
| [DOAG User SPI](https://github.com/dukecon/doag-user-spi) | KeyCloak User Provider (allows DOAG users to login to Dukecon) | [DOAG User SPI issues](https://github.com/dukecon/doag-user-spi/issues) |
| [KeyCloak Postgres HTTPS](https://github.com/dukecon/keycloak_postgres_https) | Extended KeyCloak Docker image | [KeyCloak Postgres HTTPS issues](https://github.com/dukecon/keycloak_postgres_https/issues) |
| [InspectIT CMR](https://github.com/dukecon/inspectit_cmr) | [InspectIT CMR](http://inspectit.rocks) Docker base image | [InspectIT CMR Issues](https://github.com/dukecon/inspectit_cmr/issues) |

## Deprecated sub projects

| Project | Purpose | Issues | Reason |
| ------- | ------- | ------ | ------ |
| [DukeCon-Cordova](https://github.com/dukecon/dukecon-cordova) | Cordova wrapper of [DukeCon_HTML5](https://github.com/dukecon/dukecon_html5) (mobile for iOS and Android) | [Cordova App Issues](https://github.com/dukecon/dukecon-cordova/issues) | Replaced by [DukeCon_PWA](https://github.com/dukecon/dukecon_pwa) |
| [DukeCon_HTML5](https://github.com/dukecon/dukecon_html5) | HTML5 App (mobile + browser) | [HTML5 App Issues](https://github.com/dukecon/dukecon_html5/issues) | Replaced by [DukeCon_PWA](https://github.com/dukecon/dukecon_pwa) |
| [DukeCon_Server_Docker](https://github.com/dukecon/dukecon_server_docker) | Docker container with the server application | [DukeCon Docker Issues](https://github.com/dukecon/dukecon_server_docker/issues) | Docker build incorporated into [DukeCon_Server](https://github.com/dukecon/dukecon_server) directly |
| [DukeCon_Flex](https://github.com/dukecon/dukecon_flex) | Flex (Flash) App (mobile) | [Flex App Issues](https://github.com/dukecon/dukecon_flex/issues) | Not actively maintained any longer |
| [DukeCon_Meteor](https://github.com/dukecon/dukecon_meteor) | Meteor client + server | [DukeCon Meteor Issues](https://github.com/dukecon/dukecon_meteor/issues) | Not actively maintained any longer |
| [Multi module Maven Release Plugin (Fork)](https://github.com/dukecon/multi-module-maven-release-plugin) | Fork of the [Multi module Maven Release Plugin](https://github.com/danielflower/multi-module-maven-release-plugin) | - | Automatic releasing of DukeCon components is not used any longer |
| [InspectIT Platform Docker](https://github.com/dukecon/inspectit-platform-docker) | Fork of [InspectIT Platform Docker](https://github.com/ClaudioWaldvogel/inspectit-platform-docker)  | - |
| [Docker-Cordova](https://github.com/dukecon/docker-cordova) | Fork of [Docker-Cordova](https://github.com/oren/docker-cordova)  | - |

## Unclear status

The following projects have an unclear maintenance status (as of 2018-03-24):

* https://github.com/dukecon/dukecon_monitoring
* https://github.com/dukecon/dukecon_server_reactor
* https://github.com/dukecon/url-schema-test
* https://github.com/dukecon/android-images
