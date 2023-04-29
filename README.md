# CD-CI Process

GameCi : https://game.ci/docs/

GameCI est une plateforme d'intégration continue pour les jeux vidéo qui permet aux développeurs de tester et de déployer rapidement leurs jeux sur différentes plateformes, en utilisant des workflows automatisés. Elle est conçue pour aider les développeurs à gagner du temps et à améliorer la qualité de leurs jeux.

Github Workflows : https://docs.github.com/en/actions/using-workflows/about-workflows
GitHub Workflows est un outil d'automatisation de flux de travail qui permet aux développeurs de définir, de personnaliser et d'exécuter des actions automatisées en réponse à des événements tels que la soumission de code, la création de demandes de fusion ou la publication de nouvelles versions de logiciels.

# LDJAM 53 Objectifs :

I Automatiser les builds :

1. **Windows**
2. **WebGL**
3. Android
4. Linux
5. Mac

Par priorités, seul les build windows et WebGL sont capital

II Faire une action de test
GameCI possède des actions de tests qu'il faudrait intégrer.
Ces test sont très simples, les premiers tests consistent à valider le code et sa compilation.

III Notifier du statut des tests et des builds avec discord
Cela permettrait aux devs de corriger le code dés qu'une erreur est push sur la branche DEV