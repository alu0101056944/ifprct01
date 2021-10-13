## Práctica 1 Interfaces Inteligentes

Marcos Jesús Barrios Lorenzo (alu0101056944)

![Unity practica 1](assets/gif.gif)

### Trabajo realizado


Se agregó un terreno con texturas, árboles y arbustos usando paquetes de la asset store. Un controlador en primera persona permite navegar el terreno. Tras agregar un cubo como referencia para el atajo Ctr+F, se comenzó a diseñar el punto de interés en el terreno.


Se agregaron cuatro modelos 3D de piedras, descargados de la asset store. Uno de ellos compuesto por dos modelos a su vez. Se descargó el modelo 3D de una casa abandonada, a la cual se le agregó una malla de colisión para simular las paredes. El interior de la casa es adornado con un taburete en el centro con una fuente de luz naranja a modo de foco. Para complementar el foco, la intensidad del sol fue reducida, simulando una hora del día más avanzada.


Las siguientes etiquetas fueron agregadas:


- Sun
- Chair (taburete)
- SampleBox (caja de referencia para el atajo Ctr+F)
- Building (casa)
- BigStone (objeto compuesta por dos modelos de piedra)
- SmallStone
- LightBulb (foco en el interior de la casa)
- Terrain


Un objeto vacío GlobalScripts contiene el script encargado de logear a consola los objetos que usados que contienen una etiqueta (Los que no tienen etiqueta son hijos de otros objetos).


### Paquetes Utilizados


- Modular First Person Controller
- Old Building
- Realistic Tree 9 [Rainbow Tree]
- Stone
- Terrain Textures Pack Free
- Tughues Free Bushes
- Ice Shader - Tutorial