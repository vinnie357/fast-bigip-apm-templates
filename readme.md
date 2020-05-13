# fast-bigip-apm
bigip APM policy templates for FAST

# Introduction

These templates are meant to be used with the f5-fast-framework, and a service
can be stood up simply, using
[fast-docker](https://github.com/zinkem5/fast-docker).

# Quickstart

Clone this repo, and the fast-docker repo.

Start the fast-docker container with the following template:

```
fast render fast-run.yaml | sh
```

```bash
#example
docker run --name fastdock -p 3000:3000 -v $PWD/templates:/var/config/templates fastdock fast render fast-run.yaml | sh
```