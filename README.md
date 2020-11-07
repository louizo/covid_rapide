
# Générateur de cluster

fork LAB-MI/attestation-deplacement-derogatoire-q4-2020


## Informations

Ce patch permet de générer des attestations antidatées et valables en un clin d'œil sans passer par le formulaire.

Le qrcode contient l'heure de création du fichier, remplacée par l'heure de sortie moins 5 minutes.


## Utilisation

- Cliquer sur le lien ci-dessous
- Remplir et valider le formulaire
- **Ajouter un raccourci à l'écran d'accueil**
- Créer d'autres raccourcis selon l'adresse et le motif de sortie


[le lien](https://nicopowa.github.io/covid_rapide/patch/gen.html)


Rien que pour tes yeux : [Android](https://nicopowa.github.io/covid_rapide/patch/covid_rapide_android.mp4) / [iOs](https://nicopowa.github.io/covid_rapide/patch/covid_rapide_ios.mp4)


## Exemples :

*Bob va faire ses courses*

[attestation Bob](https://nicopowa.github.io/covid_rapide?lastname=Smith&firstname=Bob&birthday=01/01/1970&placeofbirth=Bob%27s%20Hometown&address=1%20Bob%27s%20Street&zipcode=75000&city=Bob%27s%20City&motif=achats&minutes=5)


*Alice va au travail car c'est plus ou moins la seule activité autorisée*

[attestation Alice](https://nicopowa.github.io/covid_rapide?lastname=Smith&firstname=Alice&birthday=01/01/1970&placeofbirth=Alice%27s%20Hometown&address=1%20Alice%27s%20Street&zipcode=75000&city=Alice%27s%20City&motif=travail&minutes=5)


## Mauvais exemples :

*Eve se promène avec une personne qui lui plaît depuis presque une heure
et souhaite prolonger cet instant de liberté de 45 minutes*

[attestation Eve](https://nicopowa.github.io/covid_rapide?lastname=Smith&firstname=Eve&birthday=01/01/1970&placeofbirth=Eve%27s%20Hometown&address=1%20Eve%27s%20Street&zipcode=75000&city=Eve%27s%20City&motif=sport_animaux&minutes=15)


*M. Dupont aperçoit des agents de police en pleine frénésie de contrôle et n'a pas son attestation.*

*Pas de panique ! Il clique sur le raccourci et l'attestation valable s'affiche instantanément à l'écran.*


![shortcuts_screenshot](https://nicopowa.github.com/covid_rapide/patch/shortcuts.jpg)


## Fonctionnalités

fork de la version officielle + 

- automatisation
- antidatage
- petit décalage de texte très irritant
- dépendances non minifiées
- une icône tricolore
- formulaire pour les nuls
- attestation générée par le navigateur
- données stockées dans l'url du raccourci
- pas de local storage
- pas de build
- pas trop testé
- hébergé sur github pages


## Crédits

Voir repo officiel

https://github.com/LAB-MI/attestation-deplacement-derogatoire-q4-2020


## Responsabilité

Version o.0

codé Dimanche après-midi après une belle conversation Samedi nuit

Licence MIT

À vos risques et périls, respect des distances sociales, maintenir l'économie, etc...


## Reportage exclusif

[Les courses de Bob](https://nicopowa.github.io/covid_rapide/patch/bob_va_faire_ses_courses.mp4)