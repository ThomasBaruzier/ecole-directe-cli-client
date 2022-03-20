Ce script pour bash vous permet de calculer vos moyennes école directe sans avoir à attendre 2-3 jours que cela se fasse sur le site.

Pour l'instant, le programme est semi-automatisé, il faut récuperer les données manuellement.
Pour ce faire, rendez-vous sur la page avec vos notes sur école directe.
De là, entrez dans les options developpeur en appuyant sur F12.
Allez dans la catégorie "Network" ou "Réseau", et rechargez la page.
Chechez la requête "notes.awp". Cliquez dessus, allez dans la catégorie "Response" ou "Réponse", copiez l'integralité de celle-ci, et enregistrez tout cela dans un fichier "notes", situé dans le même répertoire que le script.
Il n'y a plus qu'à exécuter celui-ci pour obtenir vos moyennes.

Attention : pour le moment peu de matières sont supportées, et il faut éditer les coefficients manuellement.
