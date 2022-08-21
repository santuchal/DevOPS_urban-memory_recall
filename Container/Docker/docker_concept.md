# Docker

Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers.

A container is a standard unit of software that packages up code and all its dependencies so the application runs quickly and reliably from one computing environment to another. 

A Docker container image is a lightweight, standalone, executable package of software that includes everything needed to run an application: code, runtime, system tools, system libraries and settings.


- Why DOCKER?

    - An application is working fine on developer console but not in testing or in production.

    - In Dev there can be a software which is updated but in testing and production an older version is being used.

    - Docker is a computer program/tool that makes it easier to deploy and run applications using a concept known as “containerization”.

    - Imagine as a developer your application is packaged up with all of the parts it needs, such as libraries and other dependencies, and it is shipped out as one package

    - Docker in other words is a light weight virtualization tool and containerizing platform where you can run and deploy applications and its dependencies which can be run in a Linux environment.

    - Docker is an open-source project based on Linux containers. It uses Linux Kernel features like namespaces and control groups to create containers on top of an operating system.

- Docker Engine

    - Docker engine is the layer on which Docker runs. It’s a lightweight runtime and tooling that manages containers, images, builds, and more. It runs natively on Linux systems and is made up of:
      - 1. A Docker Daemon that runs in the host computer.
      - 2. A Docker Client that then communicates with the Docker Daemon to execute commands.
      - 3. A REST API for interacting with the Docker Daemon remotely.

- Docker Client

    - The Docker Client is what you, as the end-user of Docker, communicate with. Think of it as the UI for Docker. 

- Docker Daemon

    - The Docker daemon is what actually executes commands sent to the Docker Client — like building, running, and distributing your containers. The Docker Daemon runs on the host machine, but as a user, you never communicate directly with the Daemon. The Docker Client can run on the host machine as well, but it’s not required to. It can run on a different machine and communicate with the Docker Daemon that’s running on the host machine.

- Volumes

    - Volumes are the “data” part of a container, initialized when a container is created. Volumes allow you to persist and share a container’s data. Data volumes are separate from the default Union File System and exist as normal directories and files on the host filesystem. So, even if you destroy, update, or rebuild your container, the data volumes will remain untouched. When you want to update a volume, you make changes to it directly. (As an added bonus, data volumes can be shared and reused among multiple containers, which is pretty neat.)

