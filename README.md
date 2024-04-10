# docker-examples

This repository contains several folders with example `Dockerfile`s for the ENG2 module.

To build and run one of the images, run a command like this:

```bash
cd 01-hello
docker build . -t hello
docker run --rm hello
```

The repository includes a Github Actions workflow for automatically building these images and pushing them to the Github Container Registry.
