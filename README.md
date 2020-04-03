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

**Configuración de PROYECTOS**:

CONTEXTOS (preparación)
1. Preparar contextos
2. Crear contextos
3. Asignar nombre
4. Seleccionar contexto y crear datos de contexto
5. Cargar CSV y guardar

INSTRUMENTOS (preparación)
1. Preparar instrumentos
2. Crear instrumentos
3. Asignar tipo, nombre y descripción
4.  Crear formulario, cargar y guardar
5.  Seleccionar instrumento e implementar

USUARIOS (preparación)
1. Registrar usuarios
2. Seleccionar usuario y asignar rol

EQUIPOS (preparación)
1. Crear equipos
2. Seleccionar equipo y vincular usuarios

DECISIONES (preparación)
1. Crear decisiones

PROYECTOS (configuración)
1. Crear proyecto
2. Asignar nombre, descripción y cantidad
3. Seleccionar decisiones, contextos y equipos
4. Dibujar dimension territorial, asignar nombre y agregar

TAREAS (configuración)
1. Crear tareas
2. Asignar nombre, tipo, cantidad, proyecto, instrmento y descripción
3. Dibujar dimension territorial
