# cloudflared

```sh
sudo classic
git clone https://github.com/kusanagi-jin/cloudflared-snap.git
cd cloudflared-snap
snapcraft
# snapcraft clean cloudflared -s build
# snapcraft clean cloudflared -s pull
snap install ./cloudflared_0.1_arm64.snap --dangerous
sudo vi $HOME/.cloudflared/config.yml
snap connect cloudflared:config-cloudflared
snap start cloudflared.tunnel

systemctl status snap.cloudflared.tunnel.service
sudo journalctl -u snap.cloudflared.tunnel.service
```
