# IntercityNetwork | Errores de Sincronizacion Outlook365 ![Logo - IntercityNetwork](https://github.com/intercitynetwork.png)

Microsoft genero cambios del motodo de autenticacion entregando mas seguridad para conectar a su plataformas de Microsoft 365.-
Este cambio significo que todos los servicios **Hosteados On-Premises** en la actualidad tengan que generar cambios adicionales para sincronizacion desde el aplicativo de Outlook 365, aqui entregamos la configuracion para que puedas registrar a tus servicio Hosteados de forma local sin inconvenientes.

**Descarga el asistente para soporte y recuperacion de Microsoft SARA**
enlace de descarga: aka.ms/sara
- Este asistente nos ayudara a entender de forma detalla el estado actual del servicio, favor descargar e instalar con permisos de administrador.
> [!IMPORTANT]
> Este procedimiento debe ser aplicado una vez ya instalado el programa SARA.

CONFIGURACION MANUAL CLIENTE EXCHANGE ONPREMISES INTERCITY 
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
