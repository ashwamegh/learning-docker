# Learning Docker

## Docker Terminologies:

### Images: 
> The blueprints of our application which form the basis of containers.

### Containers:
> Created from Docker images and run the actual application. We create a container using docker run using the image that we download. A list of running containers can be seen using the `docker ps` command.

### Docker Daemon:
> The background service running on the host that manages building, running and distributing Docker containers. The daemon is the process that runs in the operating system to which clients talk to.

### Docker Client:
> The command line tool that allows the user to interact with the daemon. More generally, there can be other forms of clients too - such as Kitematic which provide a GUI to the users.

### Docker Hub:
> A registry of Docker images. You can think of the registry as a directory of all available Docker images. If required, one can host their own Docker registries and can use them for pulling images.


## Docker Compose Terminologies:

### Docker Machine:
> Create Docker hosts on your computer, on cloud providers, and inside your own data center.

### Docker Compose:
> A tool for defining and running multi-container Docker applications.

### Docker Swarm:
> A native clustering solution for Docker.


## Docker Compose

- Compose is a tool that is used for defining and running multi-container Docker apps in an easy way. It provides a configuration file called `docker-compose.yml` that can be used to bring up an application and the suite of services it depends on with just one command.

