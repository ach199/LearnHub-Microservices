# LearnHub

LearnHub est une plateforme de cours en ligne où les formateurs peuvent publier des cours et où les étudiants peuvent les découvrir, s'y inscrire et suivre leur progression.

## Vision

### Problème

Les formateurs ne disposent pas toujours d'un espace simple pour partager leurs cours. De leur côté, les étudiants peuvent avoir du mal à trouver des cours adaptés et à suivre leur avancement.

### Solution

Proposer une plateforme qui réunit les cours, les inscriptions et le suivi de la progression des étudiants.

### Public cible

- Étudiants qui souhaitent suivre des cours en ligne.
- Formateurs qui souhaitent publier des cours.
- Administrateurs de la plateforme.

## Périmètre de la première version

La première version (MVP) vise à permettre aux utilisateurs de :

- créer un compte ;
- consulter le catalogue des cours ;
- publier un cours en tant que formateur ;
- s'inscrire à un cours en tant qu'étudiant ;
- suivre sa progression dans un cours, exprimée en pourcentage.

## Rôles et besoins

| Rôle | Besoins |
| --- | --- |
| Étudiant | Créer un compte pour utiliser la plateforme.<br>Parcourir le catalogue pour trouver un cours.<br>S'inscrire à un cours pour le suivre.<br>Consulter sa progression. |
| Formateur | Créer un compte pour utiliser la plateforme.<br>Publier un cours afin que les étudiants puissent le découvrir. |
| Administrateur | Les fonctionnalités associées à ce rôle restent à préciser. |

## Hors périmètre de la première version

- Paiement des cours.
- Avis et évaluations.
- Certificats de fin de cours.

## État du projet

Le dépôt est organisé en microservices. Le dossier `services` prévoit des services distincts pour l'authentification, les utilisateurs, les cours, les inscriptions, les paiements, les notifications et les statistiques. Les dossiers `api-gateway`, `shared`, `docker` et `scripts` sont également prévus pour la passerelle API, les éléments partagés et les outils de développement.

## Image

![Image](Images/1792440273639.jpg)

Random YouTube video:
https://www.youtube.com/watch?v=dQw4w9WgXcQ
