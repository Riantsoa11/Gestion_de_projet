---
id: US-05
title: Voir l'offre « habitués du soir » du lundi au jeudi
epic: Fidélisation (demande C de Nadia)
exigence: EX-F-18
points: 3
---

# US-05 · Voir l'offre « habitués du soir » du lundi au jeudi

**En tant que** client identifié comme habitué du soir,
**je veux** voir l'offre dédiée s'afficher sur l'accueil du lundi au jeudi entre 18 h et 22 h,
**afin de** profiter de la réduction prévue sans la chercher.

**Exigence liée :** EX-F-18 (horaires et offres temporelles)

## Critères d'acceptation
- [ ] Un client avec ≥ 4 commandes du soir sur les 30 derniers jours est marqué « habitué du soir ».
- [ ] Le bandeau d'offre s'affiche du **lundi 18 h au jeudi 22 h** (fuseau du restaurant).
- [ ] En dehors de cette fenêtre, le bandeau est masqué.
- [ ] L'offre apparaît automatiquement dans le panier dès qu'elle est éligible.

## INVEST
- [x] **Indépendante** : s'intègre à l'accueil sans dépendance aux stories de gestion de commande.
- [x] **Négociable** : le seuil « 4 commandes / 30 j » reste à cadrer avec Nadia.
- [x] **Valorisable** : fidélisation des clients du soir en semaine.
- [x] **Estimable** : 3 points.
- [x] **Petite (Small)** : un sprint.
- [x] **Testable** : règles de date, d'heure et de seuil mesurables.
