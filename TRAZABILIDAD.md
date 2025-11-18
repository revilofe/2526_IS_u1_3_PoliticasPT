# Plantilla de Trazabilidad para la Selección de Políticas de Seguridad

## 1. Introducción

Este documento describe el proceso de toma de decisiones que ha llevado a la selección de las políticas de seguridad propuestas para la organización, estableciendo una **trazabilidad completa** desde el Plan Director de Seguridad (PDS) hasta las políticas implementadas.

## 2. Revisión del Plan Director de Seguridad

### 2.1. Resumen del PDS Previo

**Enlace al PDS**: [Incluir enlace al repositorio del PDS]

**Principales hallazgos del PDS**:

- **Activos críticos identificados**: [Describir brevemente]
- **Puestos de trabajo definidos**: [Listar]
- **Riesgos principales detectados**: [Enumerar]
- **Prioridades de seguridad**: [Indicar]

> **Nota**: Completar con la información específica del PDS desarrollado previamente por el grupo.

## 3. Análisis de Puestos de Trabajo y Activos Críticos

### 3.1. Identificación de Puestos de Trabajo

| ID Puesto | Puesto de Trabajo                  | Departamento   | Nº Empleados  | Criticidad        |
|-----------|------------------------------------|----------------|---------------|-------------------|
| PT-01     | [Ejemplo: Personal administrativo] | Administración | [Nº]          | [Alta/Media/Baja] |
| PT-02     | [Ejemplo: Asesor fiscal]           | Asesoría       | [Nº]          | [Alta/Media/Baja] |
| PT-03     | [Ejemplo: Técnico TI]              | IT             | [Nº]          | [Alta/Media/Baja] |
| PT-04     | [...]                              | [...]          | [...]         | [...]             |

### 3.2. Activos Clave por Puesto de Trabajo

| ID Puesto  | Activos Clave                                      | Tipo de Activo                | Impacto si se compromete  |
|------------|----------------------------------------------------|-------------------------------|---------------------------|
| PT-01      | [Ej: PC de oficina, ERP facturación, credenciales] | Hardware/Software/Información | [Describir]               |
| PT-02      | [Ej: Documentación clientes, correo electrónico]   | Información/Software          | [Describir]               |
| PT-03      | [Ej: Servidores, consolas de gestión, VPN]         | Hardware/Software             | [Describir]               |
| PT-04      | [...]                                              | [...]                         | [...]                     |

### 3.3. Escenarios de Riesgo Identificados

| ID Riesgo  | Puesto Afectado  | Descripción del Riesgo                  | Probabilidad  | Impacto  | Nivel de Riesgo  |
|------------|------------------|-----------------------------------------|---------------|----------|------------------|
| R-01       | PT-01            | [Ej: Malware por correo electrónico]    | Alta          | Alto     | **CRÍTICO**      |
| R-02       | PT-01            | [Ej: Robo de credenciales]              | Media         | Alto     | **ALTO**         |
| R-03       | PT-02            | [Ej: Fuga de información de clientes]   | Media         | Muy Alto | **CRÍTICO**      |
| R-04       | PT-03            | [Ej: Acceso no autorizado a servidores] | Baja          | Muy Alto | **ALTO**         |
| R-05       | [...]            | [...]                                   | [...]         | [...]    | [...]            |

**Matriz de Riesgos**:

```
IMPACTO
    Muy Alto |     R-03        R-04
        Alto |  R-01   R-02
       Medio |
        Bajo |
             +------------------------
                Baja  Media  Alta
                   PROBABILIDAD
```

## 4. Criterios de Priorización de Políticas

### 4.1. Criterios Definidos

Para seleccionar las políticas de seguridad más apropiadas, se han establecido los siguientes criterios:

| Criterio                               | Peso  | Descripción                                                              |
|----------------------------------------|-------|--------------------------------------------------------------------------|
| **Impacto en la reducción de riesgos** | 35%   | Capacidad de la política para mitigar los riesgos críticos identificados |
| **Cobertura de activos críticos**      | 25%   | Número y criticidad de activos protegidos por la política                |
| **Facilidad de implementación**        | 20%   | Recursos necesarios vs. disponibles; tiempo de despliegue                |
| **Cumplimiento normativo**             | 15%   | Alineación con requisitos legales (GDPR, LOPDGDD, ISO 27001)             |
| **Coste-beneficio**                    | 5%    | Relación entre inversión necesaria y beneficio esperado                  |

### 4.2. Políticas Candidatas Evaluadas

| Política Candidata        | Impacto Riesgos (35%) | Cobertura Activos (25%)  | Facilidad (20%)  | Cumplimiento (15%) | Coste-Beneficio (5%)  | **TOTAL** |
|---------------------------|-----------------------|--------------------------|------------------|--------------------|-----------------------|:---------:|
| Protección Puesto Trabajo | 35                    | 25                       | 18               | 15                 | 5                     |  **98**   |
| Aplicaciones Permitidas   | 30                    | 20                       | 16               | 12                 | 4                     |  **82**   |
| Gestión RRHH              | 25                    | 15                       | 18               | 15                 | 5                     |  **78**   |
| Contraseñas               | 28                    | 18                       | 20               | 12                 | 5                     |  **83**   |
| Control de Accesos        | 32                    | 22                       | 12               | 15                 | 4                     |  **85**   |
| Copias de Seguridad       | 30                    | 20                       | 15               | 10                 | 4                     |  **79**   |
| Teletrabajo Seguro        | 25                    | 18                       | 14               | 10                 | 3                     |  **70**   |
| [...]                     | [...]                 | [...]                    | [...]            | [...]              | [...]                 |   [...]   |

> **Nota**: Ajustar puntuaciones según el análisis específico de la organización.

## 5. Selección de Políticas a Implementar

