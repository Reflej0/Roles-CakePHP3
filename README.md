# Roles-CakePHP3
Como crear un sistema de roles en CakePHP3 para que distintos usuarios tengan acceso a distintas funciones.

# Resumen
Como implementar un Control de Acceso basado en Roles en CakePHP3, gracias a un plugin: www.github.com/CakeDC/users En el ejemplo de este repositorio se implementa el plugin con la finalidad de tener usuarios con rol de usuario los cuales solo pueden tener acceso a las recetas e ingredientes y otros usuarios con el rol de cocinero, los cuales pueden además editar, agregar o modificar recetas y/o ingredientes.

# A tener en cuenta
La implementación es sencilla, lo importante es: que en /config se encuentran dos archivos permissions.php y users.php los cuales establecen la configuración de los usuarios y sus permisos. Al implementar un plugin, los modelos, controlador y templates(vistas) de Usuarios no están por defecto en el directorio /src sino en la carpeta vendor/cakeDC

# Instalacion
Para probar este ejemplo, se necesita tener instalado y activado el XAMPP con sus módulos Apache y MySQL. Se recomienda utilizar NetBeans para la administración del directorio de archivos. El archivo vendor.zip se debe descomprimir. Descarga opcional: http://www.mediafire.com/file/t6bylqytgx3wz8r/cakerbac.zip *Ademas se adjunta una base de datos de prueba en el directorio bd con algunos registros de prueba.

# Version ONLINE
Para observar el ejemplo sin necesidad de instalar: www.reflejo.epizy.com/cakerbac
