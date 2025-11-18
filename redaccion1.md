## Actividad: Políticas de seguridad del puesto de trabajo (trazabilidad desde el PDS)

### Contexto

En la actividad anterior, cada grupo ha elaborado un **Plan Director de Seguridad (PDS)** para la misma empresa (ver repositorio `2526_IS_u1_2_PDS`).
En ese PDS ya habéis:

* Identificado los **activos prioritarios** de la organización.
* Definido los **principales puestos de trabajo**.
* Asociado, al menos de forma inicial, **riesgos** y escenarios de incidente a esos puestos y activos.

En este nuevo encargo, la empresa **subcontrata a vuestro equipo** para desarrollar uno de los proyectos del PDS:

> **Definir y documentar un conjunto de políticas de seguridad relacionadas con el puesto de trabajo.**

Este trabajo debe dejar clara la **trazabilidad**: cómo, a partir de los activos, puestos y riesgos detectados en el PDS, llegáis a decidir **qué políticas son prioritarias** y cuáles se van a implantar primero.

Además, debéis seguir el esquema y estilo de las **políticas de seguridad para la pyme de INCIBE**, en especial las de:

* **Protección del puesto de trabajo**
* **Aplicaciones permitidas**
* **Gestión de recursos humanos**

y otras que consideréis relevantes para la empresa.

---

### Objetivo de la actividad

A partir del PDS ya elaborado:

1. **Identificar los puestos de trabajo clave**, los elementos críticos (activos) asociados a cada uno y los principales escenarios de riesgo.
2. **Seleccionar las políticas de seguridad de mayor impacto y despliegue más rápido** para la organización.
3. **Definir y documentar al menos cuatro políticas de seguridad**, siguiendo el esquema de INCIBE, adaptadas al contexto concreto de la empresa.

---

### Alcance de la actividad

Debéis entregar, como mínimo, **cuatro políticas**:

* Obligatoriamente:

  1. **Política de protección del puesto de trabajo** (política central de la actividad).

* Además, al menos **tres políticas adicionales**, que pueden ser:

  * **Relacionadas directamente con el puesto de trabajo** (ej.: aplicaciones permitidas, uso de dispositivos móviles, contraseñas, almacenamiento, etc.).
  * O **políticas generales** que tengan un impacto claro en la seguridad del puesto (ej.: gestión de recursos humanos, concienciación y formación, clasificación de la información, etc.).

Todas las políticas deben estar **claramente adaptadas a la empresa del caso**, no pueden ser textos genéricos copiados sin más.

---

### Trabajo a realizar

#### 1. Revisión del Plan Director de Seguridad

Partiendo del PDS anterior:

* Revisad:

  * **Activos críticos** identificados.
  * **Puestos de trabajo** definidos (tipos de usuario, departamentos, roles…).
  * **Riesgos** asociados a esos activos y puestos.
* Si es necesario, **afinad o completad** la identificación de:

  * Puestos de trabajo más sensibles.
  * Escenarios de riesgo más realistas y relevantes.

> Esta revisión será la base para justificar por qué elegís unas políticas y no otras.

---

#### 2. Puestos de trabajo, activos y riesgos

Para cada puesto de trabajo relevante, debéis identificar:

* **Puesto / rol** (ej.: asesor fiscal, personal administrativo, técnico TI, dirección…).
* **Activos clave** que utiliza en su día a día (equipos, aplicaciones, información, credenciales, dispositivos móviles, etc.).
* **Escenarios de riesgo** más probables o más críticos (pérdida de información, acceso no autorizado, malware, fuga de datos, errores humanos, ingeniería social, etc.).

Se recomienda incluir una tabla de este estilo:

```markdown
| Puesto de trabajo      | Activo clave                         | Riesgo principal                                | Impacto (alto/medio/bajo) |
|------------------------|--------------------------------------|-------------------------------------------------|---------------------------|
| Personal administrativo| PC de oficina + ERP facturación      | Malware, robo de credenciales, fuga de datos    | Alto                      |
| Asesor fiscal          | Documentación clientes + correo      | Envío erróneo, pérdida de confidencialidad      | Alto                      |
| Técnico TI             | Servidores y consolas de gestión     | Configuración incorrecta, accesos no autorizados| Muy alto                  |
```

---

#### 3. Selección de políticas de mayor impacto

A partir del análisis anterior, debéis justificar:

* **Qué políticas de seguridad son prioritarias** para la empresa.
* **Por qué** (en base a los activos críticos, riesgos y puestos implicados).
* **Qué políticas se pueden implantar más rápido y con mejor relación esfuerzo/beneficio.**

Incluid una sección de **trazabilidad PDS → políticas**, por ejemplo con una tabla:

```markdown
| Puesto / Activo crítico              | Riesgo detectado                          | Política asociada                           | Justificación breve                                      |
|-------------------------------------|-------------------------------------------|---------------------------------------------|----------------------------------------------------------|
| PC de oficina + acceso a ERP        | Malware, acceso no autorizado             | Protección del puesto de trabajo            | Es la “puerta” principal a la información de la empresa. |
| Uso de múltiples aplicaciones       | Software pirata, apps no autorizadas      | Aplicaciones permitidas                     | Riesgo legal y de malware muy elevado.                   |
| Alta/Baja de empleados en sistemas  | Accesos activos tras baja, fuga de datos  | Gestión de recursos humanos                 | Clave en altas/bajas, permisos y confidencialidad.       |
```