### 5.1. Políticas Seleccionadas

Basándonos en el análisis anterior, se han seleccionado las siguientes **cuatro políticas** para su implementación:

#### Política 1: Protección del Puesto de Trabajo ✅ OBLIGATORIA

**Puntuación**: 98/100

**Justificación**:
- Cubre los riesgos más críticos identificados (R-01, R-02, R-04)
- Protege los activos de los puestos más sensibles (PT-01, PT-03)
- Política fundamental y transversal a toda la organización
- Alta alineación con estándares ISO 27001 y ENS

**Riesgos mitigados**: [Listar IDs de riesgos que mitiga]

**Puestos beneficiados**: [Listar IDs de puestos]



#### Política 2: [Nombre de la Segunda Política]

**Puntuación**: [XX]/100

**Justificación**:
- [Explicar por qué se selecciona esta política]
- [Conexión con riesgos identificados]
- [Activos que protege]
- [Facilidad de implementación]

**Riesgos mitigados**: [Listar IDs]

**Puestos beneficiados**: [Listar IDs]



#### Política 3: [Nombre de la Tercera Política]

**Puntuación**: [XX]/100

**Justificación**:
- [Explicar por qué se selecciona esta política]
- [Conexión con riesgos identificados]
- [Activos que protege]
- [Facilidad de implementación]

**Riesgos mitigados**: [Listar IDs]

**Puestos beneficiados**: [Listar IDs]



#### Política 4: [Nombre de la Cuarta Política]

**Puntuación**: [XX]/100

**Justificación**:
- [Explicar por qué se selecciona esta política]
- [Conexión con riesgos identificados]
- [Activos que protege]
- [Facilidad de implementación]

**Riesgos mitigados**: [Listar IDs]

**Puestos beneficiados**: [Listar IDs]



### 5.2. Políticas Descartadas (y por qué)

| Política  | Puntuación  | Motivo de Descarte                                                                   |
|-----------|-------------|--------------------------------------------------------------------------------------|
| [Nombre]  | [XX]/100    | [Explicar: menor impacto, dificultad de implementación, ya cubierta por otras, etc.] |
| [Nombre]  | [XX]/100    | [Explicar]                                                                           |

## 6. Trazabilidad Completa: PDS → Políticas → Controles

### 6.1. Mapa de Trazabilidad

| Activo Crítico       | Puesto  | Riesgo (ID)  | Política Seleccionada     | Controles Específicos (Checklist)  |
|----------------------|---------|--------------|---------------------------|------------------------------------|
| [Ej: PC oficina]     | PT-01   | R-01         | Protección Puesto Trabajo | Control #1, #2, #5                 |
| [Ej: ERP]            | PT-01   | R-02         | Aplicaciones Permitidas   | Control #3, #7                     |
| [Ej: Docs. clientes] | PT-02   | R-03         | Clasificación Información | Control #2, #4, #6                 |
| [...]                | [...]   | [...]        | [...]                     | [...]                              |

### 6.2. Cobertura de Riesgos

**Resumen de cobertura**:

| Nivel de Riesgo | Riesgos Identificados | Riesgos Cubiertos  | % Cobertura  |
|-----------------|-----------------------|--------------------|--------------|
| CRÍTICO         | [Nº]                  | [Nº]               | [%]          |
| ALTO            | [Nº]                  | [Nº]               | [%]          |
| MEDIO           | [Nº]                  | [Nº]               | [%]          |
| BAJO            | [Nº]                  | [Nº]               | [%]          |

**Riesgos residuales** (no cubiertos por estas políticas):

- [R-XX]: [Descripción] - Motivo: [Baja prioridad / Se abordará en siguiente fase]
- [R-XX]: [Descripción] - Motivo: [...]

## 7. Plan de Implementación

### 7.1. Fases de Despliegue

| Fase   | Política                  | Prioridad  | Duración Estimada  | Responsable   |
|--------|---------------------------|------------|--------------------|---------------|
| Fase 1 | Protección Puesto Trabajo | Alta       | [X semanas]        | [Responsable] |
| Fase 2 | [Política 2]              | Alta       | [X semanas]        | [Responsable] |
| Fase 3 | [Política 3]              | Media      | [X semanas]        | [Responsable] |
| Fase 4 | [Política 4]              | Media      | [X semanas]        | [Responsable] |

### 7.2. Recursos Necesarios

| Recurso                  | Descripción  | Coste Estimado  |
|--------------------------|--------------|-----------------|
| [Ej: Formación personal] | [Detalles]   | [€]             |
| [Ej: Software antivirus] | [Detalles]   | [€]             |
| [Ej: Tiempo técnico TI]  | [Detalles]   | [horas]         |

## 8. Conclusiones

### 8.1. Resumen Ejecutivo

[Párrafo resumen de 3-5 frases explicando:
- Cómo se partió del PDS
- Qué criterios se usaron para priorizar
- Qué 4 políticas se seleccionaron
- Qué porcentaje de riesgos críticos se cubren
- Próximos pasos]

### 8.2. Recomendaciones

- **Corto plazo** (0-3 meses): [Acciones inmediatas]
- **Medio plazo** (3-6 meses): [Consolidación y auditoría]
- **Largo plazo** (6-12 meses): [Políticas adicionales a considerar]



## 9. Referencias

- Plan Director de Seguridad de [Nombre Empresa]: [Enlace]
- ISO/IEC 27001:2022 - Information Security Management
- Guías de INCIBE para Políticas de Seguridad en PYMES
- ENS (Esquema Nacional de Seguridad)
- RGPD (Reglamento General de Protección de Datos)

---

**Documento elaborado por**: [Nombre del equipo]  
**Fecha**: [DD/MM/YYYY]  
**Versión**: 1.0
