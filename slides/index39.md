
## Creating an image from an existing container(cont)

* Create a new image using `docker commit`

```
docker commit ee3d5d30a555 myimage
```

* Verify the image shows up in `docker images`
* Start another container with the following command
```
docker run -it myimage /bin/sh
```
* Verify the file is present the new container
```
ls /myfile.txt
```

