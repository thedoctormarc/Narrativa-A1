# Tutorial avanzado de Probuilder (herramienta de modelado en Unity) 

Para este tutorial, he aplicado las funcionalidades que se explican en mi propia escena.

La escena se compone primeramente de formas básicas para la carretera, acera y el tronco de los árboles y postes.

Las casas están hechas a partir de un cubo y he empleado la edición de geometría para crear nuevos edges en la parte de arriba, aparte de extruir alguna cara, y así poder seleccionar vértices, moverlos y crear el tejado.

He empleado un proceso similar en el barco.

Los árboles los he planteado con el método de crear una forma poligonal customizada, vértex a vértex, visto desde arriba. Después, he extruído la cara y he conectado los vertices de modo que quedase un conjunto de hojas, el cual he duplicado y escalado unas cuantas veces.

Finalmente, he empleado los vertex colors tanto a nivel de objeto, como de caras (tejado de las casas) y de vértices (la tela entre los dos postes). 

El resultado se encuentra exportado en .obj en la carpeta "Result scene" (con un archivo .mtl aparte para materiales). 
