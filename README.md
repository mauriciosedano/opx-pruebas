# opx-pruebas
**Repositorio de pruebas del proyecto Plataforma OPx**

**Creado por**: Mauricio Sedano 03/ABR/2020 07:50

**Alimentado por**: Mauricio Sedano

**Objetivo**: Preparar y configurar un proyecto de medición para probar la Plataforma OPx 


**Principios**:

- Transición de un diseño funcional incial basado en MODULOS a un diseño técnico basado en CLASES
- Uso de *mayusculas* para hacer referencia a **MODULOS** y **CLASES** para mapear procesos en la Documentación
- USUARIOS registrados: por defecto con rol *Voluntario*
- DIMENSION territorial: por defecto las TAREAS tipo *Encuesta* dependen de los PROYECTOS y las TAREAS tipo *Mapeo* dependen de los INSTRUMENTOS
- REPORTES: por defecto son visibles para el USUARIO tipo *Super Administrador*


**Limitaciones**:

- Producto final entregado con alcance parcial
- Plan de pruebas inicial diseñado para un territorio determinado
- Plan de pruebas ajustado para a la situación de confinamiento actual (territorio generalizado)
- Universo de pruebas ejecutado con rol de usario tipo *Proyectista*
- Equipos creados con usuarios tipo *Voluntario* y *Validador*


**Contenido**:

- Aplicación Web
- Aplicación Móvil Android
- Instancia Web Kobotoolbox: gestión de recolección de datos
- Instancia Web Tasking Manager: gestión de tareas
- Instancia Web Jupyter Hub: getión de procedimientos
- Instancia Web Humanitarian Data Exchange (CKAN): gestión de conjuntos de datos


**Configuración de PROYECTOS** (procedimiento):
*Paso 1: Preparación*
1. Crear CONTEXTOS: cargar conjuntos de datos (formato csv especifico HDX para visualización de datos)
2. Crear INSTRUMENTOS: cargar formularios de recolección (formato xlsx espeficio XLSFORM para cración de formularios)
3. Registrar USUARIOS: definir *email*, *clave*, y *rol*
4. Crear EQUIPOS: vincular usuarios registrados
5. Crear DECISIONES: identificar la ACCION a tomar (fase 5 PGD) con los resultados conmunicados (fase 4 PGD) a consecuencia de la eejcución del proyecto de medición

*Paso 2: Configuración**
6. Crear PROYECTO
- Nombre: Censar población
- Descripción: Establecer la cantidad de personas que realizan actividades deportivas/recreativas en un territorio determinado
- Decisiones
- Contextos
- Tipo: Medición
- Equipos:
- Dimensiones:


6.1 Crear DIMENSION TERRITORIAL

