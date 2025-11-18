Basándome en los documentos analizados de INCIBE y la información proporcionada sobre protección del puesto de trabajo, he identificado la estructura estándar que siguen las políticas de seguridad para pymes. A continuación, te proporciono la redacción completa para el ejercicio:

***

# Actividad: Desarrollo de Políticas de Seguridad del Puesto de Trabajo

## Contexto

Como parte del [Plan Director de Seguridad (PDS)](https://github.com/revilofe/2526_IS_u1_2_PDS/blob/master/README.md) desarrollado previamente, uno de los proyectos estratégicos identificados fue la **implementación de políticas de seguridad para la protección del puesto de trabajo**. Este trabajo constituye la materialización de dicho proyecto.

En el PDS, los grupos identificaron los activos prioritarios de la organización, analizaron los distintos puestos de trabajo y evaluaron los riesgos asociados. Este trabajo previo constituye la base fundamental para determinar qué políticas de seguridad tendrán mayor impacto en la organización.

## Escenario

La empresa os subcontrata como consultores de ciberseguridad para desarrollar e implementar una política integral de protección del puesto de trabajo. Vuestro trabajo consistirá en:

1. Identificar varios puestos de trabajo críticos en la organización
2. Analizar elementos clave (activos) y escenarios de riesgo específicos
3. Priorizar los riesgos de mayor impacto
4. Desarrollar un conjunto de políticas de seguridad adaptadas a la empresa
5. Crear herramientas de validación (checklists) para garantizar su cumplimiento

## Objetivos de la Actividad

### 1. Trazabilidad y Justificación

Deberéis documentar exhaustivamente el **proceso de toma de decisiones** que os ha llevado a seleccionar las políticas propuestas:

- Conexión con el PDS previo (activos, puestos de trabajo, riesgos identificados)
- Criterios de priorización utilizados
- Justificación del impacto y urgencia de cada política seleccionada

### 2. Desarrollo de Políticas

Deberéis crear **al menos cuatro políticas de seguridad**:

- **Obligatoria**: Política de Protección del Puesto de Trabajo (general)
- **Tres adicionales** que pueden ser:
  - Políticas específicas para puestos de trabajo críticos identificados
  - Políticas generales relacionadas con el puesto de trabajo (ej: Gestión de Recursos Humanos, Aplicaciones Permitidas, Uso de Dispositivos Móviles, etc.)

### 3. Adaptación a la Organización

**CRÍTICO**: Las políticas deben estar completamente adaptadas al contexto específico de vuestra empresa:

- Tamaño y sector de la organización
- Tipo de información que se maneja
- Recursos tecnológicos disponibles
- Cultura organizacional
- Puestos de trabajo específicos identificados en el PDS

## Estructura de Cada Política

Siguiendo el modelo de INCIBE para políticas de seguridad en pymes, cada política debe incluir:

### 1.1. Antecedentes

Contexto que justifica la necesidad de esta política:

- **Elementos clave del puesto de trabajo** que se ven afectados (dispositivos, software, comunicaciones, instalaciones físicas, acceso a datos, personal)
- **Escenarios de riesgo** identificados y su impacto potencial en la organización
- Conexión con los hallazgos del PDS
- Referencias normativas aplicables (ISO 27001, GDPR, LOPDGDD)

**Ejemplo de antecedentes bien desarrollados**:
> "En nuestra organización, el equipo de desarrollo maneja código fuente propietario y credenciales de acceso a sistemas de producción desde sus puestos de trabajo. Durante el análisis de riesgos del PDS, identificamos que el 40% de los desarrolladores trabajan en modo híbrido, conectándose desde redes públicas. Los principales escenarios de riesgo incluyen: intercepción de credenciales en redes no seguras, acceso no autorizado por dispositivos desbloqueados, y fuga de código fuente por pérdida de dispositivos..."

### 1.2. Objetivos

Declaración clara y concisa del propósito de la política (1-3 frases).

**Ejemplo**:
> "Garantizar la seguridad de la información y los recursos gestionados desde los puestos de trabajo del equipo de desarrollo, protegiendo especialmente el código fuente y las credenciales de acceso mediante controles técnicos y organizativos proporcionales a los riesgos identificados."

### 1.3. Checklist

Lista de controles de seguridad para verificar el cumplimiento de la política.

**Clasificación por nivel de complejidad**:
- **Básico (B)**: Recursos y esfuerzo asumibles. Funcionalidades incorporadas en aplicaciones comunes.
- **Avanzado (A)**: Recursos considerables. Configuraciones complejas y mecanismos de recuperación.

**Clasificación por alcance**:
- **Procesos (PRO)**: Aplica a dirección o personal de gestión
- **Tecnología (TEC)**: Aplica a personal técnico especializado
- **Personas (PER)**: Aplica a todo el personal

**Formato de tabla**:

| NIVEL | ALCANCE | CONTROL | ☐ |
|-------|---------|---------|---|
| B | PRO | **Nombre del control**<br>Descripción clara de qué debe verificarse o cumplirse. | ☐ |
| A | TEC | **Nombre del control**<br>Descripción clara de qué debe verificarse o cumplirse. | ☐ |

**Cada checklist debe incluir**:
- Espacio para: "Revisado por: _______________ Fecha: __________"

### 1.4. Puntos Clave

Desarrollo detallado de las **medidas de seguridad (normativas)** que implementan los controles del checklist:

- Descripción específica de cada medida
- Instrucciones concretas sobre qué debe hacerse
- Responsables de la implementación
- Frecuencia o condiciones de aplicación

**Ejemplo de punto clave bien desarrollado**:
> **Bloqueo programado de sesión**: El personal técnico configurará el bloqueo automático de sesión en todos los equipos del equipo de desarrollo tras 5 minutos de inactividad. Esta configuración se aplicará mediante GPO (Group Policy Object) en el dominio corporativo y será auditada mensualmente. Para equipos no unidos al dominio, se proporcionará un script de configuración y un procedimiento de verificación manual.

### Referencias

Lista numerada de normativas, estándares y recursos consultados.

## Entregables

### 1. Documento Principal: `POLITICAS_SEGURIDAD.md`

Estructura del documento:

```markdown
# Políticas de Seguridad del Puesto de Trabajo
## [Nombre de la Empresa]

### Índice
1. Introducción y Trazabilidad
2. Metodología de Priorización
3. Política 1: Protección del Puesto de Trabajo
4. Política 2: [Nombre]
5. Política 3: [Nombre]
6. Política 4: [Nombre]
7. Referencias

### 1. Introducción y Trazabilidad

#### 1.1. Conexión con el Plan Director de Seguridad
[Resumen de hallazgos clave del PDS que justifican estas políticas]

#### 1.2. Puestos de Trabajo Identificados
[Lista y descripción de puestos críticos]

#### 1.3. Activos Prioritarios
[Activos identificados en el PDS que se protegen con estas políticas]

### 2. Metodología de Priorización

[Explicación de criterios utilizados para seleccionar estas políticas]

#### 2.1. Criterios de Impacto
[Matriz de riesgo: probabilidad x impacto]

#### 2.2. Criterios de Urgencia
[Factores que determinan la urgencia: normativa, incidentes previos, etc.]

#### 2.3. Justificación de Selección
[Por qué estas 4 políticas y no otras]

### 3. Política 1: Protección del Puesto de Trabajo

#### 3.1. Antecedentes
[Desarrollo detallado]

#### 3.2. Objetivos
[Declaración concisa]

#### 3.3. Checklist
[Tabla de controles]

#### 3.4. Puntos Clave
[Desarrollo de medidas]

#### 3.5. Referencias
[Lista numerada]

[Repetir estructura para Políticas 2, 3 y 4]
```

### 2. Checklists Individuales

Para cada política, crear un documento PDF independiente siguiendo el formato visual de INCIBE:

- `CHECKLIST_Politica1.pdf`
- `CHECKLIST_Politica2.pdf`
- `CHECKLIST_Politica3.pdf`
- `CHECKLIST_Politica4.pdf`

Estos checklists deben ser documentos operativos que puedan imprimirse y utilizarse para auditorías.

## Criterios de Evaluación

| Criterio | Peso | Descripción |
|----------|------|-------------|
| **Trazabilidad** | 20% | Conexión clara y documentada con el PDS. Justificación sólida del proceso de selección de políticas. |
| **Adaptación** | 25% | Las políticas están completamente adaptadas a la empresa específica, no son genéricas. |
| **Antecedentes** | 15% | Identificación completa de elementos clave del puesto y escenarios de riesgo relevantes. |
| **Objetivos** | 10% | Objetivos claros, concisos y alineados con los antecedentes. |
| **Puntos Clave** | 15% | Medidas específicas, prácticas y proporcionales a los riesgos. |
| **Checklist** | 10% | Controles verificables, bien clasificados por nivel y alcance. |
| **Presentación** | 5% | Formato profesional, estructura clara, sin errores ortográficos. |

## Recursos de Apoyo

### Documentación Base
- [Teoría: Normativa de Protección del Puesto de Trabajo](https://revilofe.github.io/section2/u01/teoria/IS-U1.3.1.-ProteccionDelPuestoDeTrabajo/)
- Ejemplos INCIBE adjuntos:
  - `proteccion-puesto-trabajo.pdf` y checklist
  - `gestion-recursos-humanos.pdf` y checklist
  - `aplicaciones-permitidas.pdf` y checklist

### Políticas Adicionales Sugeridas
Según vuestros hallazgos en el PDS, podéis considerar desarrollar:

- Uso del correo electrónico
- Uso de dispositivos móviles corporativos
- Uso de Internet
- Clasificación de la información
- Control de accesos físicos y lógicos
- Gestión de contraseñas
- Cifrado de información
- Copias de seguridad
- Teletrabajo y trabajo remoto

## Consejos Prácticos

1. **Empezad por la trazabilidad**: Revisad vuestro PDS y extraed los hallazgos clave antes de decidir qué políticas desarrollar.

2. **Sed específicos**: Evitad políticas genéricas. Incluid nombres de sistemas, roles específicos, ubicaciones reales de vuestra empresa.

3. **Pensad en la implementación real**: Las medidas deben ser factibles con los recursos de la empresa. Si proponéis medidas avanzadas, justificad su necesidad.

4. **Los antecedentes son críticos**: Esta sección debe convencer al lector (y a la dirección de la empresa) de POR QUÉ esta política es necesaria.

5. **Checklists operativos**: Diseñad los checklists pensando en que alguien realmente los usará para auditorías. Deben ser claros y sin ambigüedades.

6. **Revisad los ejemplos de INCIBE**: La estructura está probada y es efectiva. Adaptadla a vuestro contexto.

---

## Fecha de Entrega

[Especificar fecha límite]

## Forma de Entrega

Repositorio GitHub con la siguiente estructura:

```
README.md (este documento)
POLITICAS_SEGURIDAD.md
/checklists
  ├── CHECKLIST_Politica1.pdf
  ├── CHECKLIST_Politica2.pdf
  ├── CHECKLIST_Politica3.pdf
  └── CHECKLIST_Politica4.pdf
/recursos
  └── [Diagramas, tablas de riesgo, etc.]
```

***

**Nota Final**: Este trabajo representa la culminación del análisis realizado en el PDS. Debe demostrar vuestra capacidad para traducir un análisis de riesgos en políticas de seguridad concretas, prácticas y adaptadas a una organización específica. La calidad de la trazabilidad y la adaptación al contexto empresarial serán los factores determinantes en la evaluación.

[1](https://revilofe.github.io/section2/u01/teoria/IS-U1.3.1.-ProteccionDelPuestoDeTrabajo/)
[2](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/20004916/c34266c7-53da-460a-82d7-cfb490062658/gestion-recursos-humanos.pdf)
[3](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/20004916/d0e9f179-0f60-4eb9-b69f-6b4c2fa7e7f0/proteccion-puesto-trabajo.pdf)
[4](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/20004916/6246f720-cd4d-4d72-85fe-876d1b89fb56/proteccion-puesto-trabajo-checklist.pdf)
[5](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/20004916/ea48ebf6-8be5-44f4-9e7c-224014a1700a/aplicaciones-permitidas.pdf)
