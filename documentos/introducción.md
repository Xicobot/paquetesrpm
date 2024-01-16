# 1. Introducción
## ¿Que son los paquetes RPM?
RPM es un acronimo de [Redhat](https://www.redhat.com/es) Package Manager, es una herramienta que usamos como recurso en el sitema operativo Redhat o distribuciones de ella que tengan como recurso principal y herramienta de recursos principal los paquetes RPM.

Pero realmente, ¿un paquete RPM que es?, pues son los paquetes destinados a determinados sistemas operativos en el cual es como si fueran paquete .deb, pero para las distribuciones de Red Hat, como pueden ser Fedora, Mandriva, Rocky linux, etc...

Estos funcionan de manera distinta que los paquetes .deb, ya que estos requieren de otra manera para instalarlos y en el caso de que queramos instalarlo dependiendo de si son repositorios o no, hay que instalarse el paquete RPM de manera independiente(De una pagina web, no de un repositorio) y daré algunas opciones que estan disponible para paquetes RPM.

### Comandos:


rpm -i {package.rpm}
rpm -u {package.rpm}es utilizado para actualizar los paquetes de software.
    rpm -qa : comando te arrojará una lista de todos los paquetes instalados en los sistemas operativos.
    rpm-qpl {package.rpm} : ofrece la lista de archivos proporcionados por un paquete instalado para instalar RPM.
    rpm -qf {path/to/file} : determina el paquete que posee un archivo.
    rpm -e {packag.rpm} : este comando elimina un paquete instalado, pero deja los archivos de configuración.
    rpm -V : comando que cumple la función de verificación de un paquete.
    rpm -qi foo : se encarga de mostrar información acerca de un paquete RPM.
    rpm ql foo : este comando lista los ficheros de un paquete RPM instalado.
    rpm qc foo: muestra la lista de ficheros de configuración.
    rpm -q foo: muestra el nombre del paquete, la versión y el número de lanzamiento del paquete foo instalado en el sistema.
    rpm -q : consulta a la base de datos de paquetes instalados.
    
Nosotros, en el [caso practico](/documentos/casopractico.md) haremos un par de instalaciones y demostraciones de paquetes RPM en linux.
