🚀 N8N – Ambiente Local con Docker

Repositorio público para levantar n8n en un ambiente local usando Docker Compose, con persistencia de datos, autenticación básica y soporte para webhooks externos mediante ngrok.

📌 Descripción

Este proyecto permite desplegar n8n de forma rápida, segura y reproducible en un entorno local utilizando Docker.

Está pensado para:

Desarrollo de flujos

Pruebas de automatización

Integraciones con APIs

Exposición temporal de webhooks

Simulación de entornos productivos

🧱 Stack Tecnológico

🐳 Docker

🐳 Docker Compose v3.8

⚙️ n8n (imagen oficial)

🌐 ngrok (para webhooks externos)

🔐 Autenticación básica HTTP

💾 Persistencia de datos local

📂 Estructura del Proyecto
N8N-DOCKER-AMBIENTE-LOCAL/
├── docker-compose.yml
├── .env
├── n8n_data/
│   └── (datos persistentes de n8n)
└── README.md



✍️ Autor

Isaac Haro
Proyecto: N8N-DOCKER-AMBIENTE-LOCAL
