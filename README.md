# ComplianceCheck

![Status](https://img.shields.io/badge/status-active-00B386)
![Version](https://img.shields.io/badge/version-2.0-7c3aed)
![ISO 27001](https://img.shields.io/badge/ISO_27001-2022-blue)
![NIS2](https://img.shields.io/badge/NIS2-EU-purple)
![License](https://img.shields.io/badge/license-MIT-green)

 **[Faire le diagnostic](https://mvanita.github.io/Compliance-Check/)**

---

La plupart des PME ne savent pas vraiment où elles en sont sur ISO 27001 et NIS2. Pas parce qu'elles ne s'y intéressent pas — mais parce qu'un audit complet prend du temps, coûte cher, et nécessite une expertise qu'elles n'ont pas toujours en interne.

ComplianceCheck part de ce constat simple : une première visibilité vaut mieux qu'aucune visibilité. En 5 minutes, 25 questions, vous savez où vous en êtes — et surtout, par où commencer.

---

## Comment ça marche

Vous commencez par renseigner votre secteur d'activité et la taille de votre organisation. L'outil détermine automatiquement si vous êtes concerné par NIS2 en tant qu'entité essentielle, importante, ou si vous êtes hors périmètre — et adapte les questions en conséquence.

Ensuite viennent 25 questions réparties sur 7 domaines : gouvernance, contrôle d'accès, cryptographie, gestion des incidents, sécurité réseau, continuité d'activité, et conformité réglementaire. Pour les boîtes tech et SaaS, deux questions supplémentaires sur le développement sécurisé s'ajoutent automatiquement.

À la fin, vous obtenez un score de maturité par domaine, un radar chart pour visualiser vos forces et faiblesses, et une liste de recommandations concrètes classées par niveau de risque — le tout exportable en PDF.

---

## Ce qui a changé en v2

La première version générait un plan de remédiation statique — les mêmes recommandations pour tout le monde. Ce n'était pas suffisant.

En v2, vous pouvez connecter l'API Anthropic pour obtenir une analyse rédigée par une IA qui a lu vos réponses, connaît votre secteur, et sait si NIS2 vous oblige à quoi que ce soit. Ce n'est pas un rapport type — c'est une lecture de votre situation spécifique, avec une feuille de route sur 6 mois et un rappel de vos obligations légales.

Il y a aussi un système de sauvegarde. Vous pouvez garder vos évaluations dans le navigateur et revenir 3 mois plus tard pour mesurer votre progression sur un graphe. Concret à montrer à une direction qui se demande si les efforts portent leurs fruits.

---

## Ce qui est couvert

Les contrôles s'appuient sur ISO 27001:2022 (Annexe A, de A.5 à A.8), la directive NIS2 (articles 21 et 23), et les obligations RGPD essentielles (registre des traitements, DPO, analyse d'impact).

---

## Lancer le projet

```bash
git clone https://github.com/mvanita/Compliance-Check.git
cd Compliance-Check
# Ouvrir index.html dans un navigateur — rien à installer
```

Aucun serveur, aucune base de données. Tout fonctionne dans le navigateur. La sauvegarde des évaluations passe par le localStorage — vos données ne quittent jamais votre machine.

---

## Pourquoi j'ai fait ça

Je suis Marina, étudiante en 4ème année d'ingénierie cybersécurité à l'ESILV. En préparant des candidatures dans le domaine de la GRC et de la cyber-conformité, j'ai voulu comprendre de l'intérieur comment fonctionne ce type d'outil — pas juste en lire la doc, mais construire la logique de bout en bout : structurer une base de contrôles, hiérarchiser les risques, penser l'expérience de quelqu'un qui n'est pas expert.

Ce projet est le résultat de ce travail.

[LinkedIn](https://linkedin.com/in/marinavanitafouodjongnitedemo) · [GitHub](https://github.com/mvanita)
