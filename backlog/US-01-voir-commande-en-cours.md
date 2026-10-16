---
id: US-01
title: Voir ma commande en cours
epic: Gérer ses commandes (demande A de Nadia)
exigence: EX-F-15
points: 3
---

# US-01 · Voir ma commande en cours

**En tant que** client ayant passé commande,
**je veux** voir l'état d'avancement de ma commande (reçue, en préparation, prête, en livraison),
**afin de** savoir quand elle arrivera sans appeler le restaurant.

**Exigence liée :** EX-F-15 (notification « prête »)

## Critères d'acceptation
- [ ] L'écran « Ma commande » affiche l'un des 4 statuts : reçue, en préparation, prête, en livraison.
- [ ] Le statut se met à jour en moins de 10 s après changement côté cuisine.
- [ ] Une notification est envoyée au passage au statut « prête ».

## INVEST
- [x] **Indépendante** : lecture seule, ne dépend pas de la modification ni de l'annulation.
- [x] **Négociable** : le format d'affichage reste à discuter avec Nadia.
- [x] **Valorisable** : le client sait où en est sa commande sans appeler.
- [x] **Estimable** : parcours connu, 3 points.
- [x] **Petite (Small)** : tient dans un sprint.
- [x] **Testable** : les 4 statuts et le délai de 10 s sont vérifiables.
