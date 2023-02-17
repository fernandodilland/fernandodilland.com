# Fernando Dilland's Website

## Instrucciones y requisitos
Para implementar el programa se requiere lo siguiente:

- Programa Laragon o Xampp (Windows) o cualquier programa para ejecutar Wordpress localmente, con acceso de preferencia al phpMyAdmin.
Descargar el último "Respaldo" del siguiente link de Google Drive: [url]
- Descomprimir la carpeta del proyecto en la carpeta raíz del programa usado para correr wordpress (ejemplo: www/) y el archivo .sql importarlo a la base de datos con el mismo nombre del proyecto.
- Una vez que se esté ejecutando la última versión del proyecto original con WordPress y su base de datos, se pueden realizar las modificaciones necesarias en el dashboard de WordPress, utilizando el usuario "admin" y la contraseña "admin". En este caso, no hay problema si el usuario y contraseña son absolutamente inseguros, ya que se va a correr solo de manera local.

Después de realizar todas las modificaciones necesarias y personalizar la página según sus necesidades, se debe generar una versión estática de la página web (con sus index.html, recursos css, js, etc) para que funcione offline y pueda ser desplegada como una página estática en Cloudflare. Esto se puede lograr con algún plugin de WordPress como Staatic. En la configuración del plugin, asegúrese de actualizar la URL de su página y ver el directorio donde se van a guardar los recursos exportados.

Una vez que se hayan exportado los archivos offline, se puede implementar la página estática siguiendo estos pasos:

- Utilice Cloudflare Pages o Github Pages (este último puede ser más lento) para implementar la página estática.
- Seleccione un dominio personalizado en Cloudflare Pages y tenga el dominio previamente registrado en Cloudflare para que la configuración se realice de manera automática.
- Suba los archivos exportados (archivos offline) a la plataforma que haya seleccionado en el paso anterior.

## Instructions and Requirements
To implement the program, the following is required:

- Laragon or Xampp program (Windows) or any program to run WordPress locally, preferably with access to phpMyAdmin.
- Download the latest "Respaldo" from the following Google Drive link: [url]
- Unzip the project folder into the root folder of the program used to run WordPress (e.g. www/) and import the .sql file into the database with the same name as the project.

Once the latest version of the original project with WordPress and its database is running, the necessary modifications can be made in the WordPress dashboard, using the "admin" user and the "admin" password. In this case, it is not a problem if the user and password are completely insecure, as it will only be running locally.

After making all the necessary modifications and customizing the page as per your needs, a static version of the web page (with its index.html, css, js, and other resources) must be generated to make it work offline and deploy as a static page on Cloudflare. This can be achieved using a WordPress plugin such as Staatic. In the plugin settings, make sure to update the URL of your page and see where the exported resources will be saved.

Once the offline files have been exported, you can implement the static page by following these steps:

- Use Cloudflare Pages or Github Pages (the latter may be slower) to implement the static page.
- Select a custom domain in Cloudflare Pages and have the domain previously registered in Cloudflare to automate the configuration process.
- Upload the exported files (offline files) to the platform you have selected in the previous step.
