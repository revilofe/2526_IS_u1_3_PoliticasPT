# Checklist de Cumplimiento - [NOMBRE DE LA POLÍTICA]

**Política asociada**: [Nombre de la política]  
**Versión del checklist**: 1.0  
**Fecha**: [DD/MM/YYYY]

---

## Información de la Auditoría

**Fecha de auditoría**: ___________________  
**Auditor**: ___________________________  
**Área/Departamento auditado**: ___________________________  
**Alcance de la auditoría**: ___________________________

---

## Instrucciones de Uso

Este checklist debe utilizarse para verificar el cumplimiento de la política de [nombre]. 

### Niveles de Control

- **B (Básico)**: Medidas esenciales que deben estar implementadas obligatoriamente
- **A (Avanzado)**: Medidas adicionales que proporcionan protección extra

### Alcance

- **PRO (Procesos)**: Aplica a dirección y personal de gestión
- **TEC (Tecnología)**: Aplica a personal técnico de IT
- **PER (Personas)**: Aplica a todo el personal

### Sistema de Calificación

Para cada control, marcar:
- ✅ **CUMPLE**: El control está implementado correctamente
- ⚠️ **CUMPLE PARCIALMENTE**: El control está implementado pero necesita mejoras
- ❌ **NO CUMPLE**: El control no está implementado o es insuficiente
- N/A **NO APLICA**: El control no es aplicable en este contexto

---

## Resumen Ejecutivo

| Categoría | Total Controles | Cumple | Cumple Parcial | No Cumple | N/A | % Cumplimiento |
|-----------|-----------------|--------|----------------|-----------|-----|----------------|
| Controles Básicos | | | | | | |
| Controles Avanzados | | | | | | |
| **TOTAL** | | | | | | |

**Nivel de cumplimiento global**: __________% (**Objetivo**: ≥ 90% en controles básicos)

---

## 1. [CATEGORÍA 1: Ej. "Configuración Segura de Equipos"]

### 1.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Responsable Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------------|--------------|
| 1.1 | B | PER | **Bloqueo de sesión**<br>Los equipos se bloquean automáticamente tras [X] minutos de inactividad. | ☐ | | | | |
| 1.2 | B | TEC | **Antivirus actualizado**<br>Todos los equipos tienen antivirus instalado, activo y actualizado automáticamente. | ☐ | | | | |
| 1.3 | B | TEC | **Actualizaciones de sistema**<br>El sistema operativo está actualizado con todos los parches de seguridad críticos. | ☐ | | | | |
| 1.4 | B | TEC | **Firewall activado**<br>El firewall del sistema está activado y configurado correctamente. | ☐ | | | | |
| 1.5 | B | PRO | **Inventario de equipos**<br>Existe un inventario actualizado de todos los equipos de la organización. | ☐ | | | | |
| 1.6 | B | PER | **Contraseña de acceso**<br>Todos los equipos requieren contraseña para el acceso. | ☐ | | | | |
| 1.7 | B | TEC | **Usuarios con privilegios mínimos**<br>Los usuarios trabajan con cuentas sin privilegios administrativos. | ☐ | | | | |
| 1.8 | B | PER | **Pantalla de privacidad**<br>En puestos con información sensible se utilizan filtros de privacidad o se ubican para evitar miradas indiscretas. | ☐ | | | | |
| [...] | [...] | [...] | [...] | ☐ | | | | |

### 1.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Responsable Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------------|--------------|
| 1.9 | A | TEC | **Cifrado de disco completo**<br>Los discos duros de equipos portátiles están cifrados con [tecnología, ej: BitLocker, FileVault]. | ☐ | | | | |
| 1.10 | A | TEC | **Gestión centralizada de configuraciones**<br>Las configuraciones de seguridad se gestionan centralizadamente mediante [herramienta, ej: GPO, MDM]. | ☐ | | | | |
| 1.11 | A | TEC | **Segmentación de red**<br>Los equipos están en VLAN segmentadas según su función y nivel de acceso. | ☐ | | | | |
| 1.12 | A | TEC | **Monitorización de endpoints**<br>Existe un sistema de monitorización que detecta comportamientos anómalos en los equipos. | ☐ | | | | |
| [...] | [...] | [...] | [...] | ☐ | | | | |

---

## 2. [CATEGORÍA 2: Ej. "Control de Acceso y Autenticación"]

