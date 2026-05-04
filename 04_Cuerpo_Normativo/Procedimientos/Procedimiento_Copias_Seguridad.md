# Procedimiento de Copias de Seguridad - INNOVATEK

## 1. Identificacion de Datos a Respaldar
*   Bases de datos de clientes y CRM.
*   Configuraciones y flujos de n8n.
*   Documentacion corporativa en la nube (OneDrive/Google Drive).
*   Configuraciones de red y servidores.

## 2. Frecuencia y Retencion
*   **Backups diarios:** Ejecutados automaticamente de forma incremental.
*   **Backups semanales:** Completos.
*   **Retencion:** Se mantendran copias de los ultimos 30 dias y una copia mensual durante 1 ano.

## 3. Almacenamiento y Cifrado
*   Todas las copias deben estar **cifradas en reposo** (AES-256).
*   Se seguira la regla **3-2-1**: 3 copias de los datos, en 2 soportes diferentes, con 1 copia fuera de la oficina (off-site cloud).

## 4. Pruebas de Restauracion
Semestralmente, el Responsable de Seguridad realizara una prueba de restauracion para verificar la integridad de las copias y el tiempo de recuperacion (RTO).

---
**Fecha:** 4 de mayo de 2026  
**Aprobado por:** Direccion General


