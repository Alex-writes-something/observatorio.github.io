---
title: "Contacto"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Por favor escribe un correo a {{site.name}}. ¡Prometemos responder pronto!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nombre*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="Correo*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Mensaje*" required></textarea>    
<input class="btn btn-success" type="submit" value="Enviar">
</form>
