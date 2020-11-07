# example-nginx

An example app using the base-nginx image.

```bash
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
docker build -t badsyntax/example-nginx .
docker run --publish 8000:80 --name example-nginx badsyntax/example-nginx
```

Visit http://localhost:8000/
