# Checklist de Cumplimiento - Política 01: Protección del Puesto de Trabajo

**Política asociada**: Política 01 - Protección del Puesto de Trabajo  
**Versión del checklist**: 1.0  
**Fecha**: [Completar con fecha de creación]

---

## Información de la Auditoría

**Fecha de auditoría**: ___________________  
**Auditor**: ___________________________  
**Área/Departamento auditado**: ___________________________  
**Alcance de la auditoría**: ___________________________

---

## Instrucciones de Uso

### Niveles de Control

- **B (Básico)**: Medidas esenciales - implementación obligatoria
- **A (Avanzado)**: Medidas adicionales - proporcionan protección extra

### Alcance

- **PRO (Procesos)**: Dirección y gestión
- **TEC (Tecnología)**: Personal técnico de IT
- **PER (Personas)**: Todo el personal

### Sistema de Calificación

- ✅ **CUMPLE**: Control implementado correctamente
- ⚠️ **CUMPLE PARCIALMENTE**: Implementado pero necesita mejoras
- ❌ **NO CUMPLE**: No implementado o insuficiente
- N/A **NO APLICA**: No aplicable en este contexto

---

## Resumen Ejecutivo

| Categoría | Total Controles | Cumple | Cumple Parcial | No Cumple | N/A | % Cumplimiento |
|-----------|-----------------|--------|----------------|-----------|-----|----------------|
| 1. Configuración y Hardening | 10 | | | | | |
| 2. Control de Acceso | 8 | | | | | |
| 3. Protección Malware | 7 | | | | | |
| 4. Actualización y Parches | 5 | | | | | |
| 5. Gestión de Datos | 6 | | | | | |
| 6. Dispositivos y Periféricos | 7 | | | | | |
| 7. Monitorización y Auditoría | 4 | | | | | |
| 8. Formación y Concienciación | 5 | | | | | |
| **TOTAL** | **52** | | | | | |

**Nivel de cumplimiento global**: __________% (**Objetivo**: ≥ 95% en controles básicos, ≥ 70% en controles avanzados)

---

## 1. Configuración Segura y Hardening de Equipos

### 1.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 1.1.1 | B | TEC | **Configuración estándar baseline**<br>Todos los equipos se configuran según baseline de seguridad documentada (última versión aprobada). | ☐ | | | | |
| 1.1.2 | B | TEC | **Contraseña de BIOS/UEFI**<br>Los equipos tienen contraseña configurada en BIOS/UEFI que impide cambios no autorizados. | ☐ | | | | |
| 1.1.3 | B | PER | **Bloqueo automático de sesión**<br>Las sesiones se bloquean automáticamente tras [X] minutos de inactividad (≤ 10 min. recomendado). | ☐ | | | | |
| 1.1.4 | B | TEC | **Firewall local activado**<br>El firewall del sistema operativo está activado con reglas configuradas adecuadamente. | ☐ | | | | |
| 1.1.5 | B | TEC | **Servicios innecesarios deshabilitados**<br>Los servicios y puertos no necesarios están deshabilitados según baseline. | ☐ | | | | |
| 1.1.6 | B | TEC | **Usuarios sin privilegios administrativos**<br>Los usuarios trabajan con cuentas estándar sin privilegios de administrador local. | ☐ | | | | |
| 1.1.7 | B | PRO | **Inventario actualizado de equipos**<br>Existe inventario completo y actualizado (hardware, software, usuario asignado, ubicación). | ☐ | | | | |

### 1.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 1.2.1 | A | TEC | **Cifrado de disco completo**<br>Los portátiles y equipos con datos sensibles tienen cifrado de disco completo activado (ej: BitLocker, FileVault, LUKS). | ☐ | | | | |
| 1.2.2 | A | TEC | **Gestión centralizada (GPO/MDM)**<br>Las configuraciones de seguridad se gestionan centralizadamente mediante políticas de grupo o MDM. | ☐ | | | | |
| 1.2.3 | A | TEC | **Arranque seguro (Secure Boot)**<br>Secure Boot está habilitado para prevenir rootkits y bootkits. | ☐ | | | | |

---

## 2. Control de Acceso y Autenticación

