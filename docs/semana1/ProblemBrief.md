## Problem Brief

### Encabezado

VITAE es un software que permitirá la interoperabilidad entre diferentes entes prestadores de salud en Colombia.

### Equipo y roles

Thomas Aguirre - Director de proyecto.

### Problema y evidencia

Basado en la ley 2015 del año 2020 el gobierno Colombiano instauró y definió el alcance de la historia clínica interoperable en Colombia, a efectos prácticos, lo que permite esta ley es garantizar que entre los diferentes entes prestadores de salud se compartan las historias clínicas de los usuarios y de esta forma mejorar la prestación del servicio de salud a nivel nacional, todo esto mediado una herramienta tecnológica avalada por el ministerio de las TIC del gobierno colombiano.

### Usuario y actores

A pesar de que existe la necesidad clara de que las entidades prestadoras de salud compartan la información, el ministerio de las TIC no ha compartido información suficiente acerca de la herramienta tecnológica que mediará esta iniciativa, así que, los ciudadanos colombianos no entienden claramente cuál es el flujo de su información entre las EPS y el ministerio de salud y para una organización que genere historias clínicas no es de fácil acceso los lineamientos que debe cumplir para comenzar a interoperar las historias clínicas.

A día de hoy el ministerio de las TIC ha promovido una API para la comunicación y el almacenamiento de las mismas, actualmente, pocas entidades de salud interoperan sus historias clínicas (la gran mayoría de entidades que está totalmente interconectadas se sitúan en la capital del país) haciendo que las zonas alejadas de las grandes urbes no gocen de este beneficio. A pesar de que el lineamiento del gobierno es que esto funcione lo más rápido posible, en la práctica no ha sucedido así.

Escriban aquí su respuesta.

### Flujo actual de valor

Actualmente el flujo de información de las historias clínicas entre las diferentes entidades sucede así:

1. IPS (puesto de salud donde va el usuario a consulta)
   1.1 Servicio interno de IPS donde se almacena la información
2. EPS (Entidad que regula el trámite de prestar el servicio de salud)
   2.1 Servicio interno de EPS donde se almacena la información
3. Conversión del formato interno al formato interoperable exigido por el MinSalud y el MinTIC
3. Solicitud de envío de historia clínica
4. Recepción de historia clínica en los servidores del MinTIC
5. Consulta disponible para los demás IPS/EPS del país

Actualmente el flujo está mediado por circulares del MinTIC. 

### Fricciones identificadas

Actualmente el proceso depende totalmente del MinTIC y el MinSalud, esto hace que para agregar un nuevo ente emisor de historias clínicas tenga que pasar por un proceso burocrático y adecuación tecnológica a la arquitectura ofrecida por el MinTIC, el servicio actual puede afectar la operación en zonas alejadas de las cabeceras municipales donde aún no hay interoperabilidad de las historias clínicas.

### Oportunidad e hipótesis

BlockChain podría ayudar de forma implícita en la inmutabilidad de los registros, fácil inserción de nuevos nodos emisores de historias clínicas y como ciudadanos colombianos podríamos confiar plenamente, gracias a la tecnología, que no hay redes de corrupción que puedan mutar la información de la red, haciendo que esta de forma inherente sea segura y confiable.

### Criterio de pertinencia

1. El histórico no puede alterarse: Actualmente debemos confiar en la buena fe de los funcionarios del MinTIC/MinSalud en que la red de historias clínicas interoperables efectivamente es una red inmutable y de solo inserción, con BlockChain se evitaría esa fe ciega y los ciudadanos pueden confiar plenamente en que sus registros clínicos no serán mutados o eliminados de la red.

2. Intermediario: Actualmente la interoperabilidad de las historias clínicas pasa por las EPS, haciendo que se agregue un eslabón a la cadena que es incesario, trasladando esta interoperabilidad de forma directa a las IPS haríamos que la red sea más eficiente y rápida pues se evitan temas administrativos y tecnológicos entre la EPS y la IPS. 

### Supuestos y riesgos

1. Las historias clínicas deben ser inmutables
2. Las historias clínicas deben prevalecer en el tiempo

