# 🎨Cómo agregar estilos? 

Primeramente lo importamos desde react native:
> import { StyleSheet } from 'react-native';

despues creo una variable, por ejemplo:

> const Styles = StyleSheet.create ({
  container: {
    background: 'red'
  },
})  

y para usar esos estilos, es tan simple como agregar el atributo style a la etiqueta
y para darle el estilo de container mapeamos la variable styles a container, por ejemplo:

> <View style={styles.container}>código</View>

Para agregar estilos capaz es mejor crear un archivo styles.js y poner todos los estilos
ahí y despues importarlo en mis componentes:

> import {styles} from './styles.js'

y despues uso los estilos, ejemplo:

> <View style={styles.container}></View>
