# REVIZO — première base du projet

REVIZO est une application éducative destinée aux élèves du collège et du lycée.
Cette première version est un prototype frontend en HTML, CSS et JavaScript.

## Contenu
- `index.html` : structure des écrans.
- `css/style.css` : design responsive.
- `js/data/school-data.js` : classes, séries indicatives et traductions.
- `js/app.js` : navigation, profil local et langue FR/EN.

## Tester
Ouvre `index.html` dans un navigateur moderne. Pour un test plus fiable, utilise un petit serveur web local ou l'hébergement GitHub Pages.

## État actuel
Le profil élève et la navigation de base fonctionnent. Les rubriques Cours, Exercices, Quiz et Examens blancs sont des écrans de préparation : elles ne contiennent pas encore les vrais contenus pédagogiques ni les exercices interactifs.

## Étapes suivantes
1. Valider les niveaux, classes, séries et programmes officiels du pays ciblé.
2. Ajouter les matières et chapitres par classe.
3. Créer le moteur de cours, exercices et corrections.
4. Ajouter les quiz, examens chronométrés et résultats.
5. Ajouter le mode hors connexion et les tests sur Android.
6. Intégrer Capacitor et configurer une compilation Android.

## Attention
Les séries présentes dans `school-data.js` sont indicatives et doivent être vérifiées avec les programmes officiels avant toute publication. Cette base n'est pas encore un APK.
