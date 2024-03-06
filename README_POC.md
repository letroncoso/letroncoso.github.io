## Telecom Paraguay

### Modelado de Usuario
<details>
  <summary>Esta sección detalla todos los atributos modelado en el contexto de usuario</summary>

  
</details>


### Plataforma Access Manager
<details>
  <summary>Como excluir (blacklist) un determinado Browser a momento de login Forgerock SDK</summary>

  #### Journeys
  A continuación se mencionan los journeys disponibles en la plataforma.
  
  ##### Journey de login (login)
  
  ###### Logica
Va a permitir el login por medio de linea con envio de OTP
Si el usuario no existe en el DS, va a realizar la registracion del mismo
El tree va a consumir las siguientes APIs externas (muy probablemente provistas por PePa Paraguay:
API de identidades:
Permite la busqueda de identidades por numero de telefono
Esta API tambien retornara la info del usuario. Esta informacion la podemos usar como no permitir el login por ejemplo si la linea no esta activa o no existe. Es clave la informacion que nos retorne ya que luego la usaremos para la registracion en el DS
API de envio SMS: Permite enviar SMS al numero de Telefono  
  ###### Consideraciones 
  
</details>

