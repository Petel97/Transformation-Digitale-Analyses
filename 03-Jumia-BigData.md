# Cas Étude 3 : JUMIA GUINÉE

## Résumé de l'énoncé

- **Problème initial (Décembre 2021)** : Marketing non personnalisé. Mêmes promos envoyées à tout le monde.
- **Taux de clics (CTR) avant Big Data** : Seulement 2% (2 personnes sur 100 cliquaient)
- **Taux d'ouverture des emails avant** : 15%
- **Budget du projet** : 500 millions GNF
- **Résultat après 6 mois** : CA mensuel passe de 300M à 950M GNF

## Objectif

Utiliser le Big Data et l'IA pour comprendre les comportements d'achat des clients, personnaliser les offres et augmenter les ventes.

---

## Quel est le problème au départ ? (L'ancien marketing)

Imaginez que vous tenez une boutique physique. Vous voyez un client entrer, mais vous ne savez pas qui il est, ce qu'il aime ou ce qu'il a acheté hier. Pour essayer de vendre, vous criez à tout le monde : "Venez acheter des téléphones !", même à ceux qui viennent d'en acheter un ou à ceux qui ne cherchent que des vêtements.

**Résultat** : Les gens se sentent harcelés par des publicités qui ne les intéressent pas.

**Chez Jumia** : Seulement **2 personnes sur 100** cliquaient sur leurs offres. **15%** ouvraient les emails.

---

## Architecture technique déployée (Février-Juin 2022)

### Phase 1 : Collecte des données
**Durée** : 2 mois | **Coût** : 150M GNF

**Jumia collecte TOUT sur chaque client** :
- Produits consultés (même sans acheter)
- Temps passé sur chaque page
- Recherches effectuées
- Heure de connexion préférée
- Appareil utilisé (téléphone/ordinateur)
- Localisation
- Historique achats (2 ans)

**Résultat** : 50 millions de points de données sur 200 000 clients actifs !

### Phase 2 : Analyse avec IA (Détection de patterns)
**Durée** : 2 mois | **Coût** : 200M GNF

**Pattern 1 : "Les Jeudis Soir"**
- 40% des achats vêtements = Jeudi 20h-23h
- Pourquoi ? Les gens achètent pour sortir le weekend
- **Action Jumia** : Promos vêtements les jeudis uniquement

**Pattern 2 : "L'Effet Salaire"**
- Pic achats électroménager : 25-30 du mois
- Pourquoi ? Les gens reçoivent salaire fin de mois
- **Action Jumia** : Promos électro fin de mois

**Pattern 3 : "Le Panier Maman"**
- Clients qui achètent couches bébé achètent aussi : Lait, vêtements enfant, jouets
- Probabilité : 85% !
- **Action Jumia** : Recommandations "Produits complémentaires" (cross-selling)

### Phase 3 : Personnalisation totale
**Durée** : 2 mois | **Coût** : 150M GNF

**L'algorithme crée 12 profils types** :

| Profil | Cible | Produits typiques |
|--------|-------|-------------------|
| Fashionista | Femmes 18-30 ans | Vêtements mode, maquillage, chaussures |
| Bricoleur | Hommes 30-50 ans | Outils, électroménager |
| Gamer | Jeunes | Consoles, jeux vidéo |
| Maman Active | Femmes avec enfants | Produits bébé, couches, lait |
| Tech Addict | Tous âges | Smartphones, gadgets |
| Sportif | Adultes actifs | Équipements sport |
| Religieuse | Seniors | Livres religieux, tapis de prière |

**Chaque client reçoit des promos PERSONNALISÉES !**

---

## Exemple concret : Même email, 3 versions

**Aminata (Fashionista) reçoit** :
