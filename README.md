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


**Configurar PROYECTO**:

*Paso 1: Preparación*
1. Crear CONTEXTOS
- Cargar conjuntos de datos en formato CSV para HDX/CKAN (visualización de datos)
2. Crear INSTRUMENTOS
- Definir TIPO
- Definir DIMENSION TERRITORIAL (caso Encuesta)
- Cargar formularios de recolección en formato XLSX para KOBOTOLBOX/XLSFORM (caso Encuesta - creación de formularios)
3. Registrar USUARIOS
- Cargar *email* y *clave* (aplicación móvil/web - creación de usuarios)
- Asignar *rol* (aplicación web - gestión de usuarios)
4. Crear EQUIPOS
- Crear "categoria" para asignar *nombre de equipo* 
- Vincular usuarios registrados
5. Crear DECISIONES
- Crear "descripción" para *identificar la ACCION a tomar (PGD/fase 5) con los resultados conmunicados (PGD/fase 4)* a consecuencia de la ejcución del proyecto de medición

*Paso 2: Configuración*

6. Crear PROYECTO
- Nombre: P7 - Censar población
- Descripción: Registrar la cantidad de personas que realizan actividades deportivas/recreativas en un territorio determinado
- Decisiones: D1 - Identificar zonas prioritarias, D2 - Dimensionar capacidad/recursos
- Contextos: C1 - Puntos registrados, C2 - Zonas registradas
- Tipo: Medición
- Equipos: E1 - Salida Z1 3 Personas, E2 - Salida Z2 4 Personas, E3 - Cruce Z3 3 Personas, E4 - Llegada Z4 4 Persona, E5 - Intermedio Z6, E5 - Intermedio Z5, E5 - Intermedio Z7, E5 - Intermedio Z8

*Paso 2.1: Definir DIMENSION TERRITORIAL*:
- Dimensión: Zona Urbana - Cali

*Paso 3: Creación*

7. Crear TAREA
- Nombre: T1 (P2) - Contar población
- Tipo: Encuesta
- Cantidad: 4 
- Proyecto: P2 - Contar poblacion (actualizado)
- Instrumento: Zona X - Parcial Cali Urbana (actualizado)
- Descripción: Registrar  el número de el numero de mujeres, hombres, mascotas, bicicletas, motos y vehículos en tu Zona

*Paso 3.1: Definir DIMENSION TERRITORIAL*:
- Dimensión: *Sin registrar NOMBRE*
