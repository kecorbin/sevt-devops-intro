

## Creating an image from an existing container

* Start a new container from the image
    ```
    docker run -it python:slim /bin/sh

    ```
* Create a new file
    ```
    touch /myfile.txt
    ```

* Exit the container
    ```
    exit
    ```
* Get the container id from the `docker ps -a` command

```
CONTAINER ID        IMAGE                 COMMAND                  CREATED             STATUS                           PORTS                    NAMES
ee3d5d30a555        python:slim           "/bin/sh"                11 seconds ago      Exited (0) 3 seconds ago
```

