# opx-pruebas
**Repositorio de pruebas del proyecto Plataforma OPx**

**Creado por**: Mauricio Sedano 03/ABR/2020 07:50

**Alimentado por**: Mauricio Sedano

**Objetivo**: Preparar y configurar un proyecto de medición para probar la Plataforma OPx 


**Principios**:

- Usar **MAYUSCULAS** para mapear MODULOS y CLASES
- Transitar de un diseño basado en MODULOS a un diseño técnico basado en CLASES
- Asignar ROL a los USUARIOS registrados
- Dibujar DIMENSION territorial a cada TAREA tipo ENCUESTA, PROYECTO e INSTRUMENTO

**Limitaciones**:

- Producto final con alcance parcial [fecha de entrega 27/MAR/2020]
- Plan de pruebas para un territorio determinado
- Plan de pruebas ajustado para a la situación de confinamiento (territorio generalizado)
- Universo de pruebas ejecutado como PROYECTISTA (ROL de usuario)[fecha de pruebas 01-02/ABR/2020]
- EQUIPOS creados con VOLUNTARIOS y VALIDADORES (ROL de usuario)
- REPORTES visibles para SUPER ADMINISTRADO (ROL de usuario)


**Contenido**:

- Aplicación Web: XLS, CSV (conjuntos de datos + formularios) + incidencias
- Aplicación Móvil Android: APK (instalador) + incidencias
- Instancia Web Kobotoolbox: gestión de recolección de datos
- Instancia Web Tasking Manager: gestión de tareas
- Instancia Web Jupyter Hub: getión de procedimientos
- Instancia Web Humanitarian Data Exchange (CKAN): gestión de conjuntos de datos

**Configuración de PROYECTOS**: (applicación Web)

1. CONTEXTOS (preparación)
- Preparar contextos
- Crear contextos
- Asignar nombre
- Seleccionar contexto y crear datos de contexto
- Cargar CSV y guardar

2. INSTRUMENTOS (preparación)
- Preparar instrumentos
- Crear instrumentos
- Asignar tipo, nombre y descripción
- Crear formulario, cargar y guardar
- Dibujar *dimension territorial*
- Seleccionar instrumento e implementar

3. USUARIOS (preparación)
- Registrar usuarios (aplicación Móvil)
- Seleccionar usuario y asignar rol (aplicación Web)

4. EQUIPOS (preparación)
- Crear equipos
- Seleccionar equipo y vincular usuarios

5. DECISIONES (preparación)
- Crear decisiones

6. PROYECTOS (configuración)
- Crear proyecto
- Asignar nombre, descripción y cantidad
- Seleccionar decisiones, contextos y equipos
- Dibujar *dimension territorial*, asignar nombre y agregar

7. TAREAS (configuración)
- Crear tareas
- Asignar nombre, tipo, cantidad, proyecto, instrmento y descripción
- Dibujar *dimension territorial*

**Ejecución de PROYECTOS**: (aplicación Móvil)

1. Iniciar de sesión (usuario registrado)
2. Habilitar GPS 
3. Navegar contextualizado
4. Listar proyectos
5. Seleccionar proyectos, tareas
6. Realizar encuesta
7. Realizar mapeo
8. Verificar producción (applicación Web)

**Gestión de CAMBIOS**: (aplicación Web)
1. Seleccionar proyecto
2. Seleccionar *dimension territorial*
3. Re-dibujar *dimension territorial* (a nivel de proyecto)
4. Re-editar tareas afectadas
5. Re-dibujar *dimension territorial* (a nivel de tarea)
6. Aceptar
