# 🎨Cómo agregar estilos? 

Primeramente lo importamos desde react native:
import { StyleSheet } from 'react-native';

despues creo una variable, por ejemplo:

const Styles = StyleSheet.create ({
  container: {
    background: 'red'
  },
})  

y para usar esos estilos, es tan simple como agregar el atributo style a la etiqueta
y para darle el estilo de container mapeamos la variable styles a container, por ejemplo:

< View style={ styles.container }>código</View >
