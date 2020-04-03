# opx-pruebas
**Repositorio de pruebas del proyecto Plataforma OPx**

**Creado por**: Mauricio Sedano 03/ABR/2020 07:50

**Alimentado por**: Mauricio Sedano

**Objetivo**: Preparar y configurar un proyecto de medición para probar la Plataforma OPx 


**Principios**:

- Transitar de un diseño basado en **Modulos** a un diseño basado en **Clases**
- Usar **MAYUSCULAS** para mapear **Modulos** y **Clases**
- Asignar ROL a los USUARIOS registrados
- Dibujar DIMENSION territorial a las TAREAS tipo *Encuesta*, los PROYECTOS y los INSTRUMENTOS

**Limitaciones**:

- Producto final con alcance parcial
- Plan de pruebas para un territorio determinado
- Plan de pruebas ajustado para a la situación de confinamiento (territorio generalizado)
- Universo de pruebas ejecutado como PROYECTISTA (ROL de usuario)
- EQUIPOS creados con VOLUNTARIOS y VALIDADORES (ROL de usuario)
- REPORTES visibles para SUPER ADMINISTRADO (ROL de usuario)


**Contenido**:

- Aplicación Web: XLS, CSV (conjuntos de datos + formularios) + incidencias
- Aplicación Móvil Android: APK (instalador) + incidencias
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
4. Crear formulario, cargar y guardar
5. Seleccionar instrumento e implementar

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

**Ejecución de PROYECTOS**:

1. Inicio de sesión
2. Listar proyectos
3. Seleccionar proyectos, tareas
4. Realizar encuesta
5. Realizar mapeo
