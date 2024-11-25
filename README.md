# Repo template comptabilité

Ce repo est un repo github template qui est copié quand on créé une comptabilité avec [comptanar](https://comptanar.github.io/)

Il contient la structure et les branches et les github actions pertinents à faire tourner une instance de comptanar et gérer sa comptabilité sans dépendre d'un.e comptable

## Explication des différents fichiers

- `personnes.yml` : liste des personnes (morales ou physiques) connues.
  Une même personne peut avoir plusieurs rôles (salarié⋅e, client⋅e, etc.), donc ce fichier ne stocke qu'assez peu d'informations,
  d'autres fichiers viennent le compléter.
- `salarié-es.yml` : la liste des salarié⋅es de la structure
- `exercices/ANNÉE/operationsHautNiveau.yml` : les opérations de haut niveau (envoi, réception et paiement de factures) pour une année donnée
