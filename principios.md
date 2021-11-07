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
