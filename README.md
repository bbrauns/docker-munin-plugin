# Munin plugin for docker container stats
Creates statistics for:
- cpu
- memory
- network io read
- network io write
- blkio read
- blkio write

# Installation
- Copy file to /etc/munin/plugins
- chmod 0755 /etc/munin/plugins/docker_multigraph
- Create config file:

```
root@host:~# cat /etc/munin/plugin-conf.d/docker.conf
[docker_*]
user root
```