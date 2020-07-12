# cloudflared

```sh
snapcraft
snap install ./cloudflared_0.1_arm64.snap --dangerous
sudo cp ~/.cloudflared/cert.pem /var/snap/cloudflared/common
# write config file in the common dir
snap start cloudflared.tunnel

systemctl status snap.cloudflared.tunnel.service
```
