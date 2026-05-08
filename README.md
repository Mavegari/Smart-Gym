# ⚡ Smart Gym AI | Modular Payment Agent (Digital Product Edition)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3)
![Stripe](https://img.shields.io/badge/Stripe-Custom_Fields-635BFF?style=for-the-badge&logo=stripe)
![n8n](https://img.shields.io/badge/n8n-Workflow-FF6D5A?style=for-the-badge&logo=n8n)
![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?style=for-the-badge&logo=supabase)

> **Entrenamiento de precisión impulsado por IA.** Este repositorio demuestra la versatilidad del **Agente de Pagos Modular** para procesar pagos únicos con entrega inmediata de productos digitales personalizados.

## 🚀 Flujo de Usuario de Alto Impacto
A diferencia del modelo SaaS, este sistema está optimizado para la conversión directa y la captura de datos críticos en el momento del pago.

- **Frontend:** Landing Page profesional con **Storytelling** persuasivo para capturar leads.
- **Atomic Checkout (Stripe):** Captura de variables mediante `custom_fields` (Objetivo, Frecuencia, Lesiones) directamente en la pasarela de pago.
- **AI Personal Trainer (n8n):** Mapeo de datos dinámico y limpieza de etiquetas (`Data Cleaning`) para alimentar el modelo de lenguaje.
- **Persistencia Dinámica:** Registro en Supabase vinculando el `stripe_payment_id` con las métricas de salud del cliente.

## 🔧 Características Técnicas
1. **Validación de Datos:** Uso de lógica OR (`||`) en el orquestador para prevenir errores de base de datos (`not-null constraints`).
2. **UX de Pago:** Redirección inteligente con parámetros `prefilled_email` para reducir la fricción en la compra.
3. **Escalabilidad Serverless:** Arquitectura sin servidores que permite un mantenimiento mínimo y alta disponibilidad.

## 🧩 El Núcleo: Agente de Pagos Modular
Este proyecto utiliza el mismo backend que "Gourmet Master Academy", demostrando que el **Motor de Pagos** es agnóstico al sector. Cambiando simplemente el `System Prompt` y los campos de Stripe, el sistema pasa de ser un Sommelier a un Entrenador Personal.

