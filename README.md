# 🛡️ LandingSIGCRM

Este proyecto forma parte de la integración del sistema de seguros con el CRM (Customer Relationship Management), brindando una experiencia centralizada para la consulta de siniestros, descarga de pólizas y visualización de datos relacionados con vehículos asegurados.

## 🚀 Objetivo

Desarrollar una **landing page dinámica** que sirva como interfaz de consulta para los usuarios finales (colaboradores o clientes), utilizando integraciones con APIs internas de la organización.

## 🧩 Características

- 🔍 Consulta de siniestros por número de motor, VIN o placa.
- 📄 Descarga de póliza en formato PDF.
- 🎨 Interfaz minimalista y responsiva, adaptada a dispositivos móviles.
- 🔐 Integración segura con middleware de autenticación.
- 💡 Modular y fácilmente escalable.

## ⚙️ Tecnologías

- HTML5 + CSS3 + JavaScript
- Power Automate (para consumir servicios API)
- Middleware en .NET Core (intermediario entre API y CRM)
- Hosting en entorno corporativo

## 📂 Estructura del Proyecto

Seguros-SIG-CRM/ ├── public/ # Archivos estáticos │ └── index.html # Landing principal ├── styles/ # Archivos CSS ├── scripts/ # Lógica frontend ├── README.md 

##🔐 Seguridad
El proyecto está preparado para operar en entornos internos con IPs restringidas y autenticación mediante token JWT, gestionado desde un middleware personalizado en ASP.NET Core.

📚 Fuentes
Documentación oficial de Power Platform

Arquitectura del API de siniestros interna

Lineamientos de branding institucional
