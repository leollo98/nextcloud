Change default installation directory for [NextCloud VM](https://github.com/nextcloud/vm) from:
```
/mnt/ncdata
```
to
```
/mnt/Vault/ncdata
```
So is possible to use a shared folder and mount it on `/mnt/Vault`

Comands:
```
wget https://raw.githubusercontent.com/leollo98/nextcloud/main/nextcloud_install_production.sh
chmod +x nextcloud_install_production.sh
./nextcloud_install_production.sh
```
