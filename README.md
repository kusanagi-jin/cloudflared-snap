# cloudflared

```sh
snapcraft
snap install ./cloudflared_0.1_arm64.snap --dangerous
sudo cp ~/.cloudflared/cert.pem /var/snap/cloudflared/common
sudo vi /var/snap/cloudflared/common/config.yml
snap start cloudflared.tunnel

systemctl status snap.cloudflared.tunnel.service
```
