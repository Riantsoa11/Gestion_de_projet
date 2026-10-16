---
id: US-03
title: Annuler ma commande avant préparation
epic: Gérer ses commandes (demande A de Nadia)
exigence: EX-F-16
points: 3
---

# US-03 · Annuler ma commande avant préparation

**En tant que** client qui a changé d'avis,
**je veux** annuler ma commande tant qu'elle n'est pas en préparation,
**afin de** ne pas être facturé pour un repas que je ne prendrai pas.

**Exigence liée :** EX-F-16 (paiement en ligne — remboursement associé)

## Critères d'acceptation
- [ ] Le bouton « Annuler » est actif tant que le statut est « reçue ».
- [ ] L'annulation déclenche le remboursement intégral sous 24 h.
- [ ] Après « en préparation », l'annulation est refusée avec un message et le numéro du restaurant.

## INVEST
- [x] **Indépendante** : ne dépend pas de la modification.
- [x] **Négociable** : la fenêtre d'annulation reste discutable.
- [x] **Valorisable** : évite la facturation d'un repas non voulu.
- [x] **Estimable** : 3 points.
- [x] **Petite (Small)** : un sprint.
- [x] **Testable** : règles « statut reçue → OK », « statut en préparation → refus » vérifiables.
