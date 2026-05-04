# Informe de Analisis de Riesgos - INNOVATEK IT CONSULTING

## 1. Evaluacion de Riesgos por Activo

| Activo | Amenaza | Probabilidad | Impacto | Nivel de Riesgo | Medida de Mitigacion |
| :--- | :--- | :---: | :---: | :---: | :--- |
| Equipos (Laptops) | Robo o perdida | Media | Alto | **6 (Alto)** | Cifrado Bitlocker |
| Email (Cloud) | Acceso no autorizado | Alta | Alto | **9 (Critico)** | Doble Factor (MFA) |
| Servidor/Web | Caida del servicio | Media | Medio | **4 (Medio)** | Backups diarios |
| Personal | Phishing / Error humano | Alta | Medio | **6 (Alto)** | Manual de concienciacion |
| Sistemas y Equipos | Ransomware | Muy alta | Critico | **9 (Critico)** | Backups offline + Antivirus |
| Servicios Cloud | Indisponibilidad | Muy baja | Alto | **3 (Bajo)** | SLAs proveedores lderes |
| Personal y Datos | Fuga de datos | Media | Alto | **6 (Alto)** | Manual buenas practicas + Control acceso |

## 2. Conclusiones
Los riesgos criticos (Acceso no autorizado y Ransomware) estan mitigados mediante la implementacion de MFA y politicas estrictas de copias de seguridad desconectadas. El nivel de riesgo residual se considera aceptable bajo la Categoria Basica del ENS.


