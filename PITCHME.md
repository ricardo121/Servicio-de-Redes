---
#### Caracteriticas del HTTP
<ul>
  <li style="font-size:20px">Permite la transferencia de objetos multimedia, codificando los archivos binarios en cadenas de caracteres. El contenido de cada objeto intercambiado está identificado por su clasificación MIME

  </li>
  <li style="font-size:20px">Existen ocho verbos que permiten que un cliente pueda dialogar con el servidor.Los tres más utilizados son: GET, para recoger un objeto, POST, para enviar información al servidor y HEAD, para solicitar las características de un objeto(por ejemplo,la fecha de modificación de un documento HTML).
  </li>
  <li style="font-size:20px">Toda la comunicación entre los clientes y servidores se realiza a partir de caracteres US-ASCII de 7 bits.
  </li>
  <li style="font-size:20px">No mantiene estado. Cada petición de un cliente a un servidor no es influida por las transacciones anteriores. El servidor trata cada petición como una operación totalmente independiente del resto.
  </li>
</ul>
---
#### Tipica Sesión HTTP

<p style="font-size:25px">En los protocolos basados en el modelo cliente-servidor, como es el caso del HTTP, una sesión consta de tres fases:

</p>
<ul>  
  <li style="font-size:20px">El cliente establece una conexión TCP (o la conexión correspondiente si la capa de transporte corresponde a otro protocolo).
  </li>
  <li style="font-size:20px">El cliente manda su petición, y espera por la respuesta.
  </li>
  <li style="font-size:20px">El servidor procesa la petición, y responde con un código de estado y los datos correspondientes.
  </li>
</ul>
---


#### Cabeceras protocolo HTTP

<p style="font-size:25px">Los encabezados HTTP permiten que el cliente y el servidor pasen información adicional con la solicitud o la respuesta.
</p>
<p style="font-size:25px">Los encabezados se pueden agrupar de acuerdo con sus contextos:
</p>
<ul>  
  <li style="font-size:20px">Encabezado general : Encabezados que se aplican tanto a las solicitudes como a las respuestas, pero sin relación con los datos que finalmente se transmiten en el cuerpo.
  </li>
  <li style="font-size:20px">Encabezado de solicitud : encabezados que contienen más información sobre el recurso que se va a buscar o sobre el propio cliente.
  </li>
  <li style="font-size:20px">Encabezado de respuesta : Encabezados con información adicional sobre la respuesta, como su ubicación o sobre el servidor en sí (nombre y versión, etc.).
  </li>
  <li style="font-size:20px">Encabezado de entidad : Encabezados que contienen más información sobre el cuerpo de la entidad, como su longitud de contenido o su tipo MIME.
  </li>
</ul>
---
