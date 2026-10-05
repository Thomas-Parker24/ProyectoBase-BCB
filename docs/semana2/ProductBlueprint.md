Todas las historias de Thomas Aguirre. md

Propuesta de valor: 

El usuario emisor elegiría VITAE gracias a que el proceso de cargue inicia directamente en el emisor, los
ciudadanos colombianos podemos confiar ciegamente en que la red es inmutable y segura; los emisores podrían confiar en la lectura 
de las historias clínicas emitidas por otras entidades gracias a que pueden confirmar su legitimidad en dos modos, mediante la 
firma única del MINSalud y la firma única del emisor real.  

Flujo de usuario:

Ciudadano llega a consulta → 
IPS lo recibe y genera la historia clínica → 
Se genera el documento en el servicio interno de la IPS → 
Se formatea el documento a lo exigido por la red →
Se envía el documento a la red firmado por el emisor → 
MINSalud valida el documento y verifica su autenticidad firmandolo nuevamente →
El documento hace parte de la red y está disponible para los demás nodos.

Los roles necesarios en el flujo son:

1. Emisor de historias clínicas
2. Verificador de historias clínicas (MINSalud)
3. Visualizador de historias clínicas

Alcance del MVP:

El MVP será una parte parcial de la solución final donde solo existirán los nodos emisores y verificadores en la red, haciendo 
que solo se puedan emitir historias clinicas y verificar su autenticidad con los nodos verificadores, a pesar
de que el producto será acotado tendrá en su esencia el motor que será usado en el producto final debido a que la parte esencial
es la interoperabilidad de información.

Lean Canvas:
https://tecnologicodeantioquia-my.sharepoint.com/:i:/g/personal/thomas_aguirre_correo_tdea_edu_co/IQB-msVuw0EtQo_kVq1uOULiAU-sRIGCNEJU4ITHST4_U7Q?e=4DexQC

Backlog priorizado (Kanban): https://github.com/users/Thomas-Parker24/projects/1/views/1

Arquitectura inicial: 

La IU que usan los emisores les solicitá la historia clínica en el formato específico, una vez se cargue la información y se 
debe cargar el archivo en los servidores de archivos cargando el link de acceso permanente al archivo, tan pronto  
suceda lo anterior, el archivo se intenta subir a la red blockchain para que los demás nodos decidan agregar o no el archivo a la red, 
finalmente tan pronto los nodos lo decidan agregar debe haber una segunda firma por parte del nodo verificador del 
MINSalud para confirmar su legitimidad.

Uso de Stellar y justificación: Estellar cumplirá el rol de prestador de servicios BlockChain, donde se usará la infraestructura
de la red BlockChain para que crear una nueva red privada solo disponible entre emisores y el nodo verificador.


