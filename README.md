# cloudflared

```sh
sudo classic
git clone https://github.com/kusanagi-jin/cloudflared-snap.git
cd cloudflared-snap
snapcraft
snap install ./cloudflared_0.1_arm64.snap --dangerous
sudo vi $HOME/.cloudflared/config.yml
snap start cloudflared.tunnel

systemctl status snap.cloudflared.tunnel.service
```