### 2.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 2.1.1 | B | PRO | **Política de contraseñas documentada**<br>Existe política escrita que define requisitos de contraseñas (longitud mín., complejidad, caducidad). | ☐ | | | | |
| 2.1.2 | B | PER | **Contraseñas robustas**<br>Las contraseñas cumplen requisitos: mínimo [X caracteres, ej: 12], combinación alfanumérica con símbolos. | ☐ | | | | |
| 2.1.3 | B | PRO | **Proceso altas/bajas/cambios**<br>Existe procedimiento documentado para gestión de accesos (alta, baja, modificación de permisos). | ☐ | | | | |
| 2.1.4 | B | TEC | **Bloqueo de cuentas por intentos fallidos**<br>Tras [X] intentos fallidos de autenticación, la cuenta se bloquea temporalmente. | ☐ | | | | |
| 2.1.5 | B | TEC | **Revisión periódica de permisos**<br>Se revisan y certifican trimestralmente los permisos de acceso de usuarios. | ☐ | | | | |
| 2.1.6 | B | PRO | **Deshabilitación de cuentas inactivas**<br>Las cuentas inactivas [X días, ej: 90] se deshabilitan automáticamente. | ☐ | | | | |

### 2.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 2.2.1 | A | TEC | **Autenticación multifactor (MFA)**<br>Los accesos a sistemas críticos requieren segundo factor de autenticación. | ☐ | | | | |
| 2.2.2 | A | TEC | **Single Sign-On (SSO)**<br>Se utiliza SSO para acceso unificado a aplicaciones corporativas. | ☐ | | | | |

---

## 3. Protección contra Malware y Amenazas

### 3.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 3.1.1 | B | TEC | **Antivirus/Antimalware instalado**<br>Todos los equipos tienen solución antimalware instalada y en ejecución permanente. | ☐ | | | | |
| 3.1.2 | B | TEC | **Actualizaciones automáticas de firmas**<br>Las definiciones de malware se actualizan automáticamente al menos diariamente. | ☐ | | | | |
| 3.1.3 | B | TEC | **Escaneos programados**<br>Se realizan escaneos completos automáticos semanalmente en todos los equipos. | ☐ | | | | |
| 3.1.4 | B | PRO | **Procedimiento ante detección**<br>Existe procedimiento documentado de actuación ante alerta de malware. | ☐ | | | | |
| 3.1.5 | B | PER | **Formación en phishing**<br>El personal ha recibido formación sobre identificación de emails maliciosos (último año). | ☐ | | | | |

### 3.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 3.2.1 | A | TEC | **EDR implementado**<br>Se utiliza solución EDR (Endpoint Detection and Response) para detección avanzada. | ☐ | | | | |
| 3.2.2 | A | PRO | **Simulaciones de phishing**<br>Se realizan campañas trimestrales de phishing simulado para evaluar concienciación. | ☐ | | | | |

---

## 4. Gestión de Actualizaciones y Parches

### 4.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 4.1.1 | B | TEC | **Sistema operativo actualizado**<br>El SO tiene instaladas todas las actualizaciones de seguridad críticas disponibles. | ☐ | | | | |
| 4.1.2 | B | TEC | **Aplicaciones actualizadas**<br>Las aplicaciones corporativas están en versiones soportadas y actualizadas. | ☐ | | | | |
| 4.1.3 | B | PRO | **Política de actualizaciones**<br>Existe política documentada que define plazos de aplicación de parches según criticidad. | ☐ | | | | |
| 4.1.4 | B | TEC | **Inventario de software**<br>Se mantiene inventario actualizado de software instalado en cada equipo. | ☐ | | | | |

### 4.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 4.2.1 | A | TEC | **Gestión centralizada de parches**<br>Las actualizaciones se gestionan centralizadamente mediante herramienta (WSUS, SCCM, etc.). | ☐ | | | | |

---

## 5. Gestión de Datos en Puestos de Trabajo

### 5.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 5.1.1 | B | PRO | **Política de almacenamiento**<br>Existe política que define dónde se puede/debe almacenar información según clasificación. | ☐ | | | | |
| 5.1.2 | B | PER | **Datos en ubicaciones corporativas**<br>La información corporativa se almacena prioritariamente en servidores/nube corporativa, no solo en local. | ☐ | | | | |
| 5.1.3 | B | PRO | **Copias de seguridad regulares**<br>Los datos críticos en equipos locales tienen copia de seguridad automática periódica. | ☐ | | | | |
| 5.1.4 | B | PER | **Prohibición de datos personales no autorizados**<br>Está prohibido almacenar información personal no relacionada con el trabajo. | ☐ | | | | |

### 5.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 5.2.1 | A | TEC | **Sincronización automática**<br>Los documentos se sincronizan automáticamente con repositorio centralizado. | ☐ | | | | |
| 5.2.2 | A | TEC | **DLP (Data Loss Prevention)**<br>Existe sistema que detecta y previene fuga de información sensible. | ☐ | | | | |

---

## 6. Gestión de Dispositivos y Periféricos

