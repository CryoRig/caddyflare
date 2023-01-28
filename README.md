# caddyflare
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/CryoRig/caddyflare/.github/workflows/auto-build-on-base-image-change.yml?style=flat-square&logo=githubactions)
![Docker Pulls](https://img.shields.io/docker/pulls/cryorig/caddyflare?style=flat-square&logo=docker)

This Repository adds the [Cloudflare DNS Module](https://github.com/caddy-dns/cloudflare) to the official [caddy V2](https://github.com/caddyserver/caddy) Image.  

It automatically rebuilds once per Week (Friday Night UTC), **IF** the [Caddy](https://hub.docker.com/_/caddy) image was updated, and pushes it to this [Docker Repository](https://hub.docker.com/r/cryorig/caddyflare).  

# No warranty no anything... You know how this works
Use at your own risk...  
**IF** something breaks i will try to fix it, but no guarantees.  
As always, check what you download from the internet before you use it ;)
