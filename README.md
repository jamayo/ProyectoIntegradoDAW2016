# ProyectoIntegradoDAW2016
Proyecto aplicación web Ciclo Superior DAW

Proyecto: elaboración de sitio web de club artes marciales a nivel nacional (10 clubes)


Existía previamente un sitio web, pero el cliente quería una renovación al ser obsoleto
y dificil de mantener. La información se mostraba sin buena usabilidad.
          
          Requisitos del cliente: -sitio web bien estructurado con menus claros
                                  -apariencia amigable
                                  -información general sobre las disciplinas que imparten
                                  -información sobre actividades de los clubes asociados
                                    con sistema sencillo de publicación de actividades.
                                  -directorio de clubes
                                  -formulario de contacto con respuesta automática, con elección de
                                   email de club por parte del usuario.


sitio:  [proyecto.artesmarcialesclub.es](http://proyecto.artesmarcialesclub.es)

ojo, el sitio antiguo es www.artesmarcialesclub.es  el nuevo sitio estará activo a finales de junio.
                                   
EDICIÓN 16 JUNIO 2016 -- AMPLIACIÓN PROYECTO INICIAL  

Para complementar el proyecto inicial se elabora un anexo consistente en un CRUD de clientes

sitio:  www.toinvoice.org   está también enlazado en el proyecto, en el pie de pagina, debajo del logueo como "ENLACE A LISTADOS"

Funcionalidades:
          PHP:  
                    -TWIG como manejador de vistas.
                    -MYSQL BBDD
                    -PHP 5.6
                    -MVC  (Controller, Modelo, Vistas)
                    -SISTEMA DE LOGIN. user:  admin   pass: admin
                    
          JQUERY:
                    -DIALOG en confirmación de borrado
                    -DATEPICKER, en formulario, con formateo de fechas, inclusion directa de mes y año y en español.
                    -VALIDATE  en formularios
                    -BUSQUEDA INSTANTÁNEA registros en listados (nombre, apellido, domicilio, dni, telefono,etc)
                    -AJAX     --PAGINACIÓN
                              --BORRADO DE REGISTROS (visualización fade out)
                              --INCREMENTO/DECREMENTO DE CANTIDADES
                              
          -LAYOUT:
                    -CSS3. todo el css de maquetación esta hecho exprofeso para esta página, sin uso de framework o                  similares. Sólo se ha usado el css que requiere jquery para el dialog, validate, etc. Se ha            hecho un sistema personalizado de GRID de 20 columnas con anchos porcentuales. El motivo de            hacerlo en 20 columnas es únicamente para que se distinga de los habituales de 12, 16, 24 o            32 columnas que hay en internet. 
                    -MEDIAQUERY. se ha establecio mediaquery para pantallas anchas 1200px, tablet 768px y moviles apaisados           320px.  Para pantallas y tables se ajusta el layout. Para moviles no, se visualiza sin                 problemas (mejor en moviles de calidad) pero la funcionalidad del mantenimiento de clientes            no se prevee se realizará desde un movil. No obstante he realizado las pruebas y la                    aplicacion es totalmente operativa.
                    -CANVAS. se ha usado CHARTJS para mostrar una gráfica con consulta dinámica en BBDD.
                    
                    -MULTIMEDIA. se ha incluido un sonido al pulsar el botón de login.
                    -VECTORIALES Y FAVICON.  el logo usado tanto aqui como en el proyecto inicial esta vectorizado. Se usa en ambos favicon personalizado.
                    
          COSTE:  
                    PROYECTO INICIAL:   APRENDIZAJE WORDPRESS 50 horas
                                        ESTUDIO WEB SOBRE TEMATICA 15 horas
                                        PALETA COLORES, TIPOGRAFIAS 2 horas
                                        BUSQUEDA MATERIAL AUDIOVISUAL Y EDICIÓN 35 horas
                                        BUSQUEDA MATERIAL ESCRITO Y ELABORACIÓN 40 horas
                                        REUNIONES CON CLIENTE (BUSQUEDA DE REQUISITOS) 7,5 horas 
                                        MAQUETACIÓN Y MONTAJE WEB  160 horas
                                        TOTAL INICIAL:  309,5 horas
                    TRABAJO EIE:        ELABORACIÓN TRABAJO 10 horas
                    EXTENSIÓN DE PROYECTO: CODIFICACIÓN:  55 horas
                    
                                        total proyecto 374,5 horas
                                        
          PRECIO VENTA PROYECTO 495 euros + IVA = 599 euros.
          
          Coste desarrollo 300 euros. 
                    
                    HORAS PROYECTO (eliminando aprendizaje (60horas) 314,5 horas
                    Ratio de 1,05 euros/hora trabajada
          
