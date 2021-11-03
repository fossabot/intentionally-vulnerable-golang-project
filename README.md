# Intentionally vulnerable Golang project

[![Build Status](https://travis-ci.org/sonatype-nexus-community/intentionally-vulnerable-golang-project.svg?branch=master)](https://travis-ci.org/sonatype-nexus-community/intentionally-vulnerable-golang-project) [![CircleCI](https://circleci.com/gh/sonatype-nexus-community/intentionally-vulnerable-golang-project.svg?style=shield)](https://circleci.com/gh/sonatype-nexus-community/intentionally-vulnerable-golang-project)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FWS-IB-demo%2Fintentionally-vulnerable-golang-project.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FWS-IB-demo%2Fintentionally-vulnerable-golang-project?ref=badge_shield)

This is just a minimal repo for testing Sonatype's `nancy` against an intentionally vulnerable list of 
dependencies, and as well showing a small example of how to use it in Travis-CI and CircleCI

Project is currently setup to use both `dep` and `go mod` so you should be able to use either one. 

To see how `nancy` will output when finding vulnerabilities, check out [this build on Travis-CI](https://travis-ci.org/github/sonatype-nexus-community/intentionally-vulnerable-golang-project/builds/671448888) or [this build on CircleCI](https://circleci.com/gh/sonatype-nexus-community/intentionally-vulnerable-golang-project/26)


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FWS-IB-demo%2Fintentionally-vulnerable-golang-project.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2FWS-IB-demo%2Fintentionally-vulnerable-golang-project?ref=badge_large)