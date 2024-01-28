mailpit
=================

Setup mailpit

OS Platform
-----------------

### Debian

- bookworm

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `mailpit_version`

インストールするmailpitのバージョン

### `mailpit_cfg`

mailpitの設定  
@see https://mailpit.axllent.org/docs/configuration/runtime-options/

### `mailpit_envs`

mailpitの環境変数  
@see https://mailpit.axllent.org/docs/configuration/runtime-options/

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
