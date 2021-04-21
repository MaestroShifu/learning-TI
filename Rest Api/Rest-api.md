# API REST

## Que es API REST ??
* Su significado es transferencia de estado representacional.
* Es un tipo de Api que la industria utiliza.
* Maneja la comunicacion (Cliente - Servidor).
* Restfull es un servicio que utiliza api rest para comunicarse.

## Cuales son los beneficios del api rest ??
* Comunicacion simple y estandarizada.
* Son escalables y sin estado (stateless).
* Manejan alto performance y manejo de cache.

## Vamos con un ejemplo
`http://icecream.com/api/flavors`
* `api` quiere decir que estamos haciendo llamado al api desde el punto final.
* `flavors` esto se le denominan recursos en nuestra api rest.

## Sus componentes:
* **Request:** Es la solicitud que se envia del cliente al servidor.
    * Gestiona los http methods o operaciones http.
    * Se maneja el famoso `CRUD`.
        * Create -> POST.
        * Read -> GET.
        * Update -> PUT.
        * Delete -> DELETE.
    * Sus componentes son:
        * **Operaciones** Son los metodos http
        * **Endpoints** Es un punto final de nuestra api.
        * **Parametros o body** Son algunos datos que se envia por el request.
        * **Headers** Son datos especiales para nuestra api.
* **Response:** Es la respuesta que se recibe del lado del servidor.
    * Usualmente se responde con datos tipo ``JSON``.

## RestFull
Es aquel servicio web que se basa en al arquitectura ``REST``, estos servicios se basan en entregar recursos que son almacenados en el servidor y entregados cuando el cliente lo necesita.

## Arquitectura REST
Es una arquitectura de desarrollo web que puede ser utilizada por cualqueir cliente ``HTTP``, es la mas sencilla y simple ya que pueden ser ``XML`` o ``SOAP``.

* **Sus beneficios:**
    * Tiene una mayor escalabilidad.
    * Maneja un protocolo sin estado `HTTP`.
    * Presenta un conjunto de operaciones bien definidas ``Protocolo HTTP``.
    * Maneja ``URIs`` para seguir una sintaxis universal.
    * Se representa la informacion por ``hypermedios`` que son: HTML, JSON y XML.
* **URIs:** Se presentara la forma correcta del estandar.
    * http://...../fotos/12 `CORRECTO`.
    * http://...../fotos/12 `CORRECTO`.
    * http://...../usuario/231/fotos/12 `CORRECTO`.
    * http://...../fotos?fecha=octubre `CORRECTO`.
    * Deben ser unicas, no se debe tener mas de una `URI` para identificar el mismo recurso.
