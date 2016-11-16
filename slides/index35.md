
## Containers are ephemeral (cont)

Start another container using the same image
```
docker run -it python:slim /bin/sh

```

Check for the file we created
```
ls /myfile.txt
```

