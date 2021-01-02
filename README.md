# MyRedmine
個人用RedmineのDockerFile管理用。

※markdown使用設定にした際に画像サイズ指定できるようにするカスタマイズを追加。

### 起動
```sh
docker-compose up -d
```

### コンテナに入る
```sh
docker-compose ps  # Nameを調べて下記コマンドで指定
docker exec -it myredmine_redmine_1 /bin/bash
```

### 終了
```sh
docker-compose down
```


### 参考記事
https://qiita.com/yuda1k/items/651ba6207938789d0c2d

https://sayahamitt.net/redmine%E3%81%AEmarkdown%E3%81%A7%E7%94%BB%E5%83%8F%E3%82%B5%E3%82%A4%E3%82%BA%E3%82%92%E6%8C%87%E5%AE%9A%E3%81%A7%E3%81%8D%E3%82%8B%E3%82%88%E3%81%86%E3%81%AB/