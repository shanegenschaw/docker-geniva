# docker-geniva

## Running locally

```bash
# pull latest
docker pull genschsa/docker-geniva

# or build local
docker build . --file Dockerfile --tag genschsa/docker-geniva

# run
docker run -d --name geniva -p 8081:80 genschsa/docker-geniva 

curl http://localhost:8081
```
