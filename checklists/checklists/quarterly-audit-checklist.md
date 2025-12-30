# Checklist Trimestral de Auditoría de Seguridad

**Fecha de ejecución:** ______________
**Auditor:** _______________________

## ☁️ Google Workspace & Cloud

- [ ] **Revisión de Drive:** Verificar que no existan archivos con permisos "Público en la web" que contengan datos
  sensibles.
- [ ] **MFA:** Confirmar que el 100% de los usuarios activos tienen el Doble Factor de Autenticación activado.
- [ ] **Logs:** Revisar alertas de "Login sospechoso" o descargas masivas en los últimos 90 días.

## 👥 Usuarios y Accesos

- [ ] **Cuentas Zombies:** Comparar listado de empleados activos en RRHH vs. Usuarios en Google/AWS. Eliminar cuentas de
  ex-empleados.
- [ ] **Administradores:** Verificar quién tiene rol de "Super Admin". Debe mantenerse al mínimo necesario.

## 💾 Infraestructura y Datos

- [ ] **Backups:** Realizar una prueba real de restauración de un archivo/base de datos aleatoria ("Restore Test").
- [ ] **Actualizaciones:** Confirmar que los servidores y CMS (ej. WordPress) tienen los parches de seguridad críticos
  instalados.

## ✅ Conformidad

- [ ] ¿Se ha detectado alguna violación de políticas este trimestre? (Si/No)

---
*Resultado: Aprobado / Requiere Acción*