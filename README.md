# Intercity | Errores de Sincronizacion Outlook365 
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/25423296/163456776-7f95b81a-f1ed-45f7-b7ab-8fa810d529fa.png">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
  <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="https://user-images.githubusercontent.com/25423296/163456779-a8556205-d0a5-45e2-ac17-42d089e3c3f8.png">
</picture>

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
