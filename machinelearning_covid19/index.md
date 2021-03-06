# Machine Learning - Covid 19


Utiliza nuestra API en cualquier tipo de solución utilizando tecnologías en la nube como SAP Cloud Platform, Google Cloud Platform, Amazon Web Services, Heroku entre otras.

<!--more-->

## Introducción

Una vez comenzó la pandemia de Covid19, nos vimos forzados a cambiar ciertos hábitos sociales, culturales y laborales, lo cual presento diversos desafíos en el transcurso de este año 2020.

Personalmente a nivel tecnológico, nos vimos forzados a cambiar ciertos hábitos y adecuarnos a un entorno laboral desde casa. A medida que el tiempo pasaba estando confinados en nuestros hogares, surgieron nuevas necesidades para poder volver a una normalidad mas segura pese a que el virus del Covid19 todavia esta en el aire.

Las empresas se vieron obligadas por los gobiernos, a adoptar diversos protocolos de Bioseguridad para garantizar un acceso a establecimientos de comida, centros comerciales entre otros, de manera mas segura, para evitar propagar mas la pandemia.

Para no dar mas larga al asunto, quiero presentarles una solución en Machine Learning que permite analizar diversos comportamientos sociales y poder identificarlos para tomar decisiones.


{{< admonition note "Visitar documentacion completa" >}}
Si deseas visitar la pagina oficial, para ver todo lo relacionado con nuestra API de Machine Learning, te recomiendo visitar el siguiente sitio web  [New Inntech](https://www.newinntech.com) en la cual encontraras todo el detalle que se explicara en este Post.
{{< /admonition >}}

## 2 Características 

A continuacion, las caracteristicas mas fuertes, de nuestros servicios de Machine Learning, dando la tranquilidad a las personas que deseen utilizarlos, de la disponibilidad y soporte que brindamos.

### 2.1 Compatibilidad

Utiliza nuestra API en cualquier tipo de solución utilizando tecnologías en la nube como SAP Cloud Platform, Google Cloud Platform, Amazon Web Services, Heroku entre otras.

La solución en Machine Learning para Covid19 esta creada de tal manera, que puedas utilizar servicios web y realizar la integración a cualquier tipo de sistemas que poseas.

![Basic configuration preview](/images/machinelearning_covid19/Top-Programming-Languages.png "Lenguajes mas utilizados")

### 2.2 Arquitectura

Utilizamos una arquitectura completamente desacoplada, para que nuestros clientes a la hora de adquirir algún servicio de Machine Learning, puedan escalarlo en los servidores de manera rápida y fácil. 

Existen dos modelos, con el cual pueden adquirir los servicios de Machine Learning, ya sea Cloud o en un Servidor On-Premise. Actualmente todos nuestros servicios los estamos alojando en AWS debido a costo bajo y accesible para cualquier tipo de empresa bajo demanda o consumo de los servicios.

Con AWS garantizamos la disponibilidad de los servicios 7/24, permitiendo un alto rendimiento en la respuesta a cada peticion, en tan solo segundos.


### 2.3 Seguridad y acceso

Facilitamos a nuestros subscriptores, un API KEY único con el cual pueden usar todos nuestros servicios, así de simple. Adicionalmente facilitamos una Interfaz en Swagger, con la cual pueden probar la API sin la necesidad de desarrollar.

Adicionalmente también brindamos a nuestros clientes una autenticación mediante usuario y clave, con la cual una vez realicen el Login, obtendrán un Token que servira para consumir los demás servicios de Machine Learning.

{{< admonition >}}
Mas adelante, veremos el detalle de lo que se ha mencionado hasta el momento.
{{< /admonition >}}

### 2.4 Monitoreo

Estamos monitorizando constantemente los microservicios para brindar una respuesta rápida y disponibilidad para las soluciones de nuestros clientes.

Garantizamos la disponibilidad y control de errores de cada servicio web de Machine Learning, para evitar afectar cualquier tipo de implementación que nuestros clientes posean.


## 3 API MASK ML

### 3.1 Descripción

ML MASK - Es un servicio de Machine Learning que va a permitir a nuestros clientes automatizar la manera de detectar personas que tienen tapabocas puesto en su rostro, con el objetivo de tener un mayor control en un lugar determinado de que personas ingresan y que estén cumpliendo con el protocolo de Bioseguridad que afrontamos en estos tiempos de pandemia.

![Basic configuration preview](/images/machinelearning_covid19/apimask.png "Foto procesada con los servicios ML")

Nuestros servicios de ML esta construido bajo una arquitectura orientada a APIs, lo que va permitir que cualquier tipo de tecnología que soporte consumo de servicios REST, pueda acceder a nuestras funcionalidades.

Las tecnologías mas comunes que podrán integrarse con nuestros End-Points son Python, NodeJS, Java, .Net(C#,VB), C++ y tecnologias Front-End como VueJS, AngularJS, ReactJS.

Con todo este panorama, podemos llevar la inteligencia artificial a cualquier entorno delegando la parte mas compleja en nuestras APIs para el procesamiento de ML.

Nuestros microservicios, trabajan de la mano con la mejor tecnología para ofrecer una rápida respuesta en el procesamiento de una imagen dando como respuesta en poco segundos el resultado esperado con un margen de error mínimo en la mayoría de los casos.

Utilizamos los mejores Frameworks de procesamiento de imágenes y desarrollo de redes neuronales, para ofrecer modelos predictivos mas eficaces y de rápida respuesta.

Ofrecemos a nuestros clientes instancias exclusivas donde se dará respuesta rápida sin afectar rendimiento por peticiones de otros clientes, lo que nos permite garantizar una alta escalabilidad y respuesta en nuestros servicios.


Ver mas detalles [API MASK](https://ai.newinntech.com/docs/mask/)



### 3.2 Autenticación

Para consumir nuestra API de detección de tapabocas, solo es necesario tener la API KEY que proveemos al contratar nuestro servicio, y la imagen a procesar para realizar el análisis con el modelo de Machine Learning.

![Basic configuration preview](/images/machinelearning_covid19/maskapi_key.png "Autenticación con API KEY")

En caso de que se elija el método de autenticación con JWT, solo sera necesario tener un usuario y clave. Una vez la autenticación sea correcta, devolveremos un token que servira para consumir los demás servicios.

![Basic configuration preview](/images/machinelearning_covid19/maskapi_jwt.png "Autenticación con JWT")

### 3.3 Probando el servicio

Debemos de seguir los siguientes pasos utilizando la siguiente API KEY `eiWee8ep9due4deeshoa8Peichai8Eih` , la cual es de prueba y no es para uso en entornos productivos. No garantizamos con la API KEY proporcionada en esta documentación, el 100% de disponibilidad.

1. Ingresamos a la siguiente URL: `http://104.154.156.107:5000/doc/`
2. Agregamos la API KEY
3. Escogemos una imagen de nuestro equipo Windows, Linux o Mac.
4. Damos click en ejecutar.

Con lo anterior se tiene algo como lo siguiente:

![Basic configuration preview](/images/machinelearning_covid19/maskapi_howto.png "Ejempo del funcionamiento del servicio")

Una vez demos click en ejecutar, obtendremos como resultado el siguiente JSON:

```JSON
{
    basee64: "Codigo en Base64 para ser interpretado",
    mask:"Obtiene el valor 'Mask' en caso de que la persona tenga la mascara puesta",
    value:"Porcentaje de efectividad"
}
```
En caso de que deseemos probar por linea de comandos la API, pueden ingresar lo siguiente, teniendo en cuenta que deben proporcionar la ruta de la imagen:

```BASH
curl -X POST "http://104.154.156.107:5000/api/mask/apikey" -H "accept: application/json" -H "x-api-key: eiWee8ep9due4deeshoa8Peichai8Eih" -H "Content-Type: multipart/form-data" -F "images=@tapa.jpg;type=image/jpeg"
```
Teniendo claro lo explicado anteriormente, podrán integrar esta funcionalidad en diversas soluciones digitales para su negocio o compañía.

## 4 API Object ML

### 4.1 Descripción

ML OBJECT - Es un servicio de Machine Learning que va a permitir detectar diferentes tipos de objetos que se encuentren en una imagen. Esta funcionalidad es muy importante ya que el foco central es poder detectar cuantas personas hay en un lugar determinado. Esto va a permitir recopilar información del entorno y realizar estadísticas para tu negocio o compañía.

Actualmente esta funcionalidad es muy apetecida, por el tema de la pandemia actual que requiere controlar en espacios cerrados un limite de numero de personas, para no infringir las normas de Bioseguridad o normas propuestas por el gobierno.

![Basic configuration preview](/images/machinelearning_covid19/apiobject.png "Detección de objetos y personas")

### 4.2 Probando el servicio

![Basic configuration preview](/images/machinelearning_covid19/objectapi_howto.png "Ejempo del funcionamiento del servicio")

Una vez demos click en ejecutar, obtendremos como resultado el siguiente JSON:

```JSON
{
    basee64: "Codigo en Base64 para ser interpretado con el resultado",
    mask:"Obtiene el valor 'Object' en caso de detectar personas y objectos",
    value:"Porcentaje de efectividad"
}
```
En caso de que deseemos probar por linea de comandos la API, pueden ingresar lo siguiente, teniendo en cuenta que deben proporcionar la ruta de la imagen:

```BASH
curl -X POST "http://104.154.156.107:5000/api/objects/apikey" -H "accept: application/json" -H "x-api-key: eiWee8ep9due4deeshoa8Peichai8Eih" -H "Content-Type: multipart/form-data" -F "images=@people.jpeg;type=image/jpeg"
```
Teniendo claro lo explicado anteriormente, podrán integrar esta funcionalidad en diversas soluciones digitales para su negocio o compañía.

## 5 API Social Distance ML

### 5.1 Descripción

ML Social Distance - Es un servicio de Machine Learning que va a permitir detectar que personas están demasiado cerca una de la otra, con el objetivo de medir el distanciamiento social que se tiene en un lugar predeterminado y así controlar con mas asertividad las normas dictadas por el gobierno o a nivel de Bioseguridad.

![Basic configuration preview](/images/machinelearning_covid19/apisocialdistance.png "Detección de personas cercanas una de la otra")

### 5.2 Probando el servicio

Se utiliza la misma metodologia de los servicios anteriores para probar el servicio. Mostramos un ejemplo en Curl de como seria.

```BASH
curl -X POST "http://104.154.156.107:5000/api/socialdistance/apikey" -H "accept: application/json" -H "x-api-key: eiWee8ep9due4deeshoa8Peichai8Eih" -H "Content-Type: multipart/form-data" -F "images=@people.jpeg;type=image/jpeg"
```

## 6 Catalogo de servicios

Ahora bien en la siguiente imagen, veremos el catalogo completo de los servicios de ML, que disponemos para la categoria de Covid19.

![Basic configuration preview](/images/machinelearning_covid19/catalog.png "Detección de personas cercanas una de la otra")

Si desean mas detalle de como trabajamos y como desarrollamos nuestros productos, no duden en visitarnos [New Inntech](https://www.newinntech.com) <span class="emoji">:grinning:</span>
