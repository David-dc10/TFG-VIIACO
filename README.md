# TFG-VIIACO
TFG-VIIACO-E-Commerce-DockerXAWS
# 🛒 VIIACO — Tienda Online Contenerizada

Este proyecto despliega una tienda online completamente funcional utilizando Docker y Docker Compose. Incluye autenticación LDAP, monitorización con Zabbix y acceso vía HTTPS.

## 📦 Tecnologías principales

- Docker 26.1.3
- Docker Compose 2.35.1
- PHP 8.2 + Apache
- MariaDB
- OpenLDAP
- Zabbix Server + Agent
- Nginx (proxy inverso + HTTPS)
- AWS + DuckDNS

## 🚀 Despliegue rápido

```bash
git clone https://github.com/David-dc10/viiaco.git
cd viiaco
docker compose build
docker compose up -d
