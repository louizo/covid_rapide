
# Générateur de cluster

fork LAB-MI/attestation-deplacement-derogatoire-q4-2020


## Informations

Ce patch permet de générer des attestations antidatées et valables en un clin d'œil sans passer par le formulaire.

Le qrcode contient l'heure de création du fichier, remplacée par l'heure de sortie moins 5 minutes.


## Utilisation

- cliquer sur le lien ci-dessous
- remplir le formulaire
- renseigner le nombre de minutes à retrancher de l'heure actuelle
- valider le formulaire
- [iOs] page précédente
- ajouter un raccourci à l'écran d'accueil
- créer d'autres raccourcis selon l'adresse et le motif de sortie


[le lien](https://nicopowa.github.io/covid_rapide/patch/gen.html)


iOs affiche l'attestation directement dans Safari

Android télécharge le fichier pdf


## Exemples :

*Bob va faire ses courses*

[attestation Bob](https://nicopowa.github.io/covid_rapide?lastname=Smith&firstname=Bob&birthday=01/01/1970&placeofbirth=Bob%27s%20hometown&address=1%20Bob%27s%20street&zipcode=75000&city=Bob%27s%20city&motif=achats&minutes=5)


*Alice va au travail car c'est plus ou moins la seule activité autorisée*

[attestation Alice](https://nicopowa.github.io/covid_rapide?lastname=Smith&firstname=Alice&birthday=01/01/1970&placeofbirth=Alice%27s%20hometown&address=1%20Alice%27s%20street&zipcode=75000&city=Alice%27s%20city&motif=travail&minutes=5)


## Mauvais exemples :

*Eve se promène avec une personne qui lui plaît depuis presque une heure
et souhaite prolonger cet instant de liberté de 45 minutes*

[attestation Eve](https://nicopowa.github.io/covid_rapide?lastname=Smith&firstname=Eve&birthday=01/01/1970&placeofbirth=Eve%27s%20hometown&address=1%20Eve%27s%20street&zipcode=75000&city=Eve%27s%20city&motif=sport_animaux&minutes=15)


*M. Dupont aperçoit des agents de police en pleine frénésie de contrôle et n'a pas son attestation.*

*Pas de panique ! Il clique sur le raccourci et l'attestation valable s'affiche instantanément à l'écran.*


## Fonctionnalités

fork de la version officielle + 

- automatisation
- antidatage
- petit décalage de texte très irritant
- dépendances non minifiées
- une icône tricolore
- formulaire pour les nuls
- attestation générée par le navigateur
- pas besoin de build
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