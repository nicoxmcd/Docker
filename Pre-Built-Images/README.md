# Running Pre-Built Images From Docker Hub
You can find Docker official images from [here](https://hub.docker.com/search?image_filter=official). You can run the base image, which holds all the logic and code that the container needs, as a container by doing this command and replacing python with whatever image you want to use from docker hub:
```
docker run python
```
![docker run python](https://github.com/nicomcd/Docker/assets/35404943/5c7712ff-bc56-4e5a-832a-8fae599d71a6)
We can double check the history of all (`-a`) processes or images (`p`) by doing the following command:
```
docker ps -a
```
![docker ps -a](https://github.com/nicomcd/Docker/assets/35404943/7a107208-3dc3-4a02-94b2-22e7baf287ff)
The interface of the python image is not automatically exposed to us by the container. To expose the interactive session to our host machine we have to add the `-it` flag to the command:
```
docker run -it python
```
![docker run -it python](https://github.com/nicomcd/Docker/assets/35404943/5abe5b56-bf18-4529-b59e-d96baf14a09b)
Exit the container with `Ctrl+C` or `exit()` and for example, we can prove that this container is not from our local machine by checking the version of Python locally versus what version was running in the container. This is the version of python running locally on my machine:
![Local](https://github.com/nicomcd/Docker/assets/35404943/8f4066c1-476d-4f6e-b9ba-c3e2bcb7967d)
