# Instrucción Técnica: Configuración Segura de n8n - INNOVATEK

## 1. Acceso a la Plataforma
*   El acceso a n8n se realizará exclusivamente a través de un túnel seguro (HTTPS con TLS 1.2 o superior).
*   Se habilitará la autenticación básica o el uso de proveedores de identidad (OAuth/SAML) con **MFA obligatorio**.

## 2. Gestión de Credenciales y API Keys
*   Todas las credenciales utilizadas en los flujos deben almacenarse en el sistema de **Credentials** propio de n8n, nunca en el código de las funciones.
*   Se recomienda el uso de variables de entorno para datos sensibles de configuración.

## 3. Registro de Actividad (Logging)
*   Se mantendrá activado el log de ejecución de flujos para permitir la trazabilidad de las acciones.
*   Los logs se exportarán periódicamente a un sistema de almacenamiento externo para evitar su pérdida en caso de fallo del contenedor/servidor.

## 4. Actualizaciones
*   Se revisará mensualmente la disponibilidad de nuevas versiones de n8n.
*   Las actualizaciones se probarán primero en un entorno de desarrollo antes de aplicarlas a producción.

---
**Fecha:** 4 de mayo de 2026  
**Aprobado por:** Responsable de Seguridad
