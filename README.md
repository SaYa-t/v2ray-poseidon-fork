# Poseidon -- An Enhanced V2Ray(based on v2ray-core)

### Features

- Sync user from your panel to v2ray
- Log user traffic
- Limit traffic rate ( speed limit )
- Limit online IP count
- And other optimizations

### Benefits

- No other requirements
  - It's  able to run if you could launch v2ray core
- Less memory usage
  - It just takes about 5MB to 10MB memories more than v2ray core
  - Small RAM VPS would be joyful
- Simplicity configuration


### Install on Linux

```
curl -o go.sh -L -s https://raw.githubusercontent.com/Fate2077/v2ray-poseidon-fork/master/install-release.sh
sudo bash go.sh # Install latest version of v2ray-poseidon
OR
sudo bash go.sh --version v1.5.3 # Install target version of v2ray-poseidon

firewall-cmd --zone=public --add-port=443/tcp --permanent
firewall-cmd --reload
systemctl enable v2ray
service v2ray restart
sudo journalctl -u v2ray -f
```

#### Uninstall

```
curl -L -s https://raw.githubusercontent.com/Fate2077/v2ray-poseidon-fork/master/uninstall.sh | sudo bash
```
### config
/etc/v2ray/config.json

### Contact

Get in touch via [TG group: v2ray_poseidon](https://t.me/v2ray_poseidon)

### Acknowledgement

- [V2ray](https://github.com/v2ray/v2ray-core)
- [SSRPanel](https://github.com/ssrpanel/SSRPanel)
- [V2board](https://github.com/v2board/v2board)
- [SSPanel-v3-Uim](https://github.com/Anankke/SSPanel-Uim)
