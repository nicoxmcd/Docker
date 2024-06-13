# Example-Demo
To build the docker container navigate to the folder containing `Dockerfile` and run the build command:
```
cd Example-Demo
docker build .
```
![build output](https://github.com/nicomcd/Docker/assets/35404943/17bfa122-338d-4a68-8480-3aaa8f2ffe38)
![docker desktop](https://github.com/nicomcd/Docker/assets/35404943/a17c9fe9-6c14-4ba9-a4f3-934df56e405f)

We can then run a docker image using the newly created container using the container id (following `writing image sha256:`). We are using the `-p` flag to indicate we want to publish port 3000 onto port 3000 because this example utilizes that port:
```
docker run -p 3000:3000 [container-id]
```
Then open your web browser to `localhost:3000`:
![localhost:3000](https://github.com/nicomcd/Docker/assets/35404943/fde12520-c17c-4e14-b788-b4c832c18515)
