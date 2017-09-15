# Grafana dashboard using gnocchi/collectd

one dashboard using these collectd plugins:

- aggregation.conf
- cpu.conf
- df.conf
- disk.conf
- gnocchi.conf
- memory.conf
- processes.conf
- uptime.conf

![alt text](https://raw.githubusercontent.com/nhicher/gnocchi-collectd/master/img/dashboard.png)

Installation:

On a freshly installed centos 7.4 system, run:

    ansible-playbook -i 'localhost ansible_connection=local,'  grafana_gnocchi_collectd.yaml
