# Plan de Continuidad de Negocio (BCP - Lite)

Protocolo de actuación ante desastres mayores que impidan la operativa normal.

## Escenarios Críticos

### A. Caída total de Proveedor Cloud (AWS/Google)

1. **Evaluación:** Verificar status page del proveedor.
2. **Comunicación:** Notificar a clientes vía Email/SMS externo (usando proveedor alternativo).
3. **Modo Offline:** Activar protocolo de papel/local en los centros físicos (si aplica) para registrar actividad
   básica.

### B. Indisponibilidad de Oficina (Incendio/Sin luz)

1. **Trabajo Remoto:** Activación inmediata del protocolo "Remote First".
2. **VPN/Accesos:** Todos los empleados deben tener configurado el acceso remoto seguro a los sistemas críticos.

## RTO y RPO (Objetivos de Recuperación)

* **RTO (Tiempo Objetivo de Recuperación):** 24 horas. (Tiempo máximo aceptable sin sistema).
* **RPO (Punto Objetivo de Recuperación):** 1 hora. (Máxima pérdida de datos aceptable - frecuencia de backup).