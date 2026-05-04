# Procedimiento de Copias de Seguridad - INNOVATEK

## 1. Identificación de Datos a Respaldar
*   Bases de datos de clientes y CRM.
*   Configuraciones y flujos de n8n.
*   Documentación corporativa en la nube (OneDrive/Google Drive).
*   Configuraciones de red y servidores.

## 2. Frecuencia y Retención
*   **Backups diarios:** Ejecutados automáticamente de forma incremental.
*   **Backups semanales:** Completos.
*   **Retención:** Se mantendrán copias de los últimos 30 días y una copia mensual durante 1 año.

## 3. Almacenamiento y Cifrado
*   Todas las copias deben estar **cifradas en reposo** (AES-256).
*   Se seguirá la regla **3-2-1**: 3 copias de los datos, en 2 soportes diferentes, con 1 copia fuera de la oficina (off-site cloud).

## 4. Pruebas de Restauración
Semestralmente, el Responsable de Seguridad realizará una prueba de restauración para verificar la integridad de las copias y el tiempo de recuperación (RTO).

---
**Fecha:** 4 de mayo de 2026  
**Aprobado por:** Dirección General