### 6.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 6.1.1 | B | PRO | **Política de dispositivos USB**<br>Existe política que regula el uso de dispositivos de almacenamiento extraíbles. | ☐ | | | | |
| 6.1.2 | B | PER | **Escaneo de dispositivos USB**<br>Los dispositivos extraíbles se escanean antes de usar en búsqueda de malware. | ☐ | | | | |
| 6.1.3 | B | PER | **Protección física de equipos**<br>Los portátiles tienen cable de seguridad o se guardan en lugar seguro cuando no se usan. | ☐ | | | | |
| 6.1.4 | B | PRO | **Procedimiento ante pérdida/robo**<br>Existe procedimiento para reportar y actuar ante pérdida o robo de equipo. | ☐ | | | | |

### 6.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 6.2.1 | A | TEC | **Bloqueo de puertos USB**<br>Los puertos USB están bloqueados por política y solo se habilitan previa autorización. | ☐ | | | | |
| 6.2.2 | A | TEC | **Geolocalización y borrado remoto**<br>Los portátiles pueden geolocalizarse y borrarse remotamente en caso de pérdida. | ☐ | | | | |
| 6.2.3 | A | TEC | **Control de impresión**<br>Las impresiones se registran y auditan para detectar posibles fugas de información. | ☐ | | | | |

---

## 7. Monitorización y Auditoría

### 7.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 7.1.1 | B | TEC | **Logs de eventos habilitados**<br>El registro de eventos del sistema está activado y configurado adecuadamente. | ☐ | | | | |
| 7.1.2 | B | PRO | **Auditorías periódicas**<br>Se realizan auditorías de cumplimiento al menos semestralmente. | ☐ | | | | |

### 7.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 7.2.1 | A | TEC | **SIEM implementado**<br>Los logs se centralizan en un SIEM para correlación y detección de anomalías. | ☐ | | | | |
| 7.2.2 | A | TEC | **Monitorización en tiempo real**<br>Existe monitorización continua que alerta ante comportamientos anómalos. | ☐ | | | | |

---

## 8. Formación y Concienciación

### 8.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 8.1.1 | B | PRO | **Programa de formación**<br>Existe programa de formación en seguridad para todo el personal (al incorporarse y anualmente). | ☐ | | | | |
| 8.1.2 | B | PER | **Formación completada**<br>El personal ha completado la formación de seguridad en los últimos 12 meses. | ☐ | | | | |
| 8.1.3 | B | PRO | **Materiales de concienciación**<br>Se dispone de materiales (guías, pósters, comunicados) que refuerzan buenas prácticas. | ☐ | | | | |
| 8.1.4 | B | PER | **Aceptación de políticas**<br>El personal ha leído y firmado la aceptación de las políticas de seguridad. | ☐ | | | | |

### 8.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Resp. Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------|--------------|
| 8.2.1 | A | PRO | **Evaluación de efectividad**<br>Se mide la efectividad de la formación mediante tests y métricas de incidentes. | ☐ | | | | |

---

## Hallazgos y Plan de Acción

### No Conformidades Críticas

| Control | Descripción | Riesgo | Acción Correctiva | Responsable | Fecha Límite | Estado |
|---------|-------------|--------|-------------------|-------------|--------------|--------|
| | | | | | | |

### No Conformidades Importantes

| Control | Descripción | Riesgo | Acción Correctiva | Responsable | Fecha Límite | Estado |
|---------|-------------|--------|-------------------|-------------|--------------|--------|
| | | | | | | |

### Observaciones y Mejoras

| Control | Observación | Mejora Propuesta | Prioridad |
|---------|-------------|------------------|-----------|
| | | | |

---

## Conclusiones

**Puntos Fuertes**:
1. 
2. 
3. 

**Áreas de Mejora Prioritarias**:
1. 
2. 
3. 

**Nivel de Madurez**: 
☐ Inicial (0-40%)  ☐ Básico (41-60%)  ☐ Gestionado (61-80%)  ☐ Optimizado (81-95%)  ☐ Excelencia (96-100%)

---

## Firmas

**Auditor**: _______________________ Fecha: _______  
**Responsable Área**: _______________________ Fecha: _______  
**Responsable Seguridad**: _______________________ Fecha: _______

**Próxima auditoría**: _______________________

---

> **INSTRUCCIÓN PARA LOS ESTUDIANTES**: Este checklist debe estar alineado con las medidas definidas en vuestra política. Cada control del checklist debe corresponder a una medida específica descrita en la política. Podéis añadir o eliminar controles según las necesidades específicas de vuestra organización, siempre que estén justificados por los riesgos identificados en el PDS.
