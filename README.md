# はじめに
Wordpressを構築するためのPlaybookです
DBのパスワード等を変更する場合
`role/wordpress/vars/main.yml`を書き換えればOKです

## 動作環境
- Ubuntu14.04 最小構成

## 使い方
```sh
ansible-playbook -i hosts site.yml -u vagrant --ask-pass
```

# システム構成等
- WebServer : Nginx



# 今後
- WebServer,DBの冗長化を予定
