# tools
## ss
### 5秒おきにスクリーンショットをとるcron
```
# homeに移動
$ cd

# ssディレクトリ作成
$ mkdir ss

# ssディレクトリに移動
$ cd ss

# このリポジトリからソースの取得
$ git clone https://github.com/Daiki0525/tools.git

# ファイル移動
$ mv ./tools/capture.sh ./

# 実行権限を付与
$ chmod +x capture.sh
```

```
$ crontab -e

* * * * * ~/ss/capture.sh

# 1分くらいしたら確認
$ ls ~/ss/ 
```