### 2.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Responsable Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------------|--------------|
| 2.1 | B | PRO | **Política de contraseñas**<br>Existe una política de contraseñas que define requisitos mínimos de complejidad y cambio. | ☐ | | | | |
| 2.2 | B | PER | **Contraseñas robustas**<br>Las contraseñas cumplen con requisitos mínimos: [especificar: longitud, complejidad]. | ☐ | | | | |
| 2.3 | B | PRO | **Gestión de altas y bajas**<br>Existe un procedimiento documentado para alta/baja/modificación de accesos. | ☐ | | | | |
| 2.4 | B | TEC | **Deshabilitación cuentas inactivas**<br>Las cuentas de usuario inactivas durante [X días] se deshabilitan automáticamente. | ☐ | | | | |
| 2.5 | B | PER | **No compartir credenciales**<br>Está prohibido y se cumple la norma de no compartir contraseñas entre usuarios. | ☐ | | | | |
| 2.6 | B | TEC | **Revisión periódica de accesos**<br>Se revisan trimestralmente los permisos de acceso de los usuarios. | ☐ | | | | |
| [...] | [...] | [...] | [...] | ☐ | | | | |

### 2.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Responsable Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------------|--------------|
| 2.7 | A | TEC | **Autenticación multifactor (MFA)**<br>Los accesos a sistemas críticos requieren autenticación de doble factor. | ☐ | | | | |
| 2.8 | A | TEC | **Single Sign-On (SSO)**<br>Se utiliza SSO para centralizar la autenticación en aplicaciones corporativas. | ☐ | | | | |
| 2.9 | A | TEC | **Gestión de identidades (IAM)**<br>Existe un sistema de gestión de identidades que automatiza altas/bajas/cambios. | ☐ | | | | |
| 2.10 | A | TEC | **Análisis de comportamiento de usuarios**<br>Se monitorizan patrones de acceso anómalos (UEBA). | ☐ | | | | |
| [...] | [...] | [...] | [...] | ☐ | | | | |

---

## 3. [CATEGORÍA 3: Ej. "Protección contra Malware"]

### 3.1. Controles Básicos

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Responsable Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------------|--------------|
| 3.1 | B | TEC | **Antivirus/Antimalware**<br>Todos los equipos tienen solución antimalware instalada y activa. | ☐ | | | | |
| 3.2 | B | TEC | **Actualizaciones automáticas**<br>Las definiciones de malware se actualizan automáticamente a diario. | ☐ | | | | |
| 3.3 | B | TEC | **Escaneos programados**<br>Se realizan escaneos completos semanalmente en todos los equipos. | ☐ | | | | |
| 3.4 | B | PRO | **Procedimiento ante detección**<br>Existe un procedimiento documentado de actuación ante detección de malware. | ☐ | | | | |
| 3.5 | B | PER | **Formación en phishing**<br>El personal ha recibido formación sobre identificación de correos maliciosos. | ☐ | | | | |
| 3.6 | B | TEC | **Filtrado de correo**<br>El servidor de correo tiene filtros antispam y antimalware. | ☐ | | | | |
| [...] | [...] | [...] | [...] | ☐ | | | | |

### 3.2. Controles Avanzados

| # | Nivel | Alcance | Control | Estado | Evidencias | Observaciones | Responsable Corrección | Fecha Límite |
|---|-------|---------|---------|--------|------------|---------------|------------------------|--------------|
| 3.7 | A | TEC | **EDR (Endpoint Detection and Response)**<br>Se utiliza una solución EDR que detecta y responde a amenazas avanzadas. | ☐ | | | | |
| 3.8 | A | TEC | **Sandboxing**<br>Los archivos sospechosos se analizan en entorno aislado antes de su ejecución. | ☐ | | | | |
| 3.9 | A | TEC | **Análisis de tráfico de red**<br>Se monitoriza el tráfico para detectar comunicaciones con C&C de malware. | ☐ | | | | |
| 3.10 | A | PRO | **Simulaciones de phishing**<br>Se realizan campañas periódicas de phishing simulado para evaluar y mejorar la concienciación. | ☐ | | | | |
| [...] | [...] | [...] | [...] | ☐ | | | | |

---

## 4. [CATEGORÍA 4: Ej. "Gestión de Dispositivos y Medios"]

### 4.1. Controles Básicos

[Repetir estructura de categorías anteriores]

### 4.2. Controles Avanzados

[Repetir estructura]

---

## 5. [CATEGORÍA 5: Ej. "Formación y Concienciación"]

### 5.1. Controles Básicos

[Repetir estructura]

### 5.2. Controles Avanzados

[Repetir estructura]

---

## 6. [Añadir más categorías según sea necesario]

---

## Hallazgos y No Conformidades

### No Conformidades Críticas

