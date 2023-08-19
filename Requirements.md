# Functional requirements



| Prioridad:                                                   |                     | Dependencia: |               |
| ------------------------------------------------------------ | ------------------- | ------------ | ------------- |
| Código del requerimiento                                     | RF01                | Actor        | Administrador |
| Nombre del requerimiento                                     | Administrar usuario |              |               |
| Descripción                                                  |                     |              |               |
| El actor administrador contará con  funcionalidades CRUD (Crear, Leer, Actualizar y Eliminar) en el sistema.  Podrá crear y gestionar usuarios, incluyendo la asignación de roles y  permisos. |                     |              |               |
| Restricciones                                                |                     |              |               |
| Siempre existirá un administrador principal,  encargado de crear otros administradores |                     |              |               |

| Requerimientos funcionales                                   |                                                         |              |               |
| ------------------------------------------------------------ | ------------------------------------------------------- | ------------ | ------------- |
| Prioridad:                                                   |                                                         | Dependencia: |               |
| Código del requerimiento                                     | RF02                                                    | Actor        | Administrador |
| Nombre del requerimiento                                     | Ver los recursos para manufactura, comercio y  servicio |              |               |
| Descripción                                                  |                                                         |              |               |
| El administrador tendrá acceso a la gestión de  recursos, permitiéndole visualizar y administrar activos relevantes para la  manufactura, comercio y servicio en el centro de incubación. |                                                         |              |               |
| Restricciones                                                |                                                         |              |               |
| El administrador no podrá modificar ningún recurso  para la manufactura, comercio y servicio en el centro de incubación. |                                                         |              |               |

| Requerimientos funcionales                                   |                                                              |              |         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------ | ------- |
| Prioridad:                                                   |                                                              | Dependencia: |         |
| Código del requerimiento                                     | RF03                                                         | Actor        | Usuario |
| Nombre del requerimiento                                     | Vista de la gestion de recursos sea  (manufactura, comercio y servicio) |              |         |
| Descripción                                                  |                                                              |              |         |
| El usuario perteneciente a los sectores de  manufactura, comercio y servicio, tienen acceso a la vista de gestión de  recursos, donde se les permitirá visualizar y administrar los activos  pertinentes a sus respectivos negocios en el sistema. |                                                              |              |         |
| Restricciones                                                |                                                              |              |         |
|                                                              |                                                              |              |         |

| Requerimientos funcionales                                   |                                                 |              |         |
| ------------------------------------------------------------ | ----------------------------------------------- | ------------ | ------- |
| Prioridad:                                                   |                                                 | Dependencia: |         |
| Código del requerimiento                                     | RF04                                            | Actor        | Usuario |
| Nombre del requerimiento                                     | Crear, Leer, Actualizar y Eliminar los recursos |              |         |
| Descripción                                                  |                                                 |              |         |
| El usuario de los sectores manufactura, comercio  y servicio, en la vista recursos pueden realizar las operaciónes de, Crear,  Leer, Actualizar y Eliminar sobre los recursos asociados a sus respectivos  negocios. |                                                 |              |         |
| Restricciones                                                |                                                 |              |         |
| Solo se puede realizar el CRUD bajo la vista de  cada usuario, ningún otro Rol u usuario podrá realizar el CRUD en los  recursos pertinentes del usuario. |                                                 |              |         |

| Requerimientos funcionales                                   |                      |              |         |
| ------------------------------------------------------------ | -------------------- | ------------ | ------- |
| Prioridad:                                                   |                      | Dependencia: |         |
| Código del requerimiento                                     | RF05                 | Actor        | Usuario |
| Nombre del requerimiento                                     | Selección de recurso |              |         |
| Descripción                                                  |                      |              |         |
| El usuario debe poder seleccionar un recurso y  tener la capacidad de administrarlo. |                      |              |         |
| Restricciones                                                |                      |              |         |
| El recurso debe existir.                                     |                      |              |         |

