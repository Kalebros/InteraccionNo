# InteraccionNo
Interaccion negativa, granada jamming

# Modo de uso

1.- Copiar el script de InteraccionNeg.cs en el directorio de Scripts del proyecto
2.- Dentro de la jerarquía, tenéis que crear un GameObject vacio, al que llamar por ejemplo
LOGICA, y asociar como componente el script de InteraccionNeg
3.- Añadir un Canvas a la escena, y dentro del Canvas incluir un Text.
4.- Hay dos propiedades en InteraccionNeg: Cam Transform y Label Neg, los cuales deben
de apuntar el primero a la Main Cam del jugador (Abrid RigidBodyFPSController y allí arrastrar
  el componente MainCamera a Cam Transform y haced lo mismo con el Text de Canvas para Label Neg)

- El script funciona cuando el usuario se acerca Y MIRA DIRECTAMENTE al objeto para luego pulsar el botón
izquierdo del ratón o la tecla F. Podéis cambiar el código de la tecla dentro del Script.

- Time Wait es una propiedad que modifica el tiempo de espera antes de que desaparezca el texto de pantalla.

Have Fun!
