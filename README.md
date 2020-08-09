# Oportunidades en Brubank

En Brubank estamos buscando desarrolladores Junior con ganas de aprender nuevas tecnologías y enfrentarse a nuevos desafíos. Nuestro Backend esta desarrollado en Go, pero no es un requisito que conozcas el lenguaje. Lo que nos importa es que seas curios@, te guste aprender y puedas resolver problemas sol@ y con nuestra ayuda.

Es por eso que creamos este ejercicio, que no debería tomarte más que un par de horas, pero seguramente te ayudara a aprender algunas tecnologías que te serviran ahora y en un futuro.


## El problema: los espías

La agencia de inmigración de Ruritania utiliza un servicio web para transmitir los datos de todos los viajeros que ingresan al país. En el mismo se informan en formato texto los siguientes datos:

1. Nro. de pasaporte (8 dígitos)
2. Código de país (3 dígitos)
3. Apellido (20 caracteres)
4. Nombre (20 caracteres)
5. Nro de vuelo (2 dígitos)
6. Equipaje (30 caracteres)

Ej:

```
05012657001Warren              Louis               02eum unde exercitationem rem po
49879255001Griffin             Patrick             00excepturi nam mollitia eos mol
37133477002Morris              Sharon              00package main
06293532024Fernandez           Alan                04rerum qui saepe fuga accusamus
```


### Tu misión

El gobierno de Ruritania fue alertado por la agencia de inteligencia que un grupo de espías estan intentando ingresar el código fuente de un virus a través de su equipaje.

Tu misión es detectar a los espías y conseguir el código fuente del virus. Una vez obtenido el código completo deberás ejecutarlo para obtener más instrucciones de como avanzar en el proceso de entrevistas.


### El servicio web

El servicio de inmigración de Ruritaria funciona con un websocket ubicado en: 

[ws://ruritania-immigration.herokuapp.com/immigration]

Una vez conectado al websocket podrás recibir los datos de cada viajero y detectar a los espías. Cuando descubrás a todos los espías y sus equipajes podrás correr el código fuente.

El orden del código fuente esta dado por el Nro. de vuelo de cada viajero.


### Los espías

Para detectar a un espía, tendrás que tener en cuenta las siguientes características:


Mucha suerte!!
