# Plan de Respuesta ante Incidentes (IRP)

Este playbook define el protocolo de actuación ante eventos de seguridad (Ransomware, Fuga de Datos, Phishing exitoso).

## Fases de Respuesta

### 1. Identificación 🔍

* **Acción:** Reportar cualquier anomalía al canal de seguridad (Slack/Teams/Email) inmediatamente.
* **Responsable:** Todo empleado.

### 2. Contención 🛡️

* **Objetivo:** Evitar que la amenaza se propague.
* **Acciones:**
    - Desconectar el equipo afectado de la red (Wi-Fi/Cable).
    - Revocar sesiones de usuario comprometidas.
    - Cambiar contraseñas de administración.

### 3. Análisis 🧠

* **Acción:** El equipo técnico investigará el origen (Causa Raíz) y el alcance (qué datos se han tocado).
* **Herramientas:** Revisión de Logs (AWS CloudTrail, Google Admin Console).

### 4. Comunicación y Legal (RGPD) ⚖️

* **Crítico:** Si el incidente afecta a datos personales, se debe notificar a la **Agencia de Protección de Datos (AEPD)
  ** en un plazo máximo de **72 horas**.
* **Responsable:** DPD (Delegado de Protección de Datos) / Comité de Seguridad.

### 5. Erradicación y Recuperación 🧹

* **Acciones:**
    - Eliminar malware o cerrar vulnerabilidades.
    - Restaurar sistemas desde una copia de seguridad limpia (Backup).
    - Verificar funcionamiento normal.

### 6. Lecciones Aprendidas (Post-Mortem) 📝

* **Acción:** Documentar el incidente y actualizar las políticas para evitar repetición.

---
*Basado en estándares NIST / ISO 27035*