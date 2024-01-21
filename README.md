mailpit
=================

Setup mailpit

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `mailpit_version`

インストールするmailpitのバージョン

### `mailpit_cfg`

mailpitのポート設定

### `mailpit_envs`

mailpitのその他の環境変数

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: mailpit
```

License
--------------

Apache License 2.0
