# UAB Hack 2024: Optimización de Espacios y Eficiencia Energética 🏫

## Descripción
Optimización de Espacios y Eficiencia Energética en la UAB: Reto del UAB Hack 2024 que invita a analizar y optimizar el uso de los espacios universitarios para mejorar la eficiencia energética y la sostenibilidad, utilizando datasets reales de ocupación y horarios.

---

## Índice
- [Contexto y Motivación](#contexto-y-motivación)
- [Desafíos Actuales](#desafíos-actuales)
- [El Reto](#el-reto)
- [Niveles del Reto](#niveles-del-reto)
- [Datasets](#datasets)
- [Estructura del Repositorio](#estructura-del-repositorio)
- [Instrucciones de Uso](#instrucciones-de-uso)
- [Consideraciones Técnicas](#consideraciones-técnicas)
- [Posibilidades y Sugerencias](#posibilidades-y-sugerencias)
- [Contacto Técnico](#contacto-técnico)
- [Licencia](#licencia)

---

## Contexto y Motivación
En un momento en que la sostenibilidad y la eficiencia energética son cruciales, la Universidad Autónoma de Barcelona (UAB) enfrenta desafíos significativos en la gestión y optimización de sus espacios. Este proyecto busca abordar estos desafíos mediante el análisis y la optimización del uso de los espacios universitarios, con el objetivo de mejorar la eficiencia energética y la sostenibilidad.

## Desafíos Actuales
**Consumo Energético Elevado**  
- Operación de edificios durante largas jornadas.
- Climatización de espacios independientemente de su ocupación.
- Alto coste energético en el presupuesto universitario.

**Uso Ineficiente de Espacios**  
- Aulas grandes parcialmente ocupadas.
- Espacios pequeños sobresaturados.
- Distribución desequilibrada de estudiantes.

**Impacto Ambiental**  
- Huella de carbono significativa.
- Consumo innecesario de recursos.
- Necesidad de mejoras en sostenibilidad.

## El Reto
Desarrollar soluciones innovadoras para optimizar el uso de espacios en la UAB y mejorar la eficiencia energética. Utilizando los datasets proporcionados, los participantes analizarán datos reales y propondrán estrategias que generen un impacto positivo en la institución, los estudiantes y el medio ambiente.

## Niveles del Reto

### NIVEL 1: Análisis de Ocupación
- **Objetivo**: Realizar un análisis detallado de la situación actual utilizando los datasets proporcionados.
- **Tareas**:
  - Limpieza y preprocesamiento de los datos.
  - Identificación de ineficiencias en la distribución de espacios y horarios.
  - Visualización de patrones de ocupación y uso de espacios.

### NIVEL 2: Reasignación de Grupos
- **Objetivo**: Desarrollar un algoritmo que reasigne los grupos a las aulas, optimizando el uso del espacio.
- **Tareas**:
  - Aplicar técnicas de optimización para reasignar aulas.
  - Considerar restricciones de capacidad, horarios y características de las aulas.
  - Asegurar que no haya solapamientos y que se respeten las capacidades máximas.

### NIVEL 3: Optimización Energética (Opcional)
- **Objetivo**: Incorporar el cálculo del consumo energético en la optimización y proponer medidas de ahorro.
- **Tareas (Opcionales)**:
  - Investigar y estimar parámetros energéticos relevantes.
  - Incluir variables adicionales que puedan afectar al consumo energético.
  - Proponer estrategias para consolidar clases en menos edificios y franjas horarias.

## Datasets
Los datasets se proporcionan en la carpeta `datasets/` y contienen información cruda que requiere preprocesamiento:
- `grupos.csv`
- `ubicaciones.csv`
- `caracteristicas.csv`
- `recursos_caracteristicas.csv`
- `franjas_media_hora.csv`
- `franjas_cuarto_hora.csv`
- `calendario_grupos.csv`

**Nota**: La descripción detallada de cada dataset y sus campos se encuentra en la Documentación Técnica.

## Estructura del Repositorio

- `README.md'`
- `datasets/`
-- `grupos.csv`
-- `ubicaciones.csv`
-- `caracteristicas.csv`
-- `recursos_caracteristicas.csv`
-- `franjas_media_hora.csv`
-- `franjas_cuarto_hora.csv`
-- `calendario_grupos.csv`

-- `notebooks/`
--- `script-ejemplos_analisis.ipynb`

- `docs/`

## Instrucciones de Uso

### Clonar el Repositorio
```bash
git clone https://github.com/usuario/uab-hack-2024.git
```

### Instalar Dependencias
Se recomienda crear un entorno virtual.

### Explorar los Datasets

Los datasets crudos se encuentran en la carpeta datasets/
Utilizar los notebooks de ejemplo en `datasets/notebooks/` para comenzar

### Documentación Técnica
Se proporciona documentación técnica con información clave de los datasets.

### Restricciones Importantes
Ten en cuenta las restricciones técnicas que se especifican en la documentación

### Tareas Principales

- Limpieza de Datos: Manejo de valores nulos, estandarización de formatos y validación de coherencia
- Procesamiento: Unión de datasets, cálculo de ocupación y análisis temporal
- Optimización: Reasignación de grupos y, opcionalmente, optimización energética

### Contacto Técnico
Utiliza el canal de Discord para cualquier duda técnica o el canal de mentores para solicitar ayuda.

