---
title: Learn how to use Docker

description: Build, share, and run for multi-architecture use cases.

minutes_to_complete: 30

who_is_this_for: This is an introductory topic for software developers who want to learn about Docker for the Arm architecture.

learning_objectives:
    -  Build, run, and share Docker images
    -  Perform multi-architecture builds using Docker buildx
    -  Use a remote server to build a Docker image for the Arm architecture
    -  Use Docker manifest for multi-architecture builds

prerequisites:
    - A Windows, macOS, or Linux computer with Docker installed, any architecture can be used
    - An Arm Linux server with Docker installed 

author: Jason Andrews

### Tags
skilllevels: Introductory
subjects: Containers and Virtualization
armips:
    - Neoverse
    - Cortex-A
operatingsystems:
    - Linux
tools_software_languages:
    - Docker

### Cross-platform metadata only
shared_path: true
shared_between:
    - servers-and-cloud-computing
    - laptops-and-desktops
    - embedded-and-microcontrollers
    - iot

further_reading:
    - resource:
        title: Docker Documentation
        link: https://docs.docker.com
        type: documentation
    - resource:
        title: Docker buildx documentation
        link: https://docs.docker.com/engine/reference/commandline/buildx
        type: documentation
    - resource:
        title: Docker mainfest documentation
        link: https://docs.docker.com/engine/reference/commandline/manifest
        type: documentation
    - resource:
        title: Blog by Docker on buildx
        link: https://www.docker.com/blog/how-to-rapidly-build-multi-architecture-images-with-buildx
        type: blog


### FIXED, DO NOT MODIFY
# ================================================================================
weight: 1                       # _index.md always has weight of 1 to order correctly
layout: "learningpathall"       # All files under learning paths have this same wrapper
learning_path_main_page: "yes"  # This should be surfaced when looking for related content. Only set for _index.md of learning path content.
---
