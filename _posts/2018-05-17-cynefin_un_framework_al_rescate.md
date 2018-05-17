---
layout: post
title:  "Cynefin: Un framework al rescate"
date:   2018-05-17T09:00:00Z
reading: 5
image: "/assets/images/ikea_assembly_instructions.jpg"
---

![Ikea Assembly instructions ]({{ site.url }}{{ page.image }}){:.responsive}

Si, lo reconozco. **Me gusta el bricolaje y me gusta montar muebles de IKEA**. Me proporciona satisfación el ver terminado algo que poco antes era una simple caja con un montón de tornillos, tablas y una simple hoja de instrucciones. Y aunque exija poca creatividad (lo contrario podría no ser buena noticia), las propias tareas de montaje y el uso de destornilladores, martillos, alicates, llaves, etc., **siempre me hacen pasar un buen rato**. Será por el [efecto IKEA](https://es.wikipedia.org/wiki/Efecto_IKEA).

Pero el proceso, en teoría simple, no está exento de problemas. Sobre todo cuando en **una lectura o interpretación equivocada pones una pieza en el lugar incorrecto y toca dar pasos atrás**. Además se comprueba que, en la mayoría de los casos, esto no es trivial. Es probable que se haya tenido que forzar algún tornillo donde no iba y ahora, de tanto apretar y desapretar, está demasiado redondeado ... ¡Uff, esas malditas llaves allen!. Es entonces cuando antes de volver a tomar una decisión equivocada, lees con detalle (ahora sí) las instrucciones buscando algún error que indique que el problema no está en el lado de quién ha realizado el montaje. Tampoco será tan difícil. Cuestión de orgullo. Fail.

<!--more-->

En ese análisis exhaustivo descubres las caras sonrientes de los monigotes que aparecen en los dibujos, y la frustración se apodera de ti al pensar que **se suponía que ibas a pasar un buen rato**. Una, dos o tres horas (o días) después, [varios videos de youtube vistos](https://www.youtube.com/watch?v=_mTFQbaT3Zc) y algún comentario cuestionando el porqué no haberlo comprado ya montado, lo terminas.

### LAS FRUSTACIONES DEL SOFTWARE

**¿Y qué tiene que ver esto con el software?** ¿Hay algún parecido? Así de primeras, yo diría eso que en principio era fácil, puede no serlo tanto. **¿Hubiera ayudado algo tener una estimación?** Es posible, pero yo creo que en la mayoría de casos hubiera aumentado la frustración al comprobar que vas mal con respecto a lo planificado. ¿Os suena?

Y sin duda, todo puede llegar a complicarse muchísimo más si además es necesaria la ayuda de otra persona. ¡Socorro! Pero antes de llamar a mi cuñado, intentaré reflexionar sobre este tipo de situaciones a ver si encuentro algo que me rescate.

Cualquiera que haya pasado por el desarrollo de un proyecto de software, sabe que esto de la frustración forma parte del día a día. La frustración de ***"Esto tiene que estar para ayer"***, "El cliente no sabe lo que quiere", "Este proyecto es una bazofia. Vamos a hacerlo con Angular", "He probado muchas cosas pero no doy con ello", "En mi equipo funciona", "Hazlo ágil que vamos mal de tiempo", etc, etc. Comentarios que pueden escucharse en cualquier empresa como consecuencia de no entender que es natural que haya cambios en los planes previstos. Que es normal que no se tenga claro qué es lo que hay que hacerse y cómo hay que hacerlo. Que hay pocas certezas. Que la experiencia puede ser valiosa pero no garantiza resultados con éxito. Y sobre todo que **es muy importante entender el contexto**.

<figure markdown="1" class="responsive fa-pull-right">
![Cynefin Framework]({{site.url}}/assets/images/cynefin_framework.jpg)
  <figcaption>By Snowden [<a href="https://creativecommons.org/licenses/by-sa/3.0">CC BY-SA 3.0</a>], <a href="https://commons.wikimedia.org/wiki/File:Cynefin_as_of_1st_June_2014.png">from Wikimedia Commons</a></figcaption>
</figure>

### CYNEFIN FRAMEWORK

Para entener mucho mejor el contexto, podemos encontrar un salvavidas en [Cynefin](https://en.wikipedia.org/wiki/Cynefin_framework). Nos ayuda a identificar determinadas situaciones que facilitan tomar las decisiones correctas. El creador de este framework: Dave Snowden, nos dice que esas decisiones dependen del contexto (dominio) en el que estemos trabajando. Estos son:

* **Obvio**: Entornos estables con situaciones predecibles y fácilmente repetibles. Tendremos que basarnos en las mejores prácticas para dar respuesta.
* **Complicado**: No está tan claro el porqué de determinadas situaciones y expertos son los que pueden proporcionar las mejores soluciones.
* **Complejo**: No podremos saber si algo funciona hasta que se obtienen resultados. Las respuestas exigen de procesos de experimentación.
* **Caótico**: Es tan confuso que se necesitan respuestas inmmediatas para establecer un orden.
* **Desordenado**: No sabemos el contexto en el que nos encontramos y no podemos decidir la mejor forma de actuar.

Con esta información, podemos decir que **montar un mueble de IKEA es obvio, simple**, y cualquier problema encontrado puede ser producto de **ejercer mal las prácticas**. Y si hablamos de **software**, me atrevería a decir que tiene **algo de obvio, un poco de complicado y mucho de complejo**.

Hay bastante escrito sobre Cynefin y podéis encontrar referencias más precisas. Como la reciente publicación de [Jose Manuel Beas](http://jmbeas.es/): [Cómo entender y manejar la complejidad con Cynefin](http://blog.jmbeas.es/2018/05/13/como-entender-y-manejar-la-complejidad-con-cynefin/) en la que introduce una comparación con la Matriz de Stacey y pone foco en la importancia de saber el dominio en el que estamos trabajando. Pero ya puestos a citar, permitidme utilizar un ejemplo un poco más ilustrativo con uno de los trabajos que realizó Brenda Zimmerman en relación a un estudio de la complejidad en el año 2002. En ese [paper](https://www.researchgate.net/profile/Marcel_Van_Der_Watt/post/I_am_trying_to_develop_a_new_research_methodologies_to_distinguish_between_simplicity_and_complexity_Does_anyone_have_any_ideas/attachment/59d63f4a79197b807799bbcc/AS%3A426798921064448%401478768200219/download/2002_Glouberman+%26+Zimmerman_Complicated+%26+Complex+Systems.pdf), Brenda elaboró la siguiente tabla intentando explicar las diferencias entre simple, complicado y complejo:

<figure markdown="1" class="responsive">
![Simple, complicado y complejo]({{site.url}}/assets/images/simple_complicated_complex.jpg){:.responsive}
  <figcaption>By Brenda Zimmerman & Sholom Glouberman, <a href="https://www.researchgate.net/profile/Marcel_Van_Der_Watt/post/I_am_trying_to_develop_a_new_research_methodologies_to_distinguish_between_simplicity_and_complexity_Does_anyone_have_any_ideas/attachment/59d63f4a79197b807799bbcc/AS%3A426798921064448%401478768200219/download/2002_Glouberman+%26+Zimmerman_Complicated+%26+Complex+Systems.pdf">from Complicated and Complex Systems: What Would Successful Reform of Medicare Look Like?</a></figcaption>
</figure>


Simple: Seguir una receta. Complicado: Lanzar un cohete a la luna. Y **complejo: Criar un hijo**. ¡Wow! Brillante.

### YA PERO ...

¿Sabes lo que quieres hacer y cómo hacerlo? Si es que si, **simplemente sigue las mejores prácticas para obtener buenos resultados**. Si es que no, no te frustes. Estás en un contexto poco predecible y vas a necesitar experimentar. Posiblemente vas tener que realizar múltiples aproximaciones para resolver un problema. Y cuidado porque pequeños cambios pueden tener grandes consecuencias. ¿Complejo? Si, pero puede serlo más si intentas desarrollarlo cómo si fuera un mueble de IKEA. Porque **me da que seguimos pensando que un proyecto de software es complejo, pero seguimos actuando como si fuera simple o complicado**.

Pero serán sólo cosas que a mi me da ...

Dedicado a mis hijos. Perdonad mis frustraciones, nunca pensé que lanzar un cohete a la luna fuera más fácil que ser padre :)
