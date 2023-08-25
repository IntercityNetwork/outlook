# IntercityNetwork | Errores de Sincronizacion Outlook365 ![#F2F7EC](https://w2.intercity.cl/wp-content/uploads/2023/07/logo-intercity-desktop-blanco.png) `#F2F7EC`

Desde el presente, se integran distintas soluciones para la sincronizacion el cliente Outlook **hosteados en Intercity**
1) crear un nuevo perfil en el usuario afectado.
2) registrar de forma manual con los siguientes opciones en el proceso.
   
- Servidor IMAP: exchange.hosted.intercity.cl
- puerto IMAP: 993 o 995
- Seguridad: SSL/TLS

- Servidor SMTP: exchange.hosted.intercity.cl
- puerto SMTP: 587 o 465
- Seguridad: AutoSSL

De no generar cambios en la configuracion del cliente, favor considerar los siguientes:
-ejecutar el script en la carpeta regedit/autodiscover365.reg
 - cuando se ejecute este, vamos a limpiar los registros preconfigurados en el sistema operativo, luego cerrar y abrir nuevamente la aplicacion para confirmar estado del servicio.
