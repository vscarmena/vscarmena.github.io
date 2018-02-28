---
layout: page
title: Contacta conmigo
permalink: /contact/
---

![Víctor Sánchez Carmena. PING?]({{ site.url }}/assets/images/victor_sanchez_carmena_contact_me.png){:.contact-me}

PING? Es un [comando](https://es.wikipedia.org/wiki/Ping) que **tiene su origen en los submarinos y sus sónares**, que envían una señal sonora para detectar si hay algún obstáculo. Si ésta vuelve, significa que hay algún cuerpo o barrera en la trayectoria de la señal emitida por el sónar. El mecanismo del comando ping es similar al que utiliza el sónar y comprueba si hay **conectividad entre dos hosts**.

Es posible que haya alguna barrera entre tu submarino y el mío, así que quizás es mejor que lo intentemos a través de las redes sociales:

{% include social.html %}{:.contact-social}

O bien puedes enviarme un mensaje a través de este formulario:

<form method="POST" action="https://formspree.io/hola@vscarmena.com">
  <label for="name"> NOMBRE </label>
  <input type="text" name="name" placeholder="Ej: Kent Beck">
  <label for="email"> EMAIL </label>
  <input type="email" name="email" placeholder="Ej: hello@kentbeck.com">
  <label for="message"> MENSAJE </label>
  <textarea rows="4" name="message" placeholder="Ej: Make it work, make it right, make it fast."></textarea>
  <button type="submit">Enviar</button>
  <input type="hidden" name="_next" value="{{ site.url }}/thanks"/>
</form>
