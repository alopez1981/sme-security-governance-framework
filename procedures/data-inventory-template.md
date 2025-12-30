# Registro de Actividades de Tratamiento (ROPA) - Template

Este documento sirve para mapear dónde están los datos sensibles de la empresa, cumpliendo con el RGPD (GDPR).

| ID | Tipo de Dato                 | Ubicación (SaaS/On-prem) | Responsable (Owner) | Medida de Seguridad                          | Nivel de Riesgo |
|:---|:-----------------------------|:-------------------------|:--------------------|:---------------------------------------------|:----------------|
| 01 | Datos de Empleados (Nóminas) | Google Drive (RRHH)      | Head of People      | Acceso restringido a grupo 'HR-Admins' + MFA | Alto 🔴         |
| 02 | Datos de Clientes (Emails)   | Base de Datos AWS (RDS)  | CTO / Tech Lead     | Cifrado en reposo (AES-256)                  | Medio 🟠        |
| 03 | Backups de Código            | GitHub                   | Engineering Manager | 2FA obligatorio + Branch Protection          | Bajo 🟢         |
| 04 | Facturación                  | ERP / SaaS Contabilidad  | CFO                 | Contraseña robusta                           | Alto 🔴         |

---
*Revisión obligatoria: Anual*