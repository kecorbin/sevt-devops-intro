
## Running a container interactively

Now we will run the following command

```
docker run -i -t python:slim /bin/sh
```
This tells docker to start a container interactively (-i) and to allocate a tty session (-t).  These options can also
be grouped together (-it)

You now have a container running, and have an interactive shell

You can exit the container, by closing the shell using:

```
exit
```

