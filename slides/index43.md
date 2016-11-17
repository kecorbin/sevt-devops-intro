## So What??! (cont)


4. Launch a container using your new image
    ```
    docker run -p 8080:80 reattivio
    ```

    The -p flag is specifying a port mapping from 8080 on your local maching to port 80 in the running container

5. Launch your browser and point to http://127.0.0.1:8080

    You can point the tool to your lab APIC controller if you have one avaiable, if not you can use the DevNet Sandbox by using the following:

 * Address: sandboxapicdc.cisco.com
 * Username: admin
 * Password: 1vtG@lw@y
 * Use HTTPS

