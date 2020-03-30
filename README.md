# parcels-jupyter-cyversevice

Jupyter Notebook server set up with [parcels](http://oceanparcels.org/) based on a Cyverse flavor of [jupyterlab-base](https://github.com/cyverse-vice/jupyterlab-base) setup. 

This repo is the base for the [chrishah/parcels-jupyter-cyversevice](https://hub.docker.com/repository/docker/chrishah/parcels-jupyter-cyversevice) image on Dockerhub.

To run the container locally (tested on Ubuntu 16.04 and 18.04):

```bash
docker run -it --rm -v $(pwd):/app -w /app -p 8888:8888 -e REDIRECT_URL=http://localhost:8888 chrishah/parcels-jupyter-cyversevice:2.0.0beta2
```

Then go to `http://localhost:8888` in your browser and this should be it.


