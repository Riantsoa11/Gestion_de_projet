---
id: US-04
title: Consulter l'historique de mes commandes
epic: Gérer ses commandes (demande A de Nadia)
exigence: EX-F-16
points: 2
---

# US-04 · Consulter l'historique de mes commandes

**En tant que** client régulier,
**je veux** consulter la liste de mes commandes passées avec leur contenu,
**afin de** recommander un repas identique en un clic.

**Exigence liée :** EX-F-16 (paiement — trace de la transaction)

## Critères d'acceptation
- [ ] L'écran « Historique » liste les commandes des 12 derniers mois, de la plus récente à la plus ancienne.
- [ ] Chaque ligne affiche la date, le total et le statut final (livrée, annulée).
- [ ] Un bouton « Recommander » recrée le panier à l'identique.

## INVEST
- [x] **Indépendante** : lecture seule, ne dépend pas des stories de gestion active.
- [x] **Négociable** : la fenêtre de 12 mois est négociable.
- [x] **Valorisable** : raccourci « recommander » = valeur immédiate.
- [x] **Estimable** : 2 points.
- [x] **Petite (Small)** : un sprint.
- [x] **Testable** : tri, bouton recommander et fenêtre 12 mois vérifiables.
