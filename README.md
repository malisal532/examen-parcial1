# examen-parcial1
#Crear un servidor en docker para IIS, realizar la documentacion con evidencias(imagenes) a un repositorio en GIT, y subir la URL del repositorio 
# se entro al power sell se puso los comando pero no corria auque tenia todod instalafdo tal como me poedia chatgbt
se inyento se toda forma
# intente volver a descaegar pero por tema de timepo ya no se pudo
Verificación de Docker
#Ejecuté el siguiente comando en PowerShell para verificar si Docker estaba instalado correctamente:

"powershell"

"docker -v"
Este comando debería haber mostrado la versión instalada de Docker, pero no hubo respuesta, lo que indicaba que Docker no estaba funcionando correctamente.
Intento de Descargar la Imagen de IIS
Intenté descargar la imagen de IIS con el siguiente comando:

"powershell"

docker pull mcr.microsoft.com/windows/servercore/iis
Pero apareció el siguiente error:

perl
error during connect: Post "http://%2F%2F.%2Fpipe%2FdockerDesktopWindowsEngine/v1.47/images/crea

Esto indicaba que Docker no estaba ejecutándose correctamente.
# Intento de Verificar el Estado de Docker
Para comprobar si el servicio de Docker estaba activo, se ejecutó:

powershell
"Get-Service docker"
El resultado fue:

nginx

No se encuentra ningún servicio con el nombre 'docker'.
Esto confirmó que Docker no estaba corriendo correctamente.


#Después de varios intentos, se concluyó que la instalación de Docker estaba corrupta . La próxima acción será desinstalar y reinstalar Docker Desktop correctamente, asegurándose de que WSL 2 esté configurado si se usa Windows 10/11.
  # se trato de volver instalra todo pero el timepo ya mo se pudo
