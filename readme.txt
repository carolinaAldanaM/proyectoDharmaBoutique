Atributo srcset: define un conjunto de imágenes entre las que le permitiremos al navegador elegir, y le especificamos de que medida es cada una 

<img srcset="dog-320px.jpg 320w,
             dog-640px.jpg 640w,
             dog-1280px.jpg 1280w"
      sizes="(min-width: 768px) 50%, 
100%"
      src="dog-320px.jpg" 
alt=""
> 

srcset=”nombre archivo y tamaño de la imagen”
Nota: se usa la unidad w, no px como podría esperar. Esta es la medida real de la imagen

Sizes: Se pueden usar media queries, indicará en QUÉ tamaño DEBE quedar la imagen elegida por el navegador.

