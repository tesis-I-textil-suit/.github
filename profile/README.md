# 🧵 Textil Trazabilidad - IoT NFC 🌐

Bienvenidos a la organización **Textil Trazabilidad**, un proyecto enfocado en la gestión y trazabilidad de avíos en la industria textil utilizando tecnologías IoT, NFC y MQTT.

## 🚀 Objetivo del Proyecto
Facilitar la gestión y seguimiento de avíos (hilos, botones, cierres) entre almacenes de una empresa textil, asegurando que todos los materiales necesarios están disponibles antes de iniciar la confección.

## 📌 Solución Técnica
- 🌐 **Backend**: API REST en .NET Core 8 con gestión de pedidos y avíos.
- 📱 **App Móvil (Android)**: Aplicación .NET MAUI para escaneo NFC y registro.
- 💻 **Dashboard Web**: Visualización en tiempo real del estado de pedidos y avíos.
- 📡 **MQTT (Mosquitto)**: Comunicación en tiempo real para eventos de estado.
- 🛢️ **Base de Datos (SQL Server)**: Almacenamiento seguro y escalable de datos.

## 📂 Repositorios de la Organización
| Repositorio | Descripción |
|--------------|--------------|
| [🔧 textil-trazabilidad-backend](https://github.com/tesis-I-textil-suit/textil-trazabilidad-backend) | API REST y lógica de negocio. |
| [📱 textil-trazabilidad-app](https://github.com/tesis-I-textil-suit/textil-trazabilidad-app) | App móvil Android para escaneo NFC. |
| [💻 textil-trazabilidad-dashboard](https://github.com/tesis-I-textil-suit/textil-trazabilidad-dashboard) | Dashboard web para monitoreo en tiempo real. |

## 🌐 Arquitectura del Sistema
![image](https://github.com/user-attachments/assets/aba60f83-6e60-4a20-98ce-aebc48ec47e1)

## 🚦 Estado del Proyecto
- 🚀 Backend: En desarrollo ✅
- 📱 App Móvil: En desarrollo ✅
- 💻 Dashboard Web: En desarrollo ✅

## ✨ Características Clave
- 📌 Gestión de pedidos y avíos.
- 📡 Monitoreo en tiempo real vía MQTT.
- 📱 Escaneo de tags NFC para identificar avíos.
- 🔑 Control de estados: En almacén, Enviado, Recibido, Completo.
- 🔓 Tags NFC reutilizables.
