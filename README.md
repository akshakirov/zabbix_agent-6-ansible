This custom .deb package is made from bianries taken from official website https://cdn.zabbix.com/zabbix/binaries/stable/6.0/6.0.12/zabbix_agent-6.0.12-linux-3.0-amd64-static.tar.gz

The purpose of it is to populate thru Ansible to servers a new version of zabbix agent not to distrub an existing installation of Zabbix 3.4 hihi :)


You can use already build .deb or do it by yourselves

```
git clone git@github.com:akshakirov/zabbix_agent-6-custom-deb.git

dpkg-deb --build ./zabbix_agent-6.0.12-linux-3.0-amd64-static/
```

.deb package install everyting to /opt/zabbix/
