---
aliases:
  - /userguide/
description: Introduction to user guide
identifier: engine_guide_intro
keywords:
- docker, introduction, documentation, about, technology, docker.io, user, guide, user's, manual, platform, framework, home,  intro
title: Engine user guide
---

This guide takes you through the fundamentals of using Docker Engine and
integrating it into your environment. You'll learn how to use Engine to:

* Dockerize your applications.
* Run your own containers.
* Build Docker images.
* Share your Docker images with others.
* And a whole lot more!

This guide is broken into major sections that take you through learning the basics of Docker Engine and the other Docker products that support it.

## Dockerizing applications: A "Hello world"

*How do I run applications inside containers?*

Docker Engine offers a containerization platform to power your applications. To
learn how to Dockerize applications and run them:

Go to [Dockerizing Applications](../tutorials/dockerizing.md).


## Working with containers

*How do I manage my containers?*

Once you get a grip on running your applications in Docker containers, you'll learn how to manage those containers. To find out
about how to inspect, monitor and manage containers:

Go to [Working with Containers](../tutorials/usingdocker.md).

## Working with Docker images

*How can I access, share and build my own images?*

Once you've learnt how to use Docker it's time to take the next step and
learn how to build your own application images with Docker.

Go to [Working with Docker Images](../tutorials/dockerimages.md).

## Networking containers

Until now we've seen how to build individual applications inside Docker
containers. Now learn how to build whole application stacks with Docker
networking.

Go to [Networking Containers](../tutorials/networkingcontainers.md).

## Managing data in containers

Now we know how to link Docker containers together the next step is
learning how to manage data, volumes and mounts inside our containers.

Go to [Managing Data in Containers](../tutorials/dockervolumes.md).

## Managing metadata (labels) for Docker objects

Labels are a mechanism for applying metadata to Docker objects, including:

- Images
- Containers
- Local daemons
- Volumes
- Networks
- Swarm nodes
- Swarm services


You can use labels to organize your images, record licensing information, annotate
relationships between containers, volumes, and networks, or in any way that makes
sense for your business or application.

Go to [Managing Docker object labels](labels-custom-metadata.md).

## Docker products that complement Engine

Often, one powerful technology spawns many other inventions that make that easier to get to, easier to use, and more powerful.  These spawned things share one common characteristic: they augment the central technology. The following Docker products expand on the core Docker Engine functions.

### Docker Hub

Docker Hub is the central hub for Docker. It hosts public Docker images
and provides services to help you build and manage your Docker
environment. To learn more:

Go to [Using Docker Hub](/docker-hub/).

### Docker Machine

Docker Machine helps you get Docker Engines up and running quickly. Machine
can set up hosts for Docker Engines on your computer, on cloud providers,
and/or in your data center, and then configure your Docker client to securely
talk to them.

Go to [Docker Machine user guide](/machine/).

### Docker Compose

Docker Compose allows you to define an application's components -- their containers,
configuration, links and volumes -- in a single file. Then a single command
will set everything up and start your application running.

Go to [Docker Compose user guide](/compose/).


### Docker Swarm

Docker Swarm pools several Docker Engines together and exposes them as a single
virtual Docker Engine. It serves the standard Docker API, so any tool that already
works with Docker can now transparently scale up to multiple hosts.

Go to [Docker Swarm user guide](/swarm/).

## Getting help

* [Docker homepage](https://www.docker.com/)
* [Docker Hub](https://hub.docker.com)
* [Docker blog](https://blog.docker.com/)
* [Docker documentation](/)
* [Docker Getting Started Guide](../getstarted/index.md)
* [Docker code on GitHub](https://github.com/docker/docker)
* [Docker mailing
  list](https://groups.google.com/forum/#!forum/docker-user)
* Docker on IRC: irc.freenode.net and channel #docker
* [Docker on Twitter](https://twitter.com/docker)
* Get [Docker help](https://stackoverflow.com/search?q=docker) on
  StackOverflow
