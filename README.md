# Simple letsencrypt `docker-compose` sample

Sample `docker-compose.yml` that shows how to use letsencrypt-nginx-proxy-companion.

This docker-compose.yml starts up a `web` instance backed by a `api` container.

**MUST** update the following variables:
`VIRTUAL_HOST`,`VIRTUAL_PORT`,
`LETSENCRYPT_HOST`,  in order for SSL to work.

You can set a default email using `DEFAULT_EMAIL`
 or `LETSENCRYPT_EMAIL` in containers

See [letsencrypt-nginx-proxy-companion](https://github.com/nginx-proxy/docker-letsencrypt-nginx-proxy-companion) for more info.
