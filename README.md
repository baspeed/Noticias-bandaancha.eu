# Noticias-bandaancha.eu
Aplicación Android para ver las 10 últimas noticias del portal bandaancha.eu

Hacen falta dos librerías de dominio publico instaladas en el IDE para que funcione correctamente

* DzHTMLText (https://github.com/digao-dalpiaz/DzHTMLText)
* FMXComponents (https://github.com/zhaoyipeng/FMXComponents)

También hacen falta los archivos para poder acceder mediante SSL a las páginas web (desde Android 6 no se permite OpenSSL). Los podéis coger del siguiente enlace y cambiando su ruta en las opciones de Deployment de Delphi:

* Librerias SSL para Indy Components de Delphi: https://indy.fulgan.com/SSL/OpenSSL%201.0.2g%20Android.zip

Si queréis publicar la app en modo Debug no os hará falta ningún archivo KeyStore, pero si publicáis una versión Release (para la Play Store) entonces tendréis que tener una clave KeyStore de Google, que únicamente se da cuando la persona se apunta al programa de desarrolladores de Google, pagando una cuota de unos 15€ más o menos. En las opciones de Deployment de Delphi podéis poner vuestro archivo junto con el alias y la contraseña que hayáis elegido.

Las releases que se publicarán en este repositorio serán en modo Debug, para que podáis obtener el archivo .APK que permite instalar la aplicación en cualquier teléfono o tablet, dando los permisos adecuados para poder instalar la aplicación.