| Requerimientos funcionales                                   |                                                         |              |         |
| ------------------------------------------------------------ | ------------------------------------------------------- | ------------ | ------- |
| Prioridad:                                                   |                                                         | Dependencia: |         |
| Código del requerimiento                                     | RF06                                                    | Actor        | Usuario |
| Nombre del requerimiento                                     | Administración de COSTOS sobre el recurso  seleccionado |              |         |
| Descripción                                                  |                                                         |              |         |
| El usuario selecciona un recurso, se abrirá una  nueva vista que le permitirá realizar operaciones Crear, Leer, Actualizar y  Eliminar sobre el recurso. La funcionalidad adicional de esta vista es que  internamente gestionará los costos asociados al recurso que el usuario está  administrando, con el objetivo de mantener un registro preciso de los costos  reales del recurso. |                                                         |              |         |
| Restricciones                                                |                                                         |              |         |
| El recurso debe existir.                                     |                                                         |              |         |

| Requerimientos  funcionales                                  |                                            |              |         |
| ------------------------------------------------------------ | ------------------------------------------ | ------------ | ------- |
| Prioridad:                                                   |                                            | Dependencia: | RNF04,  |
| Código  del requerimiento                                    | RF07                                       | Actor        | Usuario |
| Nombre  del requerimiento                                    | Visualización  del costo total del recurso |              |         |
| Descripción                                                  |                                            |              |         |
| El  usuario puede ver de forma automática el costo total del recurso cada vez que  se realice cambios en los costos individuales del recurso. |                                            |              |         |
| Restricciones                                                |                                            |              |         |
|                                                              |                                            |              |         |

| Requerimientos  funcionales                                  |                            |              |                          |
| ------------------------------------------------------------ | -------------------------- | ------------ | ------------------------ |
| Prioridad:                                                   |                            | Dependencia: |                          |
| Código  del requerimiento                                    | RF08                       | Actor        | Usuario y  Administrador |
| Nombre  del requerimiento                                    | Autenticación  del sistema |              |                          |
| Descripción                                                  |                            |              |                          |
| El  sistema debe permitir a los usuarios ingresar sus credenciales de inicio de  sesión (nombre de usuario y contraseña???) para autenticar su identidad. |                            |              |                          |
| Restricciones                                                |                            |              |                          |
| Después de la autenticación exitosa, los usuarios deben acceder  a sus respectivas cuentas y tener acceso a las funcionalidades permitidas  según su rol. |                            |              |                          |

| Requerimientos  funcionales                                  |                      |              |         |
| ------------------------------------------------------------ | -------------------- | ------------ | ------- |
| Prioridad:                                                   |                      | Dependencia: |         |
| Código  del requerimiento                                    | RF09                 | Actor        | Usuario |
| Nombre  del requerimiento                                    | Historico  de costos |              |         |
| Descripción                                                  |                      |              |         |
| El sistema debe permitir a los usuarios ver el histórico de  costos asociados a un recurso seleccionado. Los usuarios podrán acceder a una  vista que muestre una lista cronológica de todos los costos registrados para  el recurso específico. Cada entrada en el historial de costos deberá incluir  información detallada, como la fecha del registro, el tipo de costo (por  ejemplo, producción, materiales, servicios, etc.) y el monto asociado. |                      |              |         |
| Restricciones                                                |                      |              |         |
| Esta funcionalidad proporcionará una  trazabilidad completa de los costos a lo largo del tiempo |                      |              |         |

*Future add more*

# Non-functional Requirements

| Requerimientos No Funcionales                                |                  |              |                |
| ------------------------------------------------------------ | ---------------- | ------------ | -------------- |
| Prioridad:                                                   |                  | Dependencia: |                |
| Código del requerimiento                                     | RNF01            | Actor        | Software/Roles |
| Nombre del requerimiento                                     | Gestión de roles |              |                |
| Descripción                                                  |                  |              |                |
| Debe existir la asignación por roles  Administrador y Usuario, un usuario se determina como de manufactura,  comercio y servicio. |                  |              |                |
| Restricciones                                                |                  |              |                |
| Un usuario puede tener varias asignaciones:  manufactura, comercio y servicio. |                  |              |                |

