---
#### Caracteriticas del http
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
#### Tipica Sesión Http

<p style="font-size:30px">En los protocolos basados en el modelo cliente-servidor, como es el caso del HTTP, una sesión consta de tres fases:

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
