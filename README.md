# Installation
- Copy file to /etc/munin/plugins
- chmod 0755 /etc/munin/plugins/docker_multigraph
- Create config file:

```
root@host:~# cat /etc/munin/plugin-conf.d/docker.conf
[docker_*]
user root
```