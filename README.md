[![Infinity Refactoring](https://goo.gl/8YUdB6)](https://infinityrefactoring.com)

# Docker Angular CLI

[![dockeri.co](http://dockeri.co/image/infinityrefactoring/angular-cli)](https://hub.docker.com/r/infinityrefactoring/angular-cli)

[![GitHub issues](https://img.shields.io/github/issues/InfinityRefactoring/docker-angular-cli.svg)](https://github.com/InfinityRefactoring/docker-angular-cli)
[![GitHub stars](https://img.shields.io/github/stars/InfinityRefactoring/docker-angular-cli.svg)](https://github.com/InfinityRefactoring/docker-angular-cli)
[![Docker Automated Build](https://img.shields.io/docker/automated/infinityrefactoring/angular-cli.svg)](https://hub.docker.com/r/infinityrefactoring/angular-cli/builds)
[![Docker Build Status](https://img.shields.io/docker/build/infinityrefactoring/angular-cli.svg)](https://hub.docker.com/r/infinityrefactoring/angular-cli/builds)

## What is it?

An Docker image to work on Angular projects with Angular CLI.

## Using Docker Angular CLI

### Use example:

```
docker run -ti --rm -p 4200:4200 -v $HOME/angular:/home/node/app infinityrefactoring/angular-cli
```

Creating a new project
```
ng new hello-world
cd cd hello-world/
```

Executing the project
```
ng serve --host 0.0.0.0
```
### Building this image:

```
docker build -t infinityrefactoring/angular-cli:latest --build-arg NODE_VERSION=latest --build-arg ANGULAR_CLI_VERSION=latest .
```

## Licensing

**InfinityRefactoring/docker-angular-cli** is provided and distributed under the [Apache Software License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

Refer to *LICENSE* for more information.
