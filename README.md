Link a la app: frontend-project-structure.vercel.app

𝗧𝗲𝗰𝗻𝗼𝗹𝗼𝗴𝗶𝗮𝘀
- ReactJs
- React-router-dom
- Redux
- Redux-toolkit
- Redux-saga
- Axios

En este proyecto podran observar mi forma de estructurar el Front End, el principal foco de este no es que sea algo lindo, sino algo consistente y escalable para que en base a esto podamos replicar nuestos diseños de la manera más fiel y agil posible.

Establecí un sistema donde todos los tamaños, alineaciones y espacios son múltiplos de 8, esto quiere decir que todo esta realizado a partir de 8pt para mantener la consistencia y la equivalencia entre los diferentes tamaños de forma facil.

A pesar de que me gusta usar el preprocesador Sass para facilitar algunas tareas repetitivas a la hora de dar estilos a nuestros proyectos, en este caso no se utilizó. Podemos ver el uso de variables nativas de css para todos los tamaños y tipos de fuentes, asi como para todos los colores.

No se utilzarón librerias para la creación de componentes ni para darles estilos ya que con esto puedo demostrar mi capacidad para la maquetación utilizando css flex-box y grid. 

Para implementar este diseño se usó la estrategia Mobile First y luego se adaptó a los tamaños restantes.

El proyecto incluye una configuración de Prettier para formatear el codigo y mantener la consistencia que ayuda a la ligibilidad del mismo.
