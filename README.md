# My website using the Minimal Mistakes theme

[![Docker Automated buil](https://img.shields.io/docker/automated/mtpatter/jekyll-minmistakes.svg)](https://hub.docker.com/r/mtpatter/jekyll-minmistakes/)

For Docker jekyll environment, from the root directory, build a Docker image:

```
docker build -t "jekyll_blog" .
```

Run the container with:

```
docker run --name jekyll -d -v ${PWD}:/srv/jekyll -p 4000:4000 jekyll_blog
```
