# Proyecto de Maquetación con HTML y CSS.
Este es un proyecto que armé con **HTML y CSS** mientras voy aprendiendo como crear una página web.  
La idea fue recrear una interfaz de contador de caracteres, sin usar JavaScript, para practicar la maquetación y el diseño.

## Objetivo

El objetivo principar fue en base a un pequeño proyecto real **aprender paso a paso**:
- Cómo estructurar el HTML con etiquetas semánticas.
- Cómo organizar el CSS para que todo quede ordenado.
- Cómo usar Flexbox para alinear elementos.

El proyecto me sirvió para entender mejor cómo se arma una página.

## Tecnologías 
- HTML5
- CSS3
- Google Fonts (Space Grotesk)  
- Git y GitHub para guardar los cambios 

## Organización del HTML

Intenté que el código fuera fácil de leer:
* `<main>` para el contenido principal  
* `<section>` para agrupar la tarjeta central  
* `<h1>` para el título  
* `<textarea>` para escribir texto  
* `<label>` e `<input>` para los checkboxes  
* `<button>` para el menú y el botón "See more"  
* `<img>` para el logo y las imágenes de las tarjetas  

## Organización del CSS

Lo ordené en secciones:
1. Reset  
2. Variables de colores  
3. Body  
4. Barra superior  
5. Título  
6. Textarea  
7. Controles  
8. Tarjetas de estadísticas  
9. Letter Density  
10. Responsive  

Usar variables en `:root` me ayudó a no repetir colores y mantener todo consistente.

## Decisión de diseño

El color de la tarjeta y del textarea fueron invertidos respecto a la paleta sugerida por la consigna. Fue una decisión estética propia para lograr mayor contraste visual entre el fondo del diseño que es mas oscuro que el área de texto. Así también apliqué bordes redondeados q la card, ya que personalmente me genera un mejor atractivo visual. 

## Flexbox

Flexbox me ayudó a:
* Alinear el logo y el botón en la barra superior.  
* Poner las tarjetas en fila.  
* Distribuir los controles.  
* Armar las barras de densidad de letras.  

Al principio me costó, pero con prueba y error lo fui logrando.

## Cómo resolví la sección Letter Density

Para las barras de progreso usé divs estilizados. Cada barra tiene un contenedor gris de fondo y un elemento interno de color violeta cuyo ancho representa el porcentaje de cada letra. Investigué distintas opciones como `<progress>` y `<meter>`, pero finalmente me quedé con los divs porque me daban más control visual.

## Responsive

Agregué un media query para pantallas chicas:
* Las tarjetas pasan de fila a columna.  
* El título se achica para que se lea mejor.  Probé el diseño con las herramientas del navegador simulando iPhone SE, iPhone 12 Pro e iPad Air.

## Dificultades

* Mantener el HTML ordenado.  
* Que las tarjetas se vieran proporcionadas.  
* Ajustar espacios entre elementos.  
* Entender Flexbox.  
* Adaptar el diseño a móvil sin romper el de escritorio.  
* Usar tipografía de Google Fonts.  

Todo lo fui resolviendo con práctica y comparando con el diseño original.

## Git y GitHub

Fue la primera vez que trabajé con commits de forma progresiva y fue todo un aprendizaje en sí mismo.

Siendo autocrítico, los primeros commits fueron algo desordenados, todavía estaba encontrando el ritmo. Pero a medida que avancé creo que los mensajes se fueron volviendo más claros y descriptivos. Es algo natural cuando uno está empezando, y estoy seguro de que con la práctica va a ir saliendo cada vez mejor, al igual que el proyecto en sí.