| Requerimientos No Funcionales                                |                                            |              |               |
| ------------------------------------------------------------ | ------------------------------------------ | ------------ | ------------- |
| Prioridad:                                                   |                                            | Dependencia: |               |
| Código del requerimiento                                     | RNF02                                      | Actor        | Base de datos |
| Nombre del requerimiento                                     | Persistencia de la información de Usuarios |              |               |
| Descripción                                                  |                                            |              |               |
| El sistema  deberá garantizar la seguridad y confidencialidad de los datos de los  usuarios mediante una sólida capa de encriptación y medidas de autenticación,  asegurando que solo usuarios autorizados puedan acceder y manipular la  información personal. |                                            |              |               |
| Restricciones                                                |                                            |              |               |
|                                                              |                                            |              |               |

| Requerimientos No Funcionales                                |                                            |              |               |
| ------------------------------------------------------------ | ------------------------------------------ | ------------ | ------------- |
| Prioridad:                                                   |                                            | Dependencia: |               |
| Código del requerimiento                                     | RNF03                                      | Actor        | Base de datos |
| Nombre del requerimiento                                     | Persistencia de la información de Recursos |              |               |
| Descripción                                                  |                                            |              |               |
| El sistema debe contar con una base de datos  escalable y de alto rendimiento que permita almacenar y gestionar  eficientemente la información de los recursos, asegurando la integridad y  disponibilidad de los datos en todo momento |                                            |              |               |
| Restricciones                                                |                                            |              |               |
|                                                              |                                            |              |               |

| Requerimientos No Funcionales                                |                |              |             |
| ------------------------------------------------------------ | -------------- | ------------ | ----------- |
| Prioridad:                                                   |                | Dependencia: | RF07, RNF05 |
| Código del requerimiento                                     | RNF04          | Actor        | Software    |
| Nombre del requerimiento                                     | Suma de costos |              |             |
| Descripción                                                  |                |              |             |
| El sistema deberá realizar la suma de los costos  asociados a cada recurso de manera eficiente y precisa, garantizando que el  proceso de cálculo sea rápido y preciso, incluso en casos de grandes  volúmenes de datos |                |              |             |
| Restricciones                                                |                |              |             |
|                                                              |                |              |             |

| Requerimientos No Funcionales                                |                                          |           |             |
| ------------------------------------------------------------ | ---------------------------------------- | --------- | ----------- |
| Prioridad:                                                   |                                          | Relación: | RNF04, RF07 |
| Código del requerimiento                                     | RNF05                                    | Actor     | Software    |
| Nombre del requerimiento                                     | Visualización de la suma total del costo |           |             |
| Descripción                                                  |                                          |           |             |
| Debe tener un mecanismo de actualiación automática  del costo total, cada vez que se el usuario realice cambios en los costos  individuales de los recursos. |                                          |           |             |
| Restricciones                                                |                                          |           |             |
| Deben existir costos individuales en cada recurso  para la visualización del costo total |                                          |           |             |

| Requerimientos No Funcionales                                |                             |           |               |
| ------------------------------------------------------------ | --------------------------- | --------- | ------------- |
| Prioridad:                                                   |                             | Relación: |               |
| Código del requerimiento                                     | RNF06                       | Actor     | Base de datos |
| Nombre del requerimiento                                     | Capacidad de almacenamiento |           |               |
| Descripción                                                  |                             |           |               |
| Tener una gran capacidad de almacenamiento para  poder almacenar la información de los usuarios y los recursos de cada usuario |                             |           |               |
| Restricciones                                                |                             |           |               |
|                                                              |                             |           |               |

