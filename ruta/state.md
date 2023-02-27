# State:

Lo importo con esta línea de código: 

> import React, { useState } from ‘react’;

Creo una const: 

> const [name, setName] = useState(’Asa’);

y lo puedo utilizar en este caso:

> <Text>My name is {name}</Text>

y me va a mostrar en la app “My name is Asa”

Cambiando el estado de name:

creo una const:

> const onClickHandler = () ⇒ {
  setName(’Milena’)
}

y por ejemplo si tengo un botón, al clickearlo me va a cambiar el nombre Asa por Milena:

> <Button onPress={onClickHandler}></Button>

Sigo con estilos
