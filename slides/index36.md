
## Containers are ephemeral

Explore the following commands

Start a new container

```
docker run -it python:slim /bin/sh

```

Create a new file

```
touch /myfile.txt
```

Verify the file was created
```
ls /myfile.txt
```

Exit the container

```
exit

```

