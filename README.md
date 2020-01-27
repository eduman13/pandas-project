# Pandas Project
## Introducción
En 1956 82 guerrilleros, entre los que se encuentran Fidel Castro y el argentino Ernesto "Che" Guevara, desembarcan en Sierra Maestra, Cuba donde empiezan una guerra de guerrillas para quitar del poder al dictador Fulgencio Batista. En 1959 después de tres años de guerra civil consigen alzarse con el poder instaurando una dictadura comunista dirigida por los hermanos Castro, Raúl y Fidel. Tuvo este hecho histórico que ver con los ataques producidos por tiburones debido al exilio cubano producido por el régimen castrista. Investigamos sobre ello.

  ![Guerrilleros Cubanos](/Imagenes/RevolucionCubana.jpg)

### Campos utilizados
Los campos utilizados para este estudio han sido Country, Area, Location, Year y Name por considerarlos los más sensibles a los intereses del estudio.

### Filtrado por Países
El primer filtrado que se ha realizado ha sido sobre la columna de países, eligiendo del DataSet los países que he considerado los más propicios para los exiliados del régimen castrista por su cercanía a Cuba. Dichos países son: Jamaica, Usa, Mexico, Bahamas, Haiti y los ocurridos en el Mar del Caribe.

### Filtrado por Area
En el caso del filtrado por areas, lo he realizado por los píases que tienen más de una costa. En este caso han sido USA filtrando por el área de Florida y Mexico por toda la costa del Mar del Caribe. Los casos de ausencia del valor Area en Mexico se han descartado al ser casos mínimos y no poder estimar donde ocurrieron.

 ### Filtrado por Año
En este caso he considerado los casos ocurridos en los siglos XIX, XX y XXI para poder establecer un antes y un después. Los casos en cuyo año era 0 se han descartado al considerar que no se pueden fechar.

### Filtrado por Actividad 
Este campo ha sido el más difícil de tratar por la variedad de descripciones. He intentado juntar actividades parecidas en actividades más globales. Se han descartado las actividades que no he considerado propias al estudio, como Surfing, deportes de agua, etc. Los registros sin valor se les ha dado el valor de "Unknown".

### Conclusiones
Han aumentado los casos de ataques de tiburón desde la década de los 60's coincidiendo con la Revolución Cubana. Pero viendo los datos no se puede atribuir a este suceso histórico, sino al aumento de prácticas deportivas acuáticas entre las que destaca el Surf por encima de las demás. Con el filtrado del campo de las Actividades tampoco se puede concluir que hayan aumentado los casos debido al exilio cubano. Investigando en los casos "Unknown" encontramos un registro de ataque de tiburon a refugiados cubanos, pero no existen más especificados.

[Aquí un link sobre ataques de tiburón a surfistas](https://www.surferrule.com/ataque-tiburon-surfista/)
