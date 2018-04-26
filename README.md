# Learning Docker

## Terminologies:

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