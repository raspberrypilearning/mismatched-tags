Zorg ervoor dat tags met een openings- en sluitingstag, zoals `<div>` en `</div>`, overeenkomen en correct genest zijn.

Deze HTML is onjuist omdat er geen afsluitende `</div>`-tag is.

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<section>
<div><p>Lorem ipsum</p>
</section>

--- /code ---

Deze HTML is onjuist omdat de `</div>` vóór de afsluitende `</p>`-tag staat.

--- code ---
---
language: HTML
filename: index.html
line_numbers: false
---

<div><p>Lorem ipsum</div></p>

--- /code ---

**Tip:** Als je HTML onjuist is, kan een webbrowser soms toch achterhalen wat je bedoelt. Zorg er wel voor dat jouw HTML correct is, want onjuiste HTML kan later problemen opleveren. Onjuiste HTML zorgt er bovendien voor dat schermlezers jouw pagina moeilijk kunnen begrijpen.
