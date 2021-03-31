# AWS Cloud Front

## Que es ?
Un `CDN` es un sistema de servidores distribuidos que entregan paginas web y otro tipo de contenido web a un usuario en funcion de su ubicacion geografica, origen de la pagina web y el servidor que entrega el contenido.

`Cloud Front` es un servicio de red de entrega de contenido rapido (`CDN`) que envian de forma segura los datos, videos, aplicaciones y API a clientes de todo el mundo con baja latencia y altas velocidades.

## Distribuciones:
* **Distribucion web:** Normalmente se utiliza para servicios web.
* **RMTP:** Se utiliza para la transmision de medios.

## Terminologia:
* **Edge location:** Lugar en donde se almacenara en cache el contenido tanto para lectura como para escritura.
* **Origin:** Es el origen de los archivos que distribuira el `CDN`, pueden ser: Bucket S3, Instancia EC2, ELB o Route 53. 
* **Distribution:** Es el nombre que se le da al `CDN` que posee una coleccion de ubicaciones.

## Puntos a tener encuenta:
* 136 puntos a nivel mundial.
* Ayudar a proyteger de ataques DDOS.
* Proporciona cifrado SSL.
