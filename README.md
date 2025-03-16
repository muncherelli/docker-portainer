For use with a single master node, deploy swarm-single-cloudflared.yml

Create Cloudflare Overlay Network
``` bash
docker network create --driver overlay --attachable cloudflare-net
```

``` bash
docker stack deploy -c swarm-single-cloudflared.yml portainer
```
