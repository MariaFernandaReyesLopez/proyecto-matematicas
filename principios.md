# PRINCIPIOS DE CODIFICACIÓN SEGURA

### ¿Qué es la codificación segura?

La codificación segura es diseñar y desarrollar software evitando las debilidades que conducen a vulnerabilidades relacionadas con la seguridad al adherirse a los estándares de seguridad especificados y las mejores prácticas de la industria.

Cuando se habla de seguridad, como en el libro Writing Secure Code los atacantes tienen una ventaja sobre los desarrolladores, y lo exponen en cuatro principios:

1. Quien defiende debe preocuparse por proteger todos los puntos; el atacante va a seleccionar solo uno, el más débil.
2. Los encargados de la defensa van a procurar defenderse de ataques conocidos; el atacante va a probar nuevas formas de llevar adelante sus ataques.
3. Quien se encarga de defender debe de estar en constante estado de vigilancia; el atacante hará su movida cuando lo crea conveniente.
4. El defensor debe respetar reglas; el atacante puede jugar sucio.
Teniendo en cuenta estos cuatro principios, se puede dimensionar lo importante que es tener un proceso de desarrollo seguro y formal en el que se tengan presentes los controles que garanticen la seguridad de la información.

Es necesario hacer un juicioso análisis de riesgos para poder enfocarse en los posibles puntos de falla. Se debe tener en cuenta los siguientes 10 aspectos:

1. Partir siempre de un modelo de permisos mínimos, es mejor ir escalando privilegios por demanda de acuerdo a los perfiles establecidos en las etapas de diseño.

2. Si se utiliza un lenguaje que no sea compilado, asegurarse de limpiar el código que se pone en producción, para que no contenga rutinas de pruebas, comentarios o cualquier tipo de mecanismo que pueda dar lugar a un acceso indebido.

3. Nunca confiar en los datos que ingresan a la aplicación, todo debe ser verificado para garantizar que lo que está ingresando a los sistemas es lo esperado y además evitar inyecciones de código.

4. Hacer un seguimiento de las tecnologías utilizadas para el desarrollo. Estas van evolucionando y cualquier mejora que se haga puede dejar obsoleta o inseguras versiones anteriores.

5. Todos los accesos que se hagan a los sistemas deben ser validados.

6. Para intercambiar información sensible utilizar protocolos para cifrar las comunicaciones, y en el caso de almacenamiento la información confidencial debería estar cifrada utilizando algoritmos fuertes y claves robustas.

7. Cualquier funcionalidad, campo, botón o menú nuevo debe agregarse de acuerdo a los requerimientos de diseño. De esta forma se evita tener porciones de código que resultan siendo innecesarias.

8. La información almacenada en dispositivos móviles debería ser la mínima, y más si se trata de contraseñas o datos de sesión. Este tipo de dispositivos son los más propensos a ser que se pierdan y por lo tanto su información puede ser expuestas más fácilmente.

9. Cualquier cambio que se haga debería quedar documentado, esto facilitará modificaciones futuras.

10. Poner más cuidado en los puntos más vulnerables, no hay que olvidar que el nivel máximo de seguridad viene dado por el punto más débil.

Finalmente, es muy importante resaltar que un atacante necesita solamente un pequeño error, una vulnerabilidad para lograr su cometido. Si dentro de la empresa se descuidan los temas de seguridad por acelerar la operatividad del negocio, se podria estar dejando la puerta abierta a que se comprometa la seguridad de la información. Ser responsables con los procesos es la mejor defensa, y no está de más preguntarse si es mejor invertir unas semanas más en desarrollo, que perder reputación y dinero en un instante por un incidente de seguridad.

## Directrices de codificación segura
Para lograr la seguridad, es muy esencial tener un 'Estándar de codificación segura' identificado para un programa desde el principio del desarrollo de la aplicación, y esto ayuda al equipo a cuidar los valores predeterminados de seguridad del software y a protegerlo de los ataques.

Es fundamental asegurarse de que todo el equipo esté Obligado a adherirse a este estándar , independientemente del lenguaje de codificación y las herramientas que estén utilizando en el programa.

A continuación se muestran algunos ejemplos que deben implementarse de forma predeterminada en el diseño de código seguro:

El acceso debe restringirse solo a usuarios autenticados y la autenticación debe implementarse en cada capa.
Los canales de comunicación deben estar cifrados para proteger los tokens de autenticación.
Todas las claves, contraseñas y certificados deben almacenarse y protegerse adecuadamente.
Es necesario implementar el cifrado de archivos, el cifrado de bases de datos y el cifrado de elementos de datos.

## Recomendaciones y reglas de codificación segura
Será bueno que el Programa defina un conjunto de 'Recomendaciones y reglas de codificación segura' que el código fuente puede ser evaluado para su cumplimiento de modo que los probadores puedan llevar a cabo la 'Pruebas de cumplimiento de conformidad' para cada uno de estos estándares de codificación segura.

Por lo tanto, el código de seguridad puede certificarse como Conforme o No Conforme usando esas reglas contra el punto de referencia establecido.

Algunas de las reglas que se mencionan a continuación se pueden usar para verificar si hay violaciones de seguridad:

Los archivos deben cerrarse cuando ya no se necesiten.
Siempre que pase una estructura a través de un límite, se debe evitar la fuga de información.
Los objetos deben declararse con una duración de almacenamiento adecuada.
Por lo tanto, los casos de prueba para verificar estas reglas deben diseñarse y llevarse a cabo para verificar el cumplimiento de la conformidad. También se identifica que la mayoría de las vulnerabilidades son causadas por errores de programación comunes típicos.

Por lo tanto, el desarrollador debe comprender 'Método de codificación inseguro' , mientras también aprenden las mejores prácticas de codificación segura. Es ideal para recopilar los errores de programación más comunes que contribuyen a las vulnerabilidades de seguridad de su aplicación para que puedan ser atendidos durante la codificación.

Estos errores de programación típicos se deben principalmente a desbordamientos de búfer, secuencias de comandos entre sitios y fallas de inyección.

