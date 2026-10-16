---
id: US-02
title: Modifier ma commande avant envoi en cuisine
epic: Gérer ses commandes (demande A de Nadia)
exigence: EX-F-17
points: 5
---

# US-02 · Modifier ma commande avant envoi en cuisine

**En tant que** client qui vient de valider son panier,
**je veux** modifier la composition de ma commande tant qu'elle n'est pas affichée en cuisine,
**afin de** corriger une erreur sans annuler et refaire tout le parcours.

**Exigence liée :** EX-F-17 (affichage en cuisine)

## Critères d'acceptation
- [ ] Le bouton « Modifier » est visible tant que la commande n'est pas au statut « en préparation ».
- [ ] Dès le passage « en préparation », le bouton disparaît et un message explique pourquoi.
- [ ] Les modifications recalculent le total avant confirmation.

## INVEST
- [x] **Indépendante** : s'appuie sur l'écran de US-01 mais ne la bloque pas.
- [x] **Négociable** : la fenêtre « avant cuisine » peut être étendue si besoin métier.
- [x] **Valorisable** : évite un double parcours annulation + recommande.
- [x] **Estimable** : 5 points (gestion d'état + recalcul).
- [x] **Petite (Small)** : un sprint.
- [x] **Testable** : règle « affichée en cuisine → bouton caché » vérifiable.
