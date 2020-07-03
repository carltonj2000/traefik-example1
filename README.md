# Traefik Example 1

The code in this example is based on the following documents.

- [Traefix Quick Start](https://docs.traefik.io/getting-started/quick-start/)
- [Traefik 2.0 & Docker 101](https://containo.us/blog/traefik-2-0-docker-101-fc2893944b9d/)

```bash title="docker stack"
docker stack deploy --compose-file stack.yml reverse-proxy
curl -H Host:whoami.docker.localhost http://127.0.0.1
```
