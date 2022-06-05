---
layout: page
title: Kontakt
permalink: /kontakt
comments: false
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Sende uns gerne eine Nachricht. Wir antworten so schnell wir können!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Name*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="E-mail Addresse*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="Deine Nachricht*" required></textarea>    
<input class="btn btn-dark" type="submit" value="Send">
</form>