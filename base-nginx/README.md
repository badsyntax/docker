# base-nginx

A base nginx docker image with optimised h5bp nginx config I use for static file & app hosting.

Pushing image:

```bash
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
docker build -t ghcr.io/badsyntax/base-nginx:latest .
docker run --publish 8000:80 ghcr.io/badsyntax/base-nginx:latest
docker push ghcr.io/badsyntax/base-nginx:latest
```
