# k8s-circleci

[![CircleCI](https://circleci.com/gh/punya-asapp/k8s-circleci.svg?style=svg)](https://circleci.com/gh/punya-asapp/k8s-circleci)

Demo of running component-level tests using:
* [CircleCI Docker executor](https://circleci.com/docs/2.0/executor-types/#using-docker) to run Docker under CircleCI
* [K3d](https://github.com/rancher/k3d) to run Kubernetes under Docker
* [Twirp](https://twitchtv.github.io/twirp/) to create strongly-typed RPC APIs
* [Newman](https://github.com/postmanlabs/newman) to run integration tests

See `.circleci/config.yml` for more details.
