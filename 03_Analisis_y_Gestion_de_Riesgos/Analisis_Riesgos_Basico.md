# Informe de Análisis de Riesgos - INNOVATEK IT CONSULTING

## 1. Evaluación de Riesgos por Activo

| Activo | Amenaza | Probabilidad | Impacto | Nivel de Riesgo | Medida de Mitigación |
| :--- | :--- | :---: | :---: | :---: | :--- |
| Equipos (Laptops) | Robo o pérdida | Media | Alto | **6 (Alto)** | Cifrado Bitlocker |
| Email (Cloud) | Acceso no autorizado | Alta | Alto | **9 (Crítico)** | Doble Factor (MFA) |
| Servidor/Web | Caída del servicio | Media | Medio | **4 (Medio)** | Backups diarios |
| Personal | Phishing / Error humano | Alta | Medio | **6 (Alto)** | Manual de concienciación |
| Sistemas y Equipos | Ransomware | Muy alta | Crítico | **9 (Crítico)** | Backups offline + Antivirus |
| Servicios Cloud | Indisponibilidad | Muy baja | Alto | **3 (Bajo)** | SLAs proveedores lderes |
| Personal y Datos | Fuga de datos | Media | Alto | **6 (Alto)** | Manual buenas prácticas + Control acceso |

## 2. Conclusiones
Los riesgos críticos (Acceso no autorizado y Ransomware) están mitigados mediante la implementación de MFA y políticas estrictas de copias de seguridad desconectadas. El nivel de riesgo residual se considera aceptable bajo la Categoría Básica del ENS.