| # Control | Descripción del hallazgo | Riesgo asociado | Acción correctiva | Responsable | Fecha límite | Estado |
|-----------|-------------------------|-----------------|-------------------|-------------|--------------|--------|
| | | | | | | |
| | | | | | | |

### No Conformidades Mayores

| # Control | Descripción del hallazgo | Riesgo asociado | Acción correctiva | Responsable | Fecha límite | Estado |
|-----------|-------------------------|-----------------|-------------------|-------------|--------------|--------|
| | | | | | | |
| | | | | | | |

### No Conformidades Menores

| # Control | Descripción del hallazgo | Riesgo asociado | Acción correctiva | Responsable | Fecha límite | Estado |
|-----------|-------------------------|-----------------|-------------------|-------------|--------------|--------|
| | | | | | | |
| | | | | | | |

### Oportunidades de Mejora

| # Control | Descripción | Mejora propuesta | Beneficio esperado | Prioridad |
|-----------|-------------|------------------|-------------------|-----------|
| | | | | |
| | | | | |

---

## Evidencias Recopiladas

Listar las evidencias documentales, capturas de pantalla, logs, configuraciones, etc. que respaldan la auditoría:

1. [Descripción evidencia 1] - [Ubicación/referencia]
2. [Descripción evidencia 2] - [Ubicación/referencia]
3. [...]

---

## Plan de Acción

### Resumen de Acciones Correctivas

| Prioridad | Acción | Responsable | Recursos necesarios | Fecha inicio | Fecha límite | Estado |
|-----------|--------|-------------|---------------------|--------------|--------------|--------|
| CRÍTICA | | | | | | |
| ALTA | | | | | | |
| MEDIA | | | | | | |
| BAJA | | | | | | |

### Cronograma

```
SEMANA:    1    2    3    4    5    6    7    8    9    10   11   12
Acción 1:  [====]
Acción 2:       [=======]
Acción 3:            [====]
[...]
```

---

## Conclusiones de la Auditoría

### Puntos Fuertes

1. [Aspecto positivo 1]
2. [Aspecto positivo 2]
3. [...]

### Áreas de Mejora

1. [Área que requiere atención 1]
2. [Área que requiere atención 2]
3. [...]

### Recomendaciones Generales

1. [Recomendación 1]
2. [Recomendación 2]
3. [...]

### Evaluación Global

**Nivel de madurez de seguridad**: 
- ☐ Inicial (0-40%): Controles inexistentes o muy insuficientes
- ☐ Básico (41-60%): Controles básicos implementados pero con deficiencias
- ☐ Gestionado (61-80%): Buen nivel de implementación, algunas mejoras necesarias
- ☐ Optimizado (81-95%): Alto nivel de cumplimiento y madurez
- ☐ Excelencia (96-100%): Cumplimiento ejemplar

**Tendencia respecto a auditoría anterior**: 
- ☐ Mejora significativa
- ☐ Mejora
- ☐ Estable
- ☐ Empeoramiento
- ☐ N/A (primera auditoría)

---

## Firmas

### Auditor

**Nombre**: _________________________________  
**Cargo**: _________________________________  
**Fecha**: _________________________________  
**Firma**: _________________________________

### Responsable del Área Auditada

**Nombre**: _________________________________  
**Cargo**: _________________________________  
**Fecha**: _________________________________  
**Firma**: _________________________________  
**Conformidad con hallazgos**: ☐ Sí  ☐ No (adjuntar alegaciones)

### Responsable de Seguridad

**Nombre**: _________________________________  
**Cargo**: _________________________________  
**Fecha**: _________________________________  
**Firma**: _________________________________

---

## Seguimiento

### Próxima Auditoría Programada

**Fecha prevista**: _________________________________  
**Tipo**: ☐ Completa  ☐ Seguimiento de no conformidades  ☐ Parcial

### Revisiones Intermedias

| Fecha | Responsable | % Acciones completadas | Observaciones |
|-------|-------------|------------------------|---------------|
| | | | |
| | | | |
| | | | |

---

## Anexos

### Anexo I: Capturas de Pantalla y Evidencias Técnicas

[Incluir o referenciar]

### Anexo II: Configuraciones Revisadas

[Incluir o referenciar]

### Anexo III: Entrevistas Realizadas

| Entrevistado | Cargo | Fecha | Temas tratados |
|--------------|-------|-------|----------------|
| | | | |
| | | | |

---

**Documento controlado** - Este checklist forma parte del sistema de gestión de seguridad de la información.  
**Versión**: 1.0  
**Última actualización**: [DD/MM/YYYY]  
**Próxima revisión del checklist**: [DD/MM/YYYY]
