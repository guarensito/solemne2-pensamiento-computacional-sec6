# solemne2-pensamiento-computacional-sec6
documentación de mi proceso para la solemne 2 

## links
- p5.js

- visor pantalla completa

## Un poco de mi enfoqué para mi trabajo
![imagen](Imagenes_PensamientoC/opartinspo.webp)

Mi inspiración para este proyecto fue el Op Art, ya que considero que se puede replicar alguna obra en p5.js para que sea interactivo

- Se pueden usar distintas figuras básicas, desde geometricas y líneas.
- Colores vibrantes que llaman la atención.

## Documentación del proceso
**Primer paso** Antes de empezar mi proyecto, tuve que definir las variables que usaré durante todo el proceso (variantes globales)

```
 
 let cantidadLineas 

 let rangoInteractividad

function setup() {
  createCanvas(600, 600);
    
  strokeWeight(4);
  line(20, 40, 80, 40);
   noFill();
  
}

```

#
Al poner play, no se veía nada 

 (insertar foto) 

**Segundo paso** Para empezar a dibujar, dejé el fondo negro para una mejor visualización, y también dividí mi lienzo en cuatro cuadrantes, donde cada uno tendrá un color en especifico que irá cambiando (más adelante). Puse el comando que especificará como será el bucle y el map que me ayudará a que todo se vea uniforme.

```
  background(0);
  
  let anchoCuadrante = width / 2;
  let altoCuadrante = height / 2; 
  
  for (let i = 0; i <= cantidadLineas; i++) {
  
    let distribuir = map(i, 0, cantidadLineas, 0, anchoCuadrante);
    
```
#
 8INSERTAR FOTOOOO

##  Descripción objetiva


## Descripción conceptual


## Input / Output y sistema + Diagrama de flujo 

