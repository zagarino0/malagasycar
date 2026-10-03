# MALAGASYCAR — maquette HTML/CSS/JS

Cette version utilise le **logo officiel MALAGASYCAR fourni dans la conversation** (`assets/logo-malagasycar.png`). Aucune dépendance au logo Annumada n'est utilisée.

## Pages
- `index.html` — accueil
- `voyages.html` — voyages
- `location.html` — location de véhicules et disponibilité
- `destinations.html` — destinations
- `galerie.html` — galerie
- `avis.html` — avis
- `contact.html` — contact
- `reservation.html` — réservation avec choix de siège / dates de location
- `admin.html` — dashboard administrateur

## Workflow location
1. Le client choisit le véhicule et les dates.
2. Le client envoie sa demande de paiement.
3. La demande passe en `En attente` et bloque la même période dans la maquette.
4. L'administrateur valide le paiement dans `admin.html`.
5. La location passe à `Confirmée` et le véhicule affiche `Indisponible` pour la période.
6. L'administrateur peut annuler la location ; le véhicule redevient disponible.

Les données de démonstration sont conservées dans `localStorage` sous la clé `malagasycarDemo`.

## Important
Les photos, tarifs, avis, moyens de paiement et textes opérationnels restent des contenus de démonstration à valider avec MALAGASYCAR avant mise en production.
