
## Running a container

Launching a container based on the python:slim image

```
docker run -ti python:slim echo hello

```
This command starts a new container, runs the `echo hello` and exits

You can see a list of containers which are currently running using the following command

```
docker ps
```
Because the container we started has already exited it is not listed using this command alone, to see all
containers, add the --all flag

```
docker ps --all
```

You should see something similar to the following

```
CONTAINER ID        IMAGE                 COMMAND                  CREATED             STATUS                      PORTS                    NAMES
f8ba379a6780        python:slim                "echo hello"             2 minutes ago       Exited (0) 2 minutes ago
```

