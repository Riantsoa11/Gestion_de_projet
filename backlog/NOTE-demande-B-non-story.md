# Demande B · « Il faut créer la table Commandes dans la base. »

**Verdict : ce n'est pas une user story.**

## Pourquoi ?

- Elle viole le **V** d'INVEST : aucune valeur visible pour un utilisateur ou le client.
- Elle viole le **I** : la table n'a de sens que livrée en même temps qu'une story qui l'utilise.
- Elle décrit **comment** on code (`base de données`), pas **ce que** le système doit faire.

C'est le classique **story technique** repéré en atelier INVEST (séance 2, p. 29).

## Que faire à la place ?

La table `commandes` est une **tâche technique** rattachée aux user stories qui en ont besoin :

- US-01 · Voir ma commande en cours
- US-02 · Modifier ma commande avant envoi en cuisine
- US-03 · Annuler ma commande avant préparation
- US-04 · Consulter l'historique de mes commandes

La première de ces stories à passer en sprint embarque la création de la table dans ses tâches techniques. Les suivantes la réutilisent sans la recréer.

## À dire à Nadia

> « La table arrive automatiquement avec la première story livrée (US-01). On ne la fera pas pour elle-même, parce qu'une table seule n'apporte rien à ton client. »
