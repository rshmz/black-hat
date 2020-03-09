# usage

### proxy, ftp
```
# FTP簡易サーバ起動
$ python ftp.py

# proxyサーバー起動
$ sudo python proxy.py 127.0.0.1 21 127.0.0.1 8080 21 True

# cyberduckなどでproxyを経由しftpサーバにファイルアップロード
```

### paramiko
ローカルにVM立てたりする必要がある