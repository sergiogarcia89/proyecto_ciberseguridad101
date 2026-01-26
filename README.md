
# 🔐 Auditoría de Seguridad Web – WebGoat 8.1.0

Proyecto práctico de **auditoría de seguridad web básica** realizado como parte del módulo **Introducción a la Ciberseguridad**.

## 📌 Objetivo

Realizar una auditoría de seguridad sobre una aplicación web vulnerable (**WebGoat 8.1.0**) aplicando:

- Técnicas de **Information Gathering**
- Explotación de vulnerabilidades del **OWASP Top 10**
- Uso de herramientas como **Nmap, Burp Suite y SQLMap**
- Elaboración de un **informe de auditoría profesional**

---

## 🧪 Entorno de Pruebas

| Elemento | Descripción |
|---------|-------------|
| Aplicación | WebGoat 8.1.0 |
| Entorno | Local con Docker |
| Sistema | Linux (contenedor) |
| Puerto | 8080 |

### ▶️ Despliegue con Docker

```bash
docker run --name webgoat -it -p 127.0.0.1:8080:8080 -p 127.0.0.1:9090:9090 -e TZ=Europe/Amsterdam webgoat/webgoat
docker start webgoat

