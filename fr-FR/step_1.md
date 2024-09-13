Assure-toi que les balises avec une balise ouverte et une balise fermée telles que `<div>` et `</div>` sont correctement appariées et imbriquées.

Ce code HTML est incorrect parce qu'il n'y a pas de balise fermante `</div>`.

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

<section>
<div><p>Lorem ipsum</p>
</section>
--- /code ---

Ce code HTML est incorrect parce que la balise `</div>` apparaît avant la balise fermante `</p>`.

## --- code ---

language: HTML
filename: index.html
line_numbers: false
--------------------------------------------------------

<div><p>Lorem ipsum</p></div>

\--- /code ---

**Astuce :** Si ton code HTML est incorrect, il arrive qu'un navigateur web comprenne ce que tu voulais dire. Tu dois quand même t'assurer que ton code HTML est correct, car un code HTML incorrect pourrait causer des problèmes plus tard. Un code HTML incorrect rend également difficile la compréhension de ta page par les lecteurs d'écran.
