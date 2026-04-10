# 🧱 Módulo 1: Infraestrutura e Performance Sênior

Neste módulo, elevamos o nível da base do monitoramento. Um Zabbix Sênior não aceita configurações padrão (default).

## 🚀 1. Hardening do Sistema Operacional
Antes de instalar o Zabbix, preparamos o kernel do Debian 12 para suportar alta carga:
- **Limite de Arquivos:** Ajustamos o `limits.conf` para evitar o erro "Too many open files".
- **Stack TCP:** Otimizamos o `sysctl.conf` para reciclagem rápida de conexões.

## 💎 2. Engenharia de Banco de Dados (TimescaleDB)
O segredo da performance extrema:
- **Hypertables:** Divisão automática de tabelas gigantes.
- **Compression:** Redução de até 90% no espaço em disco.
- **Tuning:** Ajuste de `shared_buffers` e `work_mem`.

## 🛠️ Atividade Prática
1. Instalar Debian 12 + PostgreSQL 16.
2. Ativar a extensão TimescaleDB.
3. Aplicar a política de compressão para 7 dias.

[⬅ Voltar para o Início](../README.md) | [Módulo 2: SNMP ➡](../02-Redes-SNMP/README.md)
