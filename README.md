varnish Role
=========


Role Variables
--------------

```
varnish_enabled: false

varnish_custom_config:
  http_resp_hdr_len: 32k
  http_resp_size: 32k

varnish_start_at_boot: "yes"
varnish_max_files_open: 131072
varnish_max_locked_memory: 82000

varnish_listen_port: false
varnish_forward_port: 8080
varnish_forward_host: 127.0.0.1
```

----------------

```
#   requirements.yml
#
#   Example
# - src: https://github.com/ergontech-ansible-roles/varnish
#   version: master
#   name: varnish
```

License
-------

[MIT](LICENSE)