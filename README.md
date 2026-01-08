# Hooks React Native – Thème clair/sombre avec useColorScheme

## Aperçu
Ce lab met en place un écran d’accueil React Native qui s’adapte automatiquement au thème système (clair/sombre) grâce au hook useColorScheme. L’interface applique des couleurs cohérentes (fond, texte, accent) et se met à jour immédiatement lorsque le thème de l’appareil change. Aucun accès Internet n’est requis.

## Plan rapide du lab
* Créer une application React Native (Expo recommandé) et lancer un émulateur.
* Ajouter un écran WelcomeScreen générique avec un logo local et un texte.
* Importer et instancier useColorScheme depuis react-native.
* Définir une palette de couleurs light/dark (fond, texte, accent).
* Appliquer des styles conditionnels via un tableau de styles.
* Ajouter une barre d’accent et un conteneur d’en-tête.
* Tester la bascule clair/sombre dans l’émulateur Android et iOS.
* Vérifier la lisibilité (contraste texte/fond) et corriger les styles.
* Ajouter une option de debug (affichage de colorScheme) sans perturber l’UI.
* Appliquer des bonnes pratiques : variables de thème, styles réutilisables, ordre des styles.
* Valider les checkpoints finaux et corriger les erreurs fréquentes.

## Objectifs d’apprentissage
* Importer et instancier useColorScheme.
* Comprendre les valeurs possibles : light, dark, null.
* Construire un mini-système de thème (palette) sans dépendances externes.
* Appliquer des styles conditionnels de manière lisible.
* Tester et valider le comportement sur émulateurs Android/iOS.

## Prérequis
* Node.js et npm (ou yarn).
* Un environnement React Native opérationnel (Expo recommandé).
* Un émulateur Android ou un simulateur iOS.
* Connaissances de base : composants ScrollView, View, Text, Image, StyleSheet.

## Notions clés
* Hook : fonction permettant d’accéder aux fonctionnalités React dans un composant fonctionnel.
* useColorScheme : lecture et abonnement au thème système.
* Styles conditionnels : tableau de styles [styleFixe, styleVariable].
* Contraste : assurer la lisibilité (texte clair sur fond sombre, et inversement).

## Architecture / Concepts
### Cible
Un écran WelcomeScreen :
* Détecte le thème système.
* Adapte le fond, les couleurs de texte, et une couleur d’accent.
* Utilise un asset local (logo) pour fonctionner hors-ligne.
### Palette de couleurs imposée
* Accent : #EE9972
* Clair : fond #EDEFEE, texte #333333
* Sombre : fond #333333, texte #EDEFEE
* Noir et blanc si nécessaire (mais conserver la cohérence avec la palette).

## Création du projet 
<img width="959" height="503" alt="Lab9 1" src="https://github.com/user-attachments/assets/5ab017ef-895c-457c-a5ce-30017df40c3b" />

## Exécution 
<img width="959" height="503" alt="Lab9 2" src="https://github.com/user-attachments/assets/fc571328-2fee-49d7-9db7-1d855bec83e0" />
<img width="959" height="474" alt="Lab9 3" src="https://github.com/user-attachments/assets/0a0fde4f-4c18-4942-8cca-9dc4a4bf98cd" />
<img width="959" height="476" alt="Lab9 4" src="https://github.com/user-attachments/assets/c6cdf43b-44ee-4b0b-a37e-008ce472e26f" />

### Mode clair
<img width="959" height="468" alt="Lab9 5" src="https://github.com/user-attachments/assets/bcb2862d-8292-487b-9844-8944eb39737a" />

### Mode sombre 
<img width="959" height="470" alt="Lab9 6 dark " src="https://github.com/user-attachments/assets/df28aa3a-c444-433c-8638-9a15d050fbc3" />

https://github.com/user-attachments/assets/94991443-2b22-4811-8b2c-49a4cca88cdd

## Auteur
* Nom : BEN-LAGHFIRI Majeda
* Cours: React Native
* Date : Janvier 2026
* Encadré par : Pr.Mohamed LACHGAR


  
