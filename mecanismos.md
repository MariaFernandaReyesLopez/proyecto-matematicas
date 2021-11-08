# LOS MECANISMOS DE AUTENTICACIÓN REMOTA
### ¿Qué es la atenticación?

La autenticación es una manera de controlar el acceso cuando los usuarios intentan acceder a un sistema remoto. La autenticación se puede configurar en el nivel del sistema y en el nivel de red. Después de que un usuario haya obtenido acceso a un sistema remoto, la autorización es una manera de limitar las operaciones que el usuario puede realizar.

La autenticación de clientes de acceso remoto es una cuestión de gran importancia para la seguridad.

El protocolo de autenticación extensible (EAP )

- Mecanismo de autenticación arbitrario, valida las conexiones de acceso remoto.

- Es una estructura de soporte, no un mecanismo específico de autenticación.

- Desarrollado a la demanda de métodos de autenticación que utilizan dispositivos de seguridad: Tarjetas inteligentes, de identificación, calculadora de cifrado, calculadora de cifrado.

- EAP-MOS CHAAP: Utiliza el mismo protocolo de desafío mutuo que CHP basado en PPP, usado para autenticar credenciales de los clientes.

- EAT-TLS: Tipo de seguridad del nivel de transporte, utilizada en entornos de seguridad basados en certificados. Utilizadas en : tarjetas inteligentes.

- EAP-RADIUS: No es un tipo de seguridad EAP, al contrario es el paso de cualquier tipo EAP, a un servidor RADIUS realizada por un autenticador de mensajes EAP.

- Protocolo de Autenticación por desafío mutuo de Microsoft(MS-CHAP) Protocolo de autenticación de contraseñas de cifrado no reversible. Funciona:

      1. Autetificador envía al cliente remoto el acceso remoto.
      2. Envía la respuesta, que contiene el nombre del usuario y un cifrado.
      3. El autentificador comprueba la respuesta y si es valida se autentifica.

- MS-CHAP version 2: Proporciona seguridad de alto nivel para las conexiones de acceso remoto, mejorando problemas de la versión anterior, como autenticación unidireccional. Funciona:

      1. El autenticador (el servidor de acceso remoto o el servidor IAS) envía un desafío al cliente de acceso remoto que consta de un identificador de sesión y una cadena de desafío arbitraria. Envía la respuesta, que contiene el nombre del usuario y un cifrado.
      2. El cliente de acceso remoto envía una respuesta.
      3. El cliente de acceso remoto comprueba la respuesta de autenticación y, si es correcta, utiliza la conexión.
