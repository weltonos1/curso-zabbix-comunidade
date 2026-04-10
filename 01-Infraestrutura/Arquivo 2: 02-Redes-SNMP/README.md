# 📡 Módulo 2: Engenharia de Redes e Coleta Avançada

Monitorar redes não é apenas dar "ping". É entender a saúde de cada interface e a segurança do tráfego.

## 🔒 1. Segurança com SNMP v3
Abordamos a configuração de **AuthPriv**:
- **Autenticação:** SHA.
- **Privacidade (Criptografia):** AES.
- Por que abandonar o SNMP v2c em ambientes críticos?

## 🪄 2. Automação com LLD (Low Level Discovery)
- Criação de Protótipos de Itens.
- Uso de **Expressões Regulares (RegEx)** para filtrar o que deve ser monitorado.
- Monitoramento de erros de CRC e descartes em interfaces.

## 🛠️ Atividade Prática
1. Configurar um dispositivo com SNMP v3.
2. Criar um LLD que descubra apenas portas de "Uplink".
3. Validar a coleta via `snmpget` no terminal do Zabbix Server.

[⬅ Módulo 1](../01-Infraestrutura/README.md) | [Módulo 3: Dashboards ➡](../03-Dashboards-SLA/README.md)
