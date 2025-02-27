<!--hide-->
# Clasificación de tarjetas utilizando el algoritmo de selección
<!--endhide-->

El "Algoritmo de Selección" es también otro ejemplo simple de cómo funcionan las computadoras al ordenar la lista de cosas. Aquí hay una explicación de 5 minutos sobre cómo funciona el algoritmo de selección:
[https://www.youtube.com/watch?v=g-PGLbMth_g](https://www.youtube.com/watch?v=g-PGLbMth_g)

<onlyfor saas="false" withBanner="false">
 
## 🌱 Cómo iniciar este proyecto

Recomendamos abrir la plantilla `vanillajs boilerplate`, utilizando una herramienta de aprovisionamiento como [Codespaces](https://4geeks.com/lesson/what-is-github-codespaces) (recomendado) o [Gitpod](https://4geeks.com/lesson/how-to-use-gitpod). Alternativamente, puedes [clonar el repositorio de GitHub](https://4geeks.com/how-to/github-clone-repository) en tu computadora local utilizando el comando `git clone`.  

Este es el repositorio que necesitas abrir o clonar:  

```sh
git clone  https://github.com/4GeeksAcademy/vanillajs-hello
```

💡 Importante: Recuerda crear un nuevo repositorio, actualizar el remoto (`git remote set-url origin <tu nueva url>`), y subir el código a tu nuevo repositorio utilizando `add`, `commit` y `push`.  

</onlyfor>

## Instrucciones

1. Crea una función que genere una lista de cartas al azar.
1. Permite que el usuario especifique cuántas cartas aleatorias debe generar el sitio web utilizando una entrada de texto.
2. Agregue un botón de "sorteo" que, al hacer clic, hace que esas cartas en el sitio web sean hermosas.
3. Agregue un botón de "clasificación" que ordene las tarjetas usando el algoritmo de clasificación `selection`.
4. Guarde todos los cambios difíciles de realizar al ordenar la lista de tareas en una nuevo array.
5. Muestra el registro completo de cambios uno encima del otro.

Así debiera verse tu aplicación:

![Bubble Sorting Cards on a website](https://raw.githubusercontent.com/breatheco-de/exercise-sorting-cards-with-select/master/preview.gif)

Pista:

1. La estrategia primero, nadie comienza a codificar la solución antes de tener una estrategia clara.
2. Apégate a tu estrategia, olvídate del stackoverflow para la estrategia.
3. Divide y conquista, intenta separar el ejercicio en ejercicios más pequeños, por ejemplo:
    - Crea el CSS y HTML codificados antes de intentar que sea dinámico, eso le dará una idea clara de qué código HTML necesita construir con su algoritmo.
    - Primero genere una matriz de tarjetas aleatorias, asegúrese de que se está generando correctamente (utilizando la consola.log) antes de intentar procesarla en el sitio web.
    - Cree una función solo para crear el HTML de UNA tarjeta y luego reutilícela para renderizar todo.
