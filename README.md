# xbps_packages
Collection of Void Linux style XBPS packages assembled for KLV 


<img width="888" height="40" alt="split" src="https://github.com/sofijacom/sofijacom/blob/main/icons_line/split.png" />


## ❯ _example for loading a package_


```
wget -c https://github.com/sofijacom/xbps_packages/raw/refs/heads/main/Conky_toggle_switch-1.0_1.noarch.xbps
```

## You can add these packages to the xbps repository 

```
echo repository=https://github.com/sofijacom/xbps_packages/raw/refs/heads/main/ | sudo tee /etc/xbps.d/packages-void.conf
```

_Then you need to refresh your repositories and accept the repository's fingerprint:_ ( Y )

```
sudo xbps-install -S
```
