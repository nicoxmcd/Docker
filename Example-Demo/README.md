# Example-Demo
To build the docker container navigate to the folder containing `Dockerfile` and run the build command:
```
cd Example-Demo
docker build .
```
![Output]()

We can then run a docker image using the newly created container using the container id (following `writing image sha256:`):
```
docker run -p 3000:3000 [container-id]
```

Then open your web browser to `localhost:3000`:
