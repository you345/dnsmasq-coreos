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
