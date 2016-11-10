
# So What??!

Let's use the git and docker skills we've acquired to do something a bit more useful

1. Use git to clone the following repo

    https://github.com/datacenter/reattivio

2. Change to the reattivio directory

    ```
    cd reattivio
    ```

3. Create a docker image for this project

    ```
    docker build -t reattivio .
    ```


4. Launch a container using your new image
    ```
    docker run -p 8080:80 reattivio
    ```

    The -p flag is specifying a port mapping from 8080 on your local maching to port 80 in the running container

5. Launch your browser and point to http://127.0.0.1:8080

    You can point the tool to

