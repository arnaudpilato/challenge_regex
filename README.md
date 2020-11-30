# challenge_regex

# Challenge

Utilisation des Regex

Comme pour les étapes précédentes, teste toutes les expressions régulières du challenge sur le site http://regexr.com/, sur le même texte d'exemple, disponible pour rappel sur le Gist suivant.

- Trouve l'expression régulière qui cherche la seule occurrence du deuxième prénom de Néo (soit le A. de "Thomas A. Anderson).
Hint : cherche vite Néo avant qu'il ne s'échappe...
# /A\./

- Trouve l'expression régulière qui cherche la date contenue dans le document.
Hint: il ne s'agit pas juste de chercher le texte 31/03/1999, mais de chercher deux chiffres et un slash, suivi de deux chiffres et d'un slash, suivi de quatre chiffres.
# /([0-3][0-9]\/){2}([0-9]{4})/g

- Trouve l'expression qui cherche la note contenue dans le texte, sans pour autant sélectionner une partie de la date (tu peux t'aider du caractère espace avant la note).
Hint: il ne s'agit pas de chercher directement le texte 9/10, mais de chercher un chiffre et un slash, suivi de deux chiffres.
# /([0-1]?[0-9]\/)([0-9]{2}) /g

- Trouve l'expression régulière qui renvoie les mots ayant au moins 14 caractères (tu devrais trouver l'age du capitaine, à moins que ça ne soit son vaisseau !)
# /[a-zA-Z]{14}/g

- Trouve l'expression régulière qui correspond à l'url de la fiche du fils sur IMDB https://www.imdb.com/title/tt0133093 (attention à ne pas sélectionner les parenthèses).
# /(https?:\/\/|www\.)[a-zA-Z-0-9-_\/\.\?=&]+/g

- Mets toutes les expressions régulières dans un fichier partagé que tu enverras le lien en solution.

# Critères de validation

- Toutes les regex du challenge sont testables sur le site http://regexr.com/.
- Les résultats correspondent précisément à ce qui est demandé.
