# 🛠️ Instalação Passo a Passo: Zabbix 7.0 no Debian 12

Este guia foca na instalação limpa e performática, utilizando os repositórios oficiais da Zabbix SIA.

## 1. Instalar o Repositório
```bash
wget [https://repo.zabbix.com/zabbix/7.0/debian/pool/main/z/zabbix-release/zabbix-release_7.0-1+debian12_all.deb](https://repo.zabbix.com/zabbix/7.0/debian/pool/main/z/zabbix-release/zabbix-release_7.0-1+debian12_all.deb)
dpkg -i zabbix-release_7.0-1+debian12_all.deb
apt update

apt install zabbix-server-pgsql zabbix-frontend-php php8.2-pgsql zabbix-apache-conf zabbix-sql-scripts zabbix-agent -y

