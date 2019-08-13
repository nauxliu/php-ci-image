# PHP CI Docker images

[![Build Status](https://wdp9fww0r9.execute-api.us-west-2.amazonaws.com/production/badge/nauxliu/php-ci-image)](https://wdp9fww0r9.execute-api.us-west-2.amazonaws.com/production/results/nauxliu/php-ci-image) 

This repository is based on the [official PHP Docker images](https://hub.docker.com/_/php) with the following additions:

* git
* composer
* unzip

### Build schedule

Every day

### Usage

Use `docker pull nauxliu/php-ci-image` to pull these images.

The following tags are available:

* 7.0
* 7.1
* 7.2
* 7.3
* 7.4.0beta2