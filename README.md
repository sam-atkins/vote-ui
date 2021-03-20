# Vote App UI

The source code is taken (with some small modifications) from the Docker Samples repo which you can find [here](https://github.com/dockersamples/example-voting-app).

CodeBuild spec builds and publishes a tagged Docker image to AWS Elastic Container Registry.

## Local Docker commands

```bash
# build
$ docker build -t vote-ui .

# run using local image
$ docker run -p 8080:8080 -it vote-ui
```
