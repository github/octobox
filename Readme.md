Octobox 📮 Desenreda tus notificaciones de GitHub.
Octobox lo ayuda a administrar sus notificaciones de GitHub de manera eficiente para que pueda dedicar menos tiempo a administrar y más tiempo a hacer las cosas.

No pierda la pista : Octobox agrega un estado "archivado" adicional a cada notificación para que pueda marcarla como "lista". Si algo sucede en un hilo, problema o relaciones públicas archivado, Octobox lo devolverá a su bandeja de entrada.

Notificaciones destacadas: seamos honestos, probablemente no tengas un problema 'favorito', pero Octobox te permite resaltar las notificaciones importantes con una estrella para que puedas volver y encontrarlas fácilmente.

Notificaciones mejoradas : como notificaciones, pero mejor. Con estado de emisión / solicitud de extracción, estado de CI, etiquetas y más que se muestran junto con información básica de título, organización, repositorio y tipo.

Filtre todas las cosas : filtre las notificaciones por repositorio, organización, tipo, acción, estado, estado de CI y motivo, y guarde las notificaciones de los bots junto con sus etiquetas habituales, autor y asignados.

Búsqueda con filtros de prefijo : no más trucos mentales Jedi. La combinación de una amplia gama de potentes filtros de búsqueda lo ayuda a acceder directamente a la notificación que está buscando y a concentrarse en lo que necesita.

Diseñado para los guerreros del teclado : navegue, clasifique y administre sus notificaciones como un profesional utilizando atajos de teclado inspirados en Gmail para cada función, sin necesidad de mouse.

Abierto para todos : los desarrolladores de Octobox usan Octobox para desarrollar Octobox. 100% desarrollado y administrado al aire libre en GitHub bajo una licencia FLOSS.

Captura de pantalla de Octobox

Estado de la construcción Ver datos de rendimiento en Skylight Estibador Gitter OpenCollective OpenCollective Ayudantes de código abierto licencia

¿Por qué es esto una cosa?
Si administra proyectos activos en GitHub, probablemente encuentre que las notificaciones de GitHub son bastante deficientes.

Las notificaciones se marcan como leídas y desaparecen de la lista tan pronto como carga la página o ve el correo electrónico de la notificación. Esto hace que sea muy difícil estar al tanto de las notificaciones de las que aún debe realizar un seguimiento. La mayoría de los mantenedores de código abierto y el personal de GitHub terminan usando una combinación compleja de filtros y etiquetas en Gmail para administrar sus notificaciones desde su bandeja de entrada. Si, como yo, intenta evitar el correo electrónico, es posible que desee otra cosa.

Octobox agrega un estado "archivado" adicional a cada notificación para que pueda marcarlo como "hecho". Si se produce una nueva actividad en el hilo / problema / pr, la próxima vez que sincronice la aplicación, el elemento relevante se desarchivará y volverá a su bandeja de entrada.

Tabla de contenido
Empezando
Instalar en pc
Uso de escritorio
Extensión web
Requisitos
Atajos de teclado
Contribuir
Divulgación de vulnerabilidades
Nota sobre parches / solicitudes de extracción
Contribuir
Código de conducta
Derechos de autor
Empezando
Instalar en pc
¡También puedes alojar Octobox tú mismo! Consulte la guía de instalación para obtener instrucciones de instalación y detalles sobre la implementación en Heroku, Docker y más.

Uso de escritorio
También puede ejecutar Octobox localmente como una aplicación de escritorio si lo desea, utilizando Nativefier :

npm install -g nativefier
nativefier " https://octobox.io "  # O su propia URL autohospedada
Esto creará una aplicación local (.exe, .app, etc.) y la colocará en su carpeta actual, lista para usar.

Extensión web
También puede instalar la extensión web Octobox para varios navegadores . Está disponible para Google Chrome y Mozilla Firefox , pero también puede usarlo con otros navegadores que admitan extensiones web.

Requisitos
Las notificaciones web deben estar habilitadas en la configuración de GitHub para que Octobox funcione. Para recibir notificaciones de vulnerabilidad, también debe habilitarlas.

captura de pantalla 2018-11-12 a las 14 32 38

Ver hilos de comentarios
El soporte de vista de subprocesos de Octobox se encuentra actualmente en versión beta pública. Para habilitarlo, seleccione 'en octobox' en el menú 'Abrir notificaciones' en /settings.

Los hilos deben sincronizarse para poder verlos en Octobox. Algunas notificaciones seguirán mostrando el :link-external:icono de la ventana de notificación si no tienen un hilo asociado o aún tienen que sincronizar uno.

Atajos de teclado
Puede utilizar atajos de teclado para navegar y realizar determinadas acciones:

a - Seleccionar / deseleccionar todo
ro .- Actualizar lista
j - Bajar en la lista
k - Subir en la lista
s - Notificación actual de estrella
x - Marcar / desmarcar la notificación actual
yo e- Archivar notificaciones actuales / marcadas
m - Silenciar notificaciones actuales / marcadas
d - Marque las notificaciones actuales / marcadas como leídas aquí y en GitHub
oo Enter- Abrir la notificación actual en una nueva ventana
Presione ?para acceder al menú de ayuda.

Patrocinadores
¡Gracias a todos nuestros patrocinadores! 🙏[ Conviértete en patrocinador ]



Patrocinadores
Apoya este proyecto convirtiéndote en patrocinador. Su logotipo se mostrará aquí con un enlace a su sitio web. [ Conviértete en patrocinador ]

         

Contribuir
¡Por favor, hazlo! El código fuente está alojado en GitHub . Si quieres algo, abre un problema o una solicitud de extracción.

Si necesita contribuir pero no sabe por dónde empezar, eche un vistazo a los problemas etiquetados como "Se busca ayuda" .

También puede ayudar con los problemas de clasificación. Esto puede incluir la reproducción de informes de errores o la solicitud de información vital, como números de versión o instrucciones de reproducción. Si desea comenzar a clasificar los problemas, una manera fácil de comenzar es suscribirse a Octobox en CodeTriage .

Finalmente, este es un proyecto de código abierto. Si desea convertirse en un mantenedor, consideraremos agregarlo si contribuye con frecuencia al proyecto. Siéntete libre de preguntar.

Para otras actualizaciones, siga el proyecto en Twitter: @octoboxio .

Nota sobre parches / solicitudes de extracción
Bifurca el proyecto.
Haga su adición de funciones o corrección de errores.
Agregue pruebas para ello. Esto es importante para no romperlo en una versión futura sin querer.
Puede usarlo bundle exec guardsi desea que las pruebas relevantes se ejecuten automáticamente cada vez que se modifica un archivo.
Envíe una solicitud de extracción. Puntos de bonificación por ramas temáticas.
Divulgación de vulnerabilidades
Apoyamos y fomentamos la investigación de seguridad en Octobox según los términos de nuestra política de divulgación de vulnerabilidades .

Código de conducta
Tenga en cuenta que este proyecto se publica con un Código de conducta para colaboradores . Al participar en este proyecto, acepta cumplir sus términos.

Derechos de autor
Licencia GNU Affero © 2018 Andrew Nesbitt .
