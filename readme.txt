Atributo srcset: define un conjunto de im�genes entre las que le permitiremos al navegador elegir, y le especificamos de que medida es cada una 

<img srcset="dog-320px.jpg 320w,
             dog-640px.jpg 640w,
             dog-1280px.jpg 1280w"
      sizes="(min-width: 768px) 50%, 
100%"
      src="dog-320px.jpg" 
alt=""
> 

srcset=�nombre archivo y tama�o de la imagen�
Nota: se usa la unidad w, no px como podr�a esperar. Esta es la medida real de la imagen

Sizes: Se pueden usar media queries, indicar� en QU� tama�o DEBE quedar la imagen elegida por el navegador.

