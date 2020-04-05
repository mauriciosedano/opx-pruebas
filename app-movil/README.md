Aplicación móvil de la Plataforma OPx

Introducción:
- **bin**: Este directorio contiene versiones de la aplicación móvil pre-configuradas para operar con el entorno de desarrollo o con el entorno de pruebas. *Entorno de desarollo*: se refiefe al producto OPx entregado por Neuromedia que opera sobre la infraestructura de *DigitalOcean*. Este es el escenario actual sobre el cual se ejecuta el plan de pruebas. *Entorno de pruebas*: se refiere a una versión del producto entregado que opera sobre la infraestructura de *DATIC*. Sobre este escenario, aun no ha sido posible ejecutar el plan de pruebas. *Entorno de produccion*: se refiere el escenario esperado al cual se transita para configurar y ejecutar proyectos de medición y evalación. Para transitar a este entorno, Neuromedia debe cumplir con requerimeitnos de documentación exigidos por MinTIC/DATIC.  

- **opx-desarrollo.apk** Es el *nombre* del instalador de la aplicación móvil para Android de la Plataforma OPx. Esta *app* esta diseñada para vincular ciudadanos a las operaciones de *definir*, *medir* y *evaluar* del Equipo OPC - Observatorio de Paz y Convivencia. Para instalar esta aplicación, será necesario autorizar el instalador dado que es una fuente que no proviene de la tienda Google Play.

**Instrucciones**
Para colaborar con el plan de pruebas es necesario:
- Desacargar OPx: https://github.com/mauriciosedano/opx-pruebas/blob/master/app-movil/bin/2020-ABR-04/app-desarrollo.apk
- Instalar OPx.
- Abrir OPx.
- Registrar un usuario. 
- Iniciar sesión. 
- Listar proyectos. 

**Ejecutar prueba**:
- Buscar el proyecto *P7 - Censar poblacion* 
- Listar sus tareas
- Completar las tareas tipo *Encuesta*: T1 - Contar población y T4 - Valorar experiencia.
- Completar las tareas tipo *Mapeo*: T2 - Registrar puntos y T3 - Reportar ascensos.

**Resultado esperado**:
En la medida en la que competas las tareas, podrás observar cambios y te surgiran preguntas. 
- Observar cambios en: progreso, ranking, lista de tareas pendientes y lista de tareas completadas.
- Registrar toda inconsistencia observada y remitirla a *mauriciosedano@gmail.com*

**Pre-requisitos**
El alcance actual del escenario de desarrollo requiere que antes de usar la app OPx, actives la aplicación *Hosts Go*.
1. Descargar Hosts Go: https://play.google.com/store/apps/details?id=dns.hosts.server.change&hl=es_419
2. Instalar
3. Mantener activado *Hosts change switch*
4. Mantener activado *DNS change switch*
5. Configurar 
- Seleccionar *Hosts editor*
- Agregar tres registros asi:
167.99.11.18 ee.oim-opc.pre
167.99.11.18 kc.oim-opc.pre
167.99.11.18 kf.oim-opc.pre
6. Retroceder
7. Iniciar
4. Iniciar

**Manual de usuario**: https://github.com/mauriciosedano/opx-opensource-doc/blob/master/manual_USUARIO-OPx-02DIC2019.pdf
