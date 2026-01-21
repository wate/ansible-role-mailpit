mailpit
=================

Setup mailpit

OS Platform
-----------------

### Debian

- trixie
- bookworm

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `mailpit_version`

インストールするmailpitのバージョン

#### `mailpit_cfg`

mailpitの設定  
@see https://mailpit.axllent.org/docs/configuration/runtime-options/

#### `mailpit_envs`

mailpitの環境変数  
@see https://mailpit.axllent.org/docs/configuration/runtime-options/

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `mailpit_user`

#### `mailpit_group`

#### `mailpit_repo`

#### `mailpit_config_dir`

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