| Requerimientos No Funcionales                                |                             |           |          |
| ------------------------------------------------------------ | --------------------------- | --------- | -------- |
| Prioridad:                                                   |                             | Relación: |          |
| Código del requerimiento                                     | RNF07                       | Actor     | Servidor |
| Nombre del requerimiento                                     | Capacidad de almacenamiento |           |          |
| Descripción                                                  |                             |           |          |
| Tener el sistema a disponibilidad de los usuarios  24/7 gracias al servidor     donde se alojará. |                             |           |          |
| Restricciones                                                |                             |           |          |
| Servidor a disposición de la UPB Seccional  Bucaramanga      |                             |           |          |

| Requerimientos No Funcionales                                |                        |           |                |
| ------------------------------------------------------------ | ---------------------- | --------- | -------------- |
| Prioridad:                                                   |                        | Relación: |                |
| Código del requerimiento                                     | RNF08                  | Actor     | Datos/Servidor |
| Nombre del requerimiento                                     | Seguridad de los datos |           |                |
| Descripción                                                  |                        |           |                |
| El sistema debe contar con medidas de seguridad  robustas para proteger la confidencialidad, integridad y disponibilidad de  los datos almacenados, garantizando que solo los usuarios autorizados tengan  acceso a la información sensible. Se implementarán prácticas de encriptación  y autenticación para prevenir posibles brechas de seguridad y asegurar la  privacidad de los usuarios. |                        |           |                |
| Restricciones                                                |                        |           |                |
|                                                              |                        |           |                |

| Requerimientos No Funcionales                                |                                   |           |          |
| ------------------------------------------------------------ | --------------------------------- | --------- | -------- |
| Prioridad:                                                   |                                   | Relación: |          |
| Código del requerimiento                                     | RNF09                             | Actor     | Software |
| Nombre del requerimiento                                     | Eficiencia del Sistema de gestión |           |          |
| Descripción                                                  |                                   |           |          |
| El Sistema debe ser desarrollado de manera  eficiente para garantizar tiempos de respuesta rápidos y una experiencia  fluida para el usuario. Los procesos ejecutados, como el cálculo y análisis  de costos, deben realizarse en un tiempo razonable que no genere  insatisfacción o molestia al usuario. |                                   |           |          |
| Restricciones                                                |                                   |           |          |
| Se realizarán pruebas de rendimiento y  optimizaciones periódicas para asegurar que el sistema opere de manera ágil y  eficiente. |                                   |           |          |

| Requerimientos No Funcionales                                |                     |           |          |
| ------------------------------------------------------------ | ------------------- | --------- | -------- |
| Prioridad:                                                   |                     | Relación: |          |
| Código del requerimiento                                     | RNF10               | Actor     | Software |
| Nombre del requerimiento                                     | Arquitectura Limpia |           |          |
| Descripción                                                  |                     |           |          |
| El sistema se debe ser desarrollado siguiendo una  arquitectura limpia y utilizando patrones de diseño que permitan la  escalabilidad y facilidad de mantenimiento. Se buscará minimizar el impacto  al realizar modificaciones en el código, asegurando una separación clara  entre el servidor de aplicaciones y el servidor de bases de datos. |                     |           |          |
| Restricciones                                                |                     |           |          |
|                                                              |                     |           |          |

| Requerimientos No Funcionales                                |                                     |           |          |
| ------------------------------------------------------------ | ----------------------------------- | --------- | -------- |
| Prioridad:                                                   |                                     | Relación: |          |
| Código del requerimiento                                     | RNF11                               | Actor     | Software |
| Nombre del requerimiento                                     | Uso de herramientas de código libre |           |          |
| Descripción                                                  |                                     |           |          |
| El desarrollo del software se basará  exclusivamente en frameworks, bibliotecas y bases de datos de código libre.  Se descartarán herramientas de pago para el desarrollo y ejecución del  sistema, asegurando que todas las tecnologías utilizadas sean de acceso  gratuito y de código abierto. |                                     |           |          |
| Restricciones                                                |                                     |           |          |
|                                                              |                                     |           |          |

*Future add more*