# Políticas de Seguridad del Puesto de Trabajo

## Contexto

Como parte del [Plan Director de Seguridad (PDS)](https://github.com/revilofe/2526_IS_u1_2_PDS) desarrollado previamente, uno de los proyectos estratégicos identificados fue la **implementación de políticas de seguridad para la protección del puesto de trabajo**.

En el PDS, se identificaron los activos prioritarios de la organización, se analizaron los distintos puestos de trabajo y se evaluaron los riesgos asociados. Este trabajo previo constituye la base fundamental para determinar qué políticas de seguridad tendrán mayor impacto en la organización.

## Escenario

La empresa subcontrata a nuestro equipo como consultores de ciberseguridad para desarrollar e implementar una política integral de protección del puesto de trabajo. El trabajo consiste en:

1. Identificar los puestos de trabajo clave, los elementos críticos (activos) asociados y los principales escenarios de riesgo
2. Seleccionar las políticas de seguridad de mayor impacto y despliegue más rápido para la organización
3. Definir y documentar al menos **cuatro políticas de seguridad**, siguiendo el esquema de INCIBE, adaptadas al contexto concreto de la empresa

## Objetivos de la Actividad

### 1. Trazabilidad y Justificación

Documentar el **proceso de toma de decisiones** que ha llevado a seleccionar las políticas propuestas:

- Conexión con el PDS previo (activos, puestos de trabajo, riesgos identificados)
- Criterios de priorización utilizados
- Justificación del impacto y urgencia de cada política seleccionada

### 2. Desarrollo de Políticas

Crear **al menos cuatro políticas de seguridad**:

- **Obligatoria**: Política de Protección del Puesto de Trabajo (política central)
- **Tres adicionales**, que pueden ser:
  - Políticas específicas para puestos de trabajo críticos identificados
  - Políticas generales relacionadas con el puesto de trabajo (ej: Gestión de Recursos Humanos, Aplicaciones Permitidas, Uso de Dispositivos Móviles, etc.)

### 3. Adaptación a la Organización

**CRÍTICO**: Las políticas deben estar completamente adaptadas al contexto específico de la empresa:

- Tamaño y sector de la organización
- Tipo de información que se maneja
- Recursos tecnológicos disponibles
- Cultura organizacional
- Puestos de trabajo específicos identificados en el PDS

## 📖 Cómo Empezar

**IMPORTANTE**: Si es la primera vez que trabajas en este proyecto, **lee primero la [Guía Rápida de Trabajo](GUIA_RAPIDA.md)** que explica paso a paso cómo completar este ejercicio.

## Estructura del Trabajo

El trabajo está organizado de la siguiente manera:

```
/
├── README.md (este documento)
├── GUIA_RAPIDA.md (⭐ LEER PRIMERO - Guía paso a paso)
├── TRAZABILIDAD.md (proceso de selección de políticas)
├── POLITICAS_SEGURIDAD.md (índice y descripción general)
├── politicas/
│   ├── PLANTILLA_POLITICA.md (plantilla genérica reutilizable)
│   ├── politica_01_proteccion_puesto_trabajo.md (ejemplo con instrucciones)
│   ├── politica_02_[nombre].md (⚠️ por completar)
│   ├── politica_03_[nombre].md (⚠️ por completar)
│   └── politica_04_[nombre].md (⚠️ por completar)
└── checklists/
    ├── PLANTILLA_CHECKLIST.md (plantilla genérica reutilizable)
    ├── checklist_politica_01.md (ejemplo con instrucciones)
    ├── checklist_politica_02.md (⚠️ por completar)
    ├── checklist_politica_03.md (⚠️ por completar)
    └── checklist_politica_04.md (⚠️ por completar)
```

## Documentos del Proyecto

### Documentación Principal

- **[Trazabilidad de Políticas](TRAZABILIDAD.md)**: Proceso de selección de políticas desde el análisis del PDS
- **[Políticas de Seguridad](POLITICAS_SEGURIDAD.md)**: Índice y navegación a las políticas desarrolladas

### Políticas Desarrolladas

1. **Política de Protección del Puesto de Trabajo** - [Ver política](politicas/politica_01_proteccion_puesto_trabajo.md) | [Ver checklist](checklists/checklist_politica_01.md)
2. **Política [Nombre]** - [Ver política](politicas/politica_02_nombre.md) | [Ver checklist](checklists/checklist_politica_02.md)
3. **Política [Nombre]** - [Ver política](politicas/politica_03_nombre.md) | [Ver checklist](checklists/checklist_politica_03.md)
4. **Política [Nombre]** - [Ver política](politicas/politica_04_nombre.md) | [Ver checklist](checklists/checklist_politica_04.md)

## Estructura de Cada Política

Siguiendo el modelo de INCIBE para políticas de seguridad en pymes, cada política incluye:

### 1. Antecedentes

Contexto que justifica la necesidad de esta política:
- Elementos clave del puesto de trabajo que se ven afectados
- Escenarios de riesgo identificados y su impacto potencial
- Conexión con los hallazgos del PDS
- Referencias normativas aplicables (ISO 27001, GDPR, LOPDGDD)

### 2. Objetivos

Declaración clara y concisa del propósito de la política (1-3 frases).

### 3. Checklist

Lista de controles de seguridad para verificar el cumplimiento de la política.

**Clasificación por nivel de complejidad**:
- **Básico (B)**: Recursos y esfuerzo asumibles
- **Avanzado (A)**: Recursos considerables y configuraciones complejas

**Clasificación por alcance**:
- **Procesos (PRO)**: Aplica a dirección o personal de gestión
- **Tecnología (TEC)**: Aplica a personal técnico especializado
- **Personas (PER)**: Aplica a todo el personal

### 4. Puntos Clave

Resumen estructurado de las medidas más importantes de la política, adaptadas a la empresa.

## Criterios de Evaluación

| Criterio | Peso | Descripción |
|----------|------|-------------|
| **Trazabilidad** | 20% | Conexión clara y documentada con el PDS. Justificación sólida del proceso de selección. |
| **Adaptación** | 25% | Las políticas están completamente adaptadas a la empresa específica, no son genéricas. |
| **Antecedentes** | 15% | Identificación completa de elementos clave y escenarios de riesgo relevantes. |
| **Objetivos** | 10% | Objetivos claros, concisos y alineados con los antecedentes. |
| **Puntos Clave** | 15% | Medidas específicas, prácticas y proporcionales a los riesgos. |
| **Checklist** | 10% | Controles verificables, bien clasificados por nivel y alcance. |
| **Presentación** | 5% | Formato profesional, estructura clara, sin errores ortográficos. |

## Recursos de Apoyo

### Documentación Base

- [Teoría: Normativa de Protección del Puesto de Trabajo](https://revilofe.github.io/section2/u01/teoria/IS-U1.3.1.-ProteccionDelPuestoDeTrabajo/)
- [Plan Director de Seguridad previo](https://github.com/revilofe/2526_IS_u1_2_PDS)

### Ejemplos INCIBE Disponibles

Los siguientes ejemplos están disponibles en la carpeta `.recursos/`:

- Protección del puesto de trabajo
- Aplicaciones permitidas
- Gestión de recursos humanos
- Contraseñas
- Clasificación de la información
- Copias de seguridad
- Teletrabajo seguro
- Y muchas más...

## Equipo de Trabajo

- [Nombre del equipo]
- Integrantes: [Listar integrantes]

## Fecha de Entrega

[Especificar fecha límite]

---

**Nota**: Este trabajo representa la culminación del análisis realizado en el PDS. Debe demostrar la capacidad para traducir un análisis de riesgos en políticas de seguridad concretas, prácticas y adaptadas a una organización específica.
