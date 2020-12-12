---
layout: post
title:  "¿Por qué el testing es importante?"
date: 2020-06-08
reading: 5
image: "/assets/images/cost_to_fix_error.jpg"
---

![Cost to fix error]({{ site.url }}{{ page.image }}){:.responsive}

Cualquier persona involucrada en el desarrollo de un proyecto de software, es posible que se haya realizado esta pregunta en más de una ocasión. Además, es más que probable que la respuesta haya sido distinta por paso del tiempo, por un cambio de posición, equipo, proyecto, tecnología, empresa, etc., o simplemente por nuestros propios sesgos. Multitud de factores que hacen que el testing del software sea para algunos una experiencia realmente positiva o, por el contrario para otros, un factor más que ralentiza la velocidad en el desarrollo de software.

<!--more-->

Personalmente, mi opinión ha ido oscilando con el paso del tiempo y me he encontrado a mi mismo defender "perder" el menor tiempo posible en automatizar eso que se ha hecho ya manualmente, y a la vez defender totalmente lo contrario, cobertura de código 100% sí o sí. La realidad es que, hablar de testing y, por tanto, exponer a debate la calidad del software, es un asunto delicado y que requiere de profundidad y exije cierto grado de contextualización. Por ejemplo, **no se puede/debe tratar igual la calidad del software en una startup que en un producto con un modelo de negocio definido y rentable**. Siendo un poco más descriptivo y como dijo [Carlos Buenosvinos en la kyenote de Techne Forum 2018](https://techneforum.com/ponencias/keynote-primeros-pasos-liderando-equipos-tecnicos/) explicando [el modelo 3x de Kent Beck](https://medium.com/@kentbeck_7670/fast-slow-in-3x-explore-expand-extract-6d4c94a7539), cuando se trata de experimentar: "Don't worry, be crappy".

<figure markdown="1" class="responsive">
 ![3x Model by Kent Beck](https://sketchingscrummaster.files.wordpress.com/2018/06/3x-model-diagram.png){:.responsive}
  <figcaption>3x Model by Kent Beck, <a href="https://sketchingscrummaster.com/2018/06/11/kent-beck-the-product-development-triathlon/">Sketch by Julia @SketchingSM</a></figcaption>
</figure>



En esta situación, parece más que evidente que dejemos a un lado esto de clean code y el testing cuando se trata de explorar fórmulas de negocio o  poner en marcha [pruebas de concepto](https://es.wikipedia.org/wiki/Prueba_de_concepto) para valorar si algo puede ser simplemente viable o no desde un plano técnico. **Pero, ¿qué sucede cuándo necesitamos que ese código no sea tan *crappy*?** 

(Es decir, que sea mantenible, fiable, reusable, entendible o testeable.)

### TESTEABILIDAD

Según SQALE lo primero que debes de conseguir 

es imprescindible conocer previamente algunos conceptos que con toda seguridad cualquiera que haya participado alguna vez en un proyecto de software , pero que puedan ayudar a justificar la importancia del testing y la forma más óptima de realizarlo. Estos son:


- Código legado -> No test

- Problema del objetivo con el code coverage

### DEUDA TÉCNICA

-> SQALE

http://www.sqale.org/download


### CALIDAD


### COBERTURA DE CÓDIGO

Cobertura de código

https://blog.armesto.net/el-problema-con-el-code-coverage/

### PIRÁMIDE DE TEST

https://martinfowler.com/articles/practical-test-pyramid.html

-> Claves

- Entregar software de forma rápida y frequente sin sacrificar la calidad

- 




