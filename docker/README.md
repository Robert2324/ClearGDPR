<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [Docker Configuration](#docker-configuration)
  - [Entry points](#entry-points)
  - [Directory `definitions`](#directory-definitions)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Docker Configuration

This project is based on Docker/Docker-Compose for local development.

### Entry points

Scripts `docker/run` are meant to be called directly during local development from the root directory.

### Directory `definitions`

Contains Dockerfiles and accessory file for Docker images that are not built by us at ClearGDPR

* `postgres` is used during local development. Databases for server environments are usually not on Docker.
