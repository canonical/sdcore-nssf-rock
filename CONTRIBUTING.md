# Contributing

## Build and deploy

```bash
sudo snap install rockcraft --classic --edge
rockcraft pack -v
sudo rockcraft.skopeo --insecure-policy copy oci-archive:sdcore-nssf_1.4.1_amd64.rock docker-daemon:sdcore-nssf:1.4.1
docker run sdcore-nssf:1.4.1
```