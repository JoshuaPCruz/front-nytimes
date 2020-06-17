
# Revisión de Proyecto 

> Es más facil escribir código que leerlo.
> -Joel Spolsky (Fundador de Stack Overflow)

Los puntos que voy a tocar aquí son sobre todo para mejorar y reforzar huecos que tenemos en algunas areas.

# HTML

Para la parte de HTML los puntos que hay que recalcar son sobre todo las buenas practicas.

###  Bueno

- Uso de etiquetas de texto en el texto 
- Estructura con sentido
- Buena identación

### Malo

- Usamos demasiados `div` en varias secciones.
- Hay que usar los tags adecuados para la ocasión, por ejemplo el `div` separador, no le veo la importancia, cuando hay tags que ya hacen eso

Nos hace falta reforzar las etiquetas de HTML y las buenas prácticas.
Te recomiendo checar este repo y esta pagina para las etiquetas:
[https://github.com/hail2u/html-best-practices#escape-----and--with-named-character-references](https://github.com/hail2u/html-best-practices#escape-----and--with-named-character-references)

[https://www.w3schools.com/TAGS/default.ASP](https://www.w3schools.com/TAGS/default.ASP)

# CSS

Para esta parte lo que hay que tener en cuenta es el escalamiento de un proyecto, la redacción y el uso de las propiedades correctas

### Bueno

- Tenemos una baja especificidad en las reglas
- Buen uso de variables

### Malo

- **Utilizamos solamente `px`, eso es muy muy MALO**. Para tamaño de letra se utiliza una diferente medida (em o rem), para tamaño de cosas que tengan que ver con sus padres hay más opciones y para las que tengan que ver con el tamaño de la página hay aún más.
- No es escalable
- Todo esta en un solo archivo, debemos de poder pensar en como se puede modularizar todo.
- No tienes nada documentado

Hay que practicar, te dejo links donde puedes encontrar lo que te puse:
[https://www.w3schools.com/cssref/css_units.asp](https://www.w3schools.com/cssref/css_units.asp)
[https://css-tricks.com/guides/](https://css-tricks.com/guides/)

# CONCLUSIÓN

Debemos intentarlo más, tienes buena organización de tus carpetas, pero **no tenemos README** pero si un `npm init`, recuerda que me estas hablando con tu código, y necesitas documentarlo todo
**Debemos de seguir practicando.**