---

#### 4. Desarrollo de las políticas (formato INCIBE)

Para cada una de las **cuatro políticas** seleccionadas, debéis redactar un documento siguiendo el esquema de INCIBE:

1. **Título de la política**

   * Ej.: *Política de protección del puesto de trabajo*, *Política de aplicaciones permitidas*, etc.
   * Indicad claramente si la política es:

     * **General** (afecta a toda la organización).
     * **Específica de ciertos puestos** (ej.: técnicos TI, personal de administración, etc.).

2. **1.1. Antecedentes**

   * Explicad, con vuestras palabras:

     * Cómo se trabaja en la empresa desde esos puestos.
     * Qué activos y qué riesgos justifican la existencia de esta política.
   * Debe verse claramente la **relación con el PDS y el análisis previo** (puestos, activos, riesgos).

3. **1.2. Objetivos**

   * Entre 2 y 4 frases que resuman:

     * Qué pretende garantizar la política.
     * Qué se quiere evitar.
   * Siempre **adaptado a la empresa del caso**, no en abstracto.

4. **1.3. Checklist**

   * Listado de **controles** que permitirán verificar el cumplimiento de la política.
   * Cada control debe indicar:

     * **Nivel**: Básico (B) o Avanzado (A).
     * **Alcance**: PRO (procesos/dirección), TEC (tecnología/personal técnico), PER (personas/empleados).
   * Se recomienda usar una tabla similar a la de INCIBE, por ejemplo:

```markdown
| Nº | Nivel | Alcance | Control / Medida                                                      | Evidencia de cumplimiento                     |
|----|-------|---------|------------------------------------------------------------------------|-----------------------------------------------|
| 1  | B     | PER     | Bloquear la sesión al ausentarse del puesto de trabajo.               | Observación, cartelería, registro de formación|
| 2  | B     | TEC     | Mantener el sistema operativo y el antivirus actualizados.            | Informes de actualización, inventario software|
| 3  | A     | PRO/TEC | Deshabilitar por defecto los puertos USB y habilitarlos solo a quien proceda.| Políticas TI, registros de solicitud y autorización|
```

* El número de controles debe ser **coherente con la política** y cubrir sus principales riesgos.

5. **1.4. Puntos clave**

   * Resumen estructurado de las **medidas más importantes** de la política.
   * Podéis inspiraros en los puntos clave de los documentos de INCIBE, pero:

     * Deben estar **adaptados a la empresa**.
     * Deben ser **redactados por vuestro grupo**, no copiados literalmente.

---

#### 5. Trazabilidad y explicación del proceso

Además de las políticas en sí, debéis incluir en el trabajo una sección donde expliquéis:

* **Cómo habéis pasado**:

  * De los **activos y riesgos del PDS**
  * A las **políticas seleccionadas**
  * Y de ahí a los **controles concretos de cada checklist**.

Esta explicación puede combinar:

* Un breve texto narrativo (2–3 párrafos).
* Tablas de trazabilidad como las indicadas más arriba.

La idea es que quede muy claro que las políticas **no salen “de la nada”**, sino que responden a:

* Una necesidad concreta de la empresa.
* Unos riesgos identificados previamente.
* Unos puestos de trabajo y activos muy específicos.

---

### Entrega

La entrega consistirá en:

1. **Documento(s) en Markdown** dentro de este repositorio, donde se incluyan:

   * La identificación de **puestos, activos y riesgos**.
   * La **selección justificada de políticas**.
   * Las **cuatro políticas desarrolladas** con el formato INCIBE (Antecedentes, Objetivos, Checklist, Puntos clave).
   * La sección de **trazabilidad** que explique el camino PDS → políticas → controles.

2. En el `README.md` del repositorio debéis:

   * Añadir una sección titulada, por ejemplo, `## Políticas de seguridad del puesto de trabajo`.
   * Incluir un breve resumen del trabajo realizado.
   * Añadir los **enlaces** a los ficheros donde habéis desarrollado las políticas.

---

### Criterios de evaluación (resumen)

Se valorará especialmente que:

* Se definan **al menos cuatro políticas**, incluyendo:

  * La **Política de protección del puesto de trabajo**.
  * Tres políticas adicionales coherentes con los riesgos detectados.
* Cada política tenga:

  * **Antecedentes** claros, conectados con los activos, puestos y riesgos del PDS.
  * **Objetivos** bien definidos y concretos.
  * **Puntos clave** que recojan las medidas principales.
  * Una **checklist coherente**, con nivel (B/A) y alcance (PRO/TEC/PER), y controles verificables.
* Las políticas estén **adaptadas al caso real de la empresa**, no redactadas de forma genérica.
* Se explique de forma entendible la **trazabilidad completa**:
  PDS → activos/puestos/riesgos → políticas seleccionadas → controles en checklist.

