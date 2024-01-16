# 1. Introducción
## ¿Que son los paquetes RPM?
RPM es un acronimo de [Redhat](https://www.redhat.com/es) Package Manager, es una herramienta que usamos como recurso en el sitema operativo Redhat o distribuciones de ella que tengan como recurso principal y herramienta de recursos principal los paquetes RPM.

Pero realmente, ¿un paquete RPM que es?, pues son los paquetes destinados a determinados sistemas operativos en el cual es como si fueran paquete .deb, pero para las distribuciones de Red Hat, como pueden ser Fedora, Mandriva, Rocky linux, etc...

Estos funcionan de manera distinta que los paquetes .deb, ya que estos requieren de otra manera para instalarlos y en el caso de que queramos instalarlo dependiendo de si son repositorios o no, hay que instalarse el paquete RPM de manera independiente(De una pagina web, no de un repositorio) y daré algunas opciones que estan disponible para paquetes RPM.

### Comandos:

`rpm -i {package.rpm}´

`rpm -u {package.rpm}´

`rpm -qa´

`rpm-qpl {package.rpm}´

`rpm -qf {path/to/file}´

`rpm -e {packag.rpm}´

`rpm -V´

`rpm -qi foo´

`rpm ql foo´

`rpm qc foo´

`rpm -q foo´

`rpm -q´
    
Nosotros, en el [caso practico](/documentos/casopractico.md) haremos un par de instalaciones y demostraciones de paquetes RPM en linux.
