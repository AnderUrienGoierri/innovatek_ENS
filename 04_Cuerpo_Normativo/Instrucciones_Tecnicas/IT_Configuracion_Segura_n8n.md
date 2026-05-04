# Instruccion Tecnica: Configuracion Segura de n8n - INNOVATEK

## 1. Acceso a la Plataforma
*   El acceso a n8n se realizara exclusivamente a traves de un tunel seguro (HTTPS con TLS 1.2 o superior).
*   Se habilitara la autenticacion basica o el uso de proveedores de identidad (OAuth/SAML) con **MFA obligatorio**.

## 2. Gestion de Credenciales y API Keys
*   Todas las credenciales utilizadas en los flujos deben almacenarse en el sistema de **Credentials** propio de n8n, nunca en el codigo de las funciones.
*   Se recomienda el uso de variables de entorno para datos sensibles de configuracion.

## 3. Registro de Actividad (Logging)
*   Se mantendra activado el log de ejecucion de flujos para permitir la trazabilidad de las acciones.
*   Los logs se exportaran periodicamente a un sistema de almacenamiento externo para evitar su perdida en caso de fallo del contenedor/servidor.

## 4. Actualizaciones
*   Se revisara mensualmente la disponibilidad de nuevas versiones de n8n.
*   Las actualizaciones se probaran primero en un entorno de desarrollo antes de aplicarlas a produccion.

---
**Fecha:** 4 de mayo de 2026  
**Aprobado por:** Responsable de Seguridad


