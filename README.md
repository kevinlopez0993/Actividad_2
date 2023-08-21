# Sistema de Ventas
Taller de productividad basada en herramientas tecnológicas Fase IV : Resultados
***
## Tabla de contenido
#### README
[Descripción del programa](#Descripción-del-programa)

[Problema identificado](#Problema-identificado)

[Solución](#Solución)

[Arquitectura](#Arquitectura)

[Descripción sus componentes](#Descripción-sus-componentes)

[Datos de la empresa](#Datos-de-la-empresa)
***
### WIKI
<a name="Home"></a>
[Home](https://github.com/kevinlopez0993/Actividad_2/wiki)
***
<a name="Descripción-del-programa"></a>
## Descripción del programa
Es un sistema que permite la entrada al sistema web, tanto administrador como vendedor y usuario.
<a name="Problema-identificado"></a>
## Problema identificado
La microempresa no contaba con la pagina web y esta queria tener un mayor alcance a más usuarios para ofrecer sus productos y así poder aumentar sus ventas.
***
<a name="Solución"></a>
## Solución 
Al conocer el probelma que esta empresa enfrenta, se le solicta la autorizacion para poder realizar la pagina o proyecto para llevar acabo el control de las ventas desde un administrador, con esto el puede agregar y quitar productos que se vendan en dicha tienda
asi como seguridad en la interfaz yaque para poder acceder se tiene que loguerar en un login. 
***
## Arquitectura
El usuario solicita un Request que será enviado al servidor de aplicación mediante el uso de Apache Tomcat, donde se conectara con la base de datos MySQL para solicitar la opción, la Base de datos MySQL almacenara la información y responder al usuario.
***
<a name="Descripción-sus-componentes"></a>
## Descripción sus componentes
1.	Administrador: El administrador debe ingresar los datos solicitados para darse de altapara poder acceder al sistema.
2.	Producto cargo: Debe tener información del codigo, nombrecargo y estado, para dar de alta un producto.
3.	Base de datos: Utilizaremos una MySQL para ingresar la información obtenida del usuario y producto para ser almacenados. 
