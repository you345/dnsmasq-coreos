# dnsmasq-coreos

https://qiita.com/abeshi01/items/1fb0226568d98de86e83

```
Settings/Developer Settings -> ここで、パーソナルトークンの発行がgit push時に必要
```

```
たまにファイル更新のため実行が必要
curl -s https://warui.intaa.net/adhosts/hosts.txt | sed -E "s/(0.0.0.0) (.*)$/address=\/\2\/\1/" > ./dnsmasq.d/adblock.conf
```

```
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
```

```
sudo docker-compose up -d
```

```
[admin@CoreOS dnsmasq-coreos]$ sudo systemctl disable systemd-resolved
Removed "/etc/systemd/system/dbus-org.freedesktop.resolve1.service".
Removed "/etc/systemd/system/sysinit.target.wants/systemd-resolved.service".
[admin@CoreOS dnsmasq-coreos]$
[admin@CoreOS dnsmasq-coreos]$ sudo systemctl stop systemd-resolved
[admin@CoreOS dnsmasq-coreos]$
[admin@CoreOS dnsmasq-coreos]$ docker-compose up
```
