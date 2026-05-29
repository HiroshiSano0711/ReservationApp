# YouTube用アプリ

## DBの設定

roleを作成

作成したroleで接続

```
$ psql -U reservation_app -d reservation_app_development
```

role単位でタイムゾーンをUTCに設定する。
```
ALTER ROLE reservation_system SET timezone TO 'UTC';
```

一旦セッションを終了し、もう一度接続し直して

```
SHOW timezone;
```

を打ち、UTCと表示されればOK。