# CONCEPTOS DE WEB SERVICES
### ¿Qué son los WEB service?

De acuerdo con García:

"Un web service es una vía de intercomunicación e interoperabilidad entre máquinas conectadas en Red. En el mundo de Internet se han popularizado enormemente, ya se trate de web services públicos o privados. Generalmente, la interacción se basa en el envío de solicitudes y respuestas entre un cliente y un servidor, que incluyen datos. El cliente solicita información, enviando a veces datos al servidor para que pueda procesar su solicitud. El servidor genera una respuesta que envía de vuelta al cliente, adjuntando otra serie de datos que forman parte de esa respuesta. Por tanto, se puede entender un servicio web como un tráfico de mensajes entre dos máquinas."

Por otro lado, un web service facilita un servicio a través de Internet: se trata de una interfaz mediante la que dos máquinas (o aplicaciones) se comunican entre sí. Esta tecnología se caracteriza por estos dos rasgos:

1. Multiplataforma: cliente y servidor no tienen por qué contar con la misma configuración para comunicarse. El servicio web se encarga de hacerlo posible.
2. Distribuida: por lo general, un servicio web no está disponible para un único cliente, sino que son diferentes los que acceden a él a través de Internet.

Cuando se utiliza un web service, un cliente manda una solicitud a un servidor, desencadenando una acción por parte de este. Posteriormente, el servidor devuelve una respuesta al cliente.

* **SOAP:** es un protocolo que define cómo deben de realizarse las comunicaciones entre máquinas. SOAP usa XML como lenguaje de intercambio de datos con una estructura compleja que es capaz de albergar todo tipo de datos sobre la solicitud o respuesta generada.
* **REST:** usa el propio protocolo HTTP para la comunicación entre máquinas. HTTP es ampliamente soportado por todos los sistemas y de hecho para la transferencia de datos en la web se usa HTTP.
se caracteriza por no tener estado. Es decir, el servidor no es capaz de recordar el estado de la anterior solicitud REST que pudo, o no, hacer un cliente. Por ello, el cliente tiene que enviar en cada solicitud todo el estado de su sesión, lo que se suele hacer mediante un token que le *ayude a recordar* al servidor.

## XML vs JSON
Para los sistemas de comunicación entre máquinas se requiere una serie de características, básicamente marcadas porque las máquinas implicadas en la comunicación pueden tener sistemas muy diferentes. Pueden usar lenguajes de programación o bases de datos diferentes y hasta los sistemas operativos suelen ser distintos entre clientes y servidores. Por ello, para la comunicación de los datos se usa básicamente lenguajes escritos en archivos de texto plano.

* **XML:** está basado en etiquetas, como HTML. Es más tradicional pero también es un lenguaje más avanzado, que presenta diversas utilidades para su extensión, validación de la información y sintaxis de los datos, etc.
* **JSON:** es un lenguaje más nuevo, basado en sintaxis Javascript. Generalmente, es más ligero y requiere mucho mejor carga del servidor para su procesamiento.
