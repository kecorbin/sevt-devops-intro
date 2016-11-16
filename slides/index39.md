
# Creating an image from a Dockerfile

* Create a file called `Dockerfile` in your project directory
    ```
    FROM python:slim
    COPY . /app
    CMD python /app/hello.py
    ```
* Build an image from your Dockerfile
    ```
    docker build -t myimage .
    ```
* Start a new container using your image
    ```
    docker run myimage
    ```

