# Cas Étude 3 : JUMIA GUINÉE

## Résumé de l'énoncé

**Problème initial (Décembre 2021)** : Marketing non personnalisé. Jumia envoyait les mêmes promotions à tous les clients, sans tenir compte de leurs préférences ou de leur historique d'achat. Résultat : seulement 2% de taux de clics (CTR) et 15% de taux d'ouverture des emails. L'échec du marketing de masse était flagrant. **Budget du projet** : 500 millions GNF. **Objectif** : Utiliser le Big Data et l'IA pour comprendre les comportements d'achat, personnaliser les offres et augmenter significativement les ventes.

## Le problème au départ : l'ancien marketing

Imaginez que vous tenez une boutique physique. Vous voyez un client entrer, mais vous ne savez pas qui il est, ce qu'il aime ou ce qu'il a acheté hier. Pour essayer de vendre, vous criez à tout le monde : "Venez acheter des téléphones !", même à ceux qui viennent d'en acheter un ou à ceux qui ne cherchent que des vêtements. Résultat : les gens se sentent harcelés par des publicités qui ne les intéressent pas. Chez Jumia, seulement **2 personnes sur 100** cliquaient sur leurs offres. Le chiffre **15%** servait de point de comparaison pour mesurer l'échec du marketing non personnalisé : c'était le taux d'ouverture des emails avant l'IA, contre 58% après.

---

## Architecture technique déployée (Février-Juin 2022)

| Phase | Durée | Coût | Actions détaillées | Résultat |
|-------|-------|------|-------------------|----------|
| **Phase 1 : Collecte des données** | 2 mois | 150M GNF | Collecte de : produits consultés (même sans achat), temps passé par page, recherches effectuées, heure de connexion, appareil utilisé, localisation, historique achats (2 ans) | 50 millions de points de données sur 200 000 clients actifs |
| **Phase 2 : Analyse avec IA (détection de patterns)** | 2 mois | 200M GNF | Algorithmes analysent les données pour découvrir des schémas de comportement cachés | 3 patterns majeurs identifiés (Jeudis Soir, Effet Salaire, Panier Maman) |
| **Phase 3 : Personnalisation totale** | 2 mois | 150M GNF | Création de profils clients, segmentation, recommandations automatiques | 12 profils types créés, promos 100% personnalisées |

---

## Détail des patterns découverts par l'IA

| Pattern | Découverte | Pourquoi ? | Action Jumia | Impact |
|---------|------------|------------|--------------|--------|
| **"Les Jeudis Soir"** | 40% des achats vêtements = Jeudi 20h-23h | Les gens achètent pour sortir le weekend | Promos vêtements uniquement les jeudis | Hausse des ventes vêtements le jeudi |
| **"L'Effet Salaire"** | Pic achats électroménager : 25-30 du mois | Les gens reçoivent leur salaire fin de mois | Promos électro en fin de mois | Hausse des ventes électroménager |
| **"Le Panier Maman"** | Clients achetant couches bébé achètent aussi lait, vêtements enfant, jouets (85% probabilité) | Besoins complémentaires des jeunes parents | Recommandations "produits complémentaires" (cross-selling) | Panier moyen augmenté de +73% |

---

## Les 12 profils types créés par l'IA

| Profil | Cible | Produits typiques | Stratégie marketing |
|--------|-------|-------------------|---------------------|
| Fashionista | Femmes 18-30 ans | Vêtements mode, maquillage, chaussures | Promos sur les tendances, livraison rapide |
| Bricoleur | Hommes 30-50 ans | Outils, électroménager | Promos fin de mois, garages |
| Gamer | Jeunes 15-25 ans | Consoles, jeux vidéo, accessoires | Promos sur nouvelles sorties |
| Maman Active | Femmes 25-40 ans avec enfants | Produits bébé, couches, lait, jouets | Cross-selling, offres famille |
| Tech Addict | 20-45 ans | Smartphones, gadgets, accessoires | Promos sur nouveautés tech |
| Sportif | 20-50 ans | Équipements sport, vêtements technique | Promos saisonnières |
| Religieuse | 50+ ans | Livres religieux, tapis de prière | Réduction sur quantités |
| Étudiant | 18-25 ans | Fournitures scolaires, vêtements pas chers | Promos rentrée, livraison gratuite |
| Senior | 60+ ans | Téléphones simples, livres | Interface simplifiée, livraison à domicile |
| Professionnel | 30-55 ans | Équipement bureau, informatique | Facturation pro, livraison rapide |
| Beauté | 18-40 ans | Cosmétiques, soins, parfums | Échantillons gratuits, coffrets |
| Maison | 30-60 ans | Décoration, électroménager, linge | Promos sur lots, livraison gratuite |

---

## Exemple concret : même email, 3 versions différentes

| Client | Profil | Email reçu | Résultat attendu |
|--------|--------|------------|------------------|
| **Aminata** | Fashionista | "🎉 Aminata, POUR VOUS : 👗 Robe que vous avez vue hier : -40%, 👠 Chaussures assorties : -30%, 💄 Maquillage tendance : CADEAU dès 300K" | Taux de clics élevé |
| **Ibrahim** | Bricoleur | "🔨 Ibrahim, Promotions Bricolage : 🔧 Perceuse que vous cherchiez : -35%, 📦 Pack 100 vis : OFFERT, 🛠️ Nouveau marteau disponible" | Taux de clics élevé |
| **Mme Diallo** | Religieuse | "📿 Mme Diallo, Nouveautés : 📖 Coran français-arabe : -20%, 🧎 Tapis prière qualité : -15%, 🕌 Livres religieux : 2 achetés = 1 offert" | Taux de clics élevé |

---

## Cas réel : prédiction parfaite

| Étape | Date/Heure | Action | Détail |
|-------|------------|--------|--------|
| **1. Détection IA** | 25 Mars 2023, 14h | Analyse comportement client | Kadiatou (28 ans) a cherché "poussette bébé" 5 fois cette semaine, a consulté 12 produits bébé, mais n'a rien acheté (hésite sur le prix) |
| **2. Prédiction** | 14h05 | Calcul probabilité | IA : "90% de probabilité d'achat dans les 48 heures" |
| **3. Action automatique** | 20h00 | Email personnalisé | "Kadiatou, la poussette que vous aimez = -25% SEULEMENT AUJOURD'HUI" + "Payez en 3 fois sans frais" |
| **4. Achat déclenché** | 27 Mars, 09h00 | Transaction | Achat de la poussette : 480 000 GNF |
| **5. Cross-selling** | 09h05 | Recommandations automatiques | Achat supplémentaire : couches, vêtements bébé, biberon |
| **6. Résultat final** | 09h10 | Panier total | **780 000 GNF** (au lieu de 480K prévu) |

---

## Prédictions encore plus poussées

| Cas | Détection IA | Signaux suspects | Prédiction | Action Jumia | Résultat |
|-----|--------------|------------------|------------|--------------|----------|
| **Anticiper une grossesse** | Cliente achète vitamines prénatales + consulte vêtements grande taille + cherche "fatigue grossesse" | Probabilité = 85% | "Probablement enceinte, 2ème trimestre" | Proposition catalogue "Maman & Bébé" | Cliente surprise mais ravie, achète beaucoup |
| **Détecter un déménagement** | Client achète cartons + scotch + matériel emballage | Probabilité = 90% | "Déménagement imminent" | Proposition meubles, décoration, électroménager | Panier moyen × 5 |
| **Cadeau d'anniversaire** | Date de naissance dans le compte client | Date connue | "Anniversaire dans 15 jours" | Email automatique : "🎂 Offre spéciale anniversaire : -30%" | 40% des clients achètent pour leur propre anniversaire |

---

## Comment ça marche techniquement ? (Architecture Big Data)

| Étape | Composant technique | Technologie utilisée | Fonction | Volume traité |
|-------|---------------------|---------------------|----------|---------------|
| **1. Collecte** | Data Collection | Cookies navigateur + tracking application mobile + historique serveur | Chaque clic, vue, recherche et achat est enregistré en temps réel | 50M+ événements/jour |
| **2. Stockage** | Data Lake | Serveurs AWS (Afrique du Sud) + stockage distribué | Stockage massif des données brutes et historisées | 2 pétaoctets (2 millions de Go) |
| **3. Analyse** | Machine Learning | TensorFlow + Python + 50+ modèles prédictifs | Détection de patterns, calcul de probabilités, entraînement continu | 200 000 profils analysés |
| **4. Action** | Marketing Automation | Plateforme emailing + notifications push + API recommandations | Envoi automatique d'emails personnalisés, push ciblés, promos dynamiques | 58% taux d'ouverture, 23% CTR |

---

## Résultats clés (6 mois après)

| Indicateur | Avant Big Data | Après Big Data | Évolution | Interprétation |
|------------|----------------|----------------|------------|----------------|
| Taux d'ouverture des emails | 15% | 58% | **+287%** 🚀 | Les clients ouvrent car le contenu les intéresse |
| Taux de clic (CTR) | 2% | 23% | **+1050%** 🚀 | Les offres personnalisées génèrent plus de clics |
| Taux de conversion | 0,5% | 8% | **+1500%** 🚀 | Les clients achètent plus car on répond à leurs besoins |
| Panier moyen | 450K GNF | 780K GNF | **+73%** 🚀 | Le cross-selling fonctionne |
| Clients récurrents | 18% | 52% | **+189%** 🚀 | La personnalisation fidélise |
| Chiffre d'affaires mensuel | 300M GNF | 950M GNF | **+217%** 🚀 | Impact direct sur les revenus |

---

## Évaluation du projet (critères techniques)

| Critère | Analyse Technique et Stratégique | Note /10 |
|---------|--------------------------------|----------|
| Volume de données | Exploitation de 50 millions de points de données collectés sur 200 000 clients actifs | 9/10 |
| Potentiel de conversion | Passage d'un CTR générique de 2% à un taux personnalisé de 23% | 10/10 |
| Précision de l'IA | Capacité des algorithmes à prédire un achat avec une probabilité de 90% dans les 48h | 9/10 |
| Valeur du panier | Augmentation du panier moyen de +73% via le cross-selling | 8/10 |
| Coût du projet | Investissement de 500 millions GNF pour la plateforme de données et l'expertise | 7/10 |
| ROI | Chiffre d'affaires mensuel bondissant de 300M à 950M GNF en 6 mois | 10/10 |

---

## Recommandation finale

✅ **LANCER** le projet Big Data

## Justification (3 arguments clés)

| Argument | Explication | Preuve chiffrée |
|----------|-------------|-----------------|
| **1. Passage du marketing de masse au marketing prédictif** | Avant : mêmes promotions pour tous (ex: couches à des célibataires) → désintérêt. Après : segmentation en 12 profils types → on répond à un besoin spécifique au bon moment | CTR : 2% → 23% |
| **2. Anticipation des événements de vie** | L'algorithme analyse les changements de comportement (ex: achat vêtements maternité → prédit besoin poussettes, lait, couches). Cette proactivité crée une dépendance positive | Cas Kadiatou : 480K → 780K GNF |
| **3. Optimisation des stocks et de la logistique** | En sachant ce que les clients vont acheter dans les 30 prochains jours, Jumia pré-positionne ses stocks à Conakry → réduction des délais, fin des ruptures | CA mensuel : 300M → 950M GNF (+217%) |

---

## Leçons pour entreprises

| Leçon | Enseignement | Citation |
|-------|---------------|----------|
| **Données = Nouvel Or** | Les données clients sont l'actif le plus précieux d'une entreprise moderne | "Avant : on DEVINE ce que veut le client. Après : on SAIT ce qu'il veut avant même qu'il le sache !" - Moussa, Data Scientist |
| **Personnalisation > Promotion massive** | 1 email personnalisé est 10× plus efficace que 100 emails génériques | Taux d'ouverture : 15% → 58% |
| **Commencez simple** | Jumia a commencé avec 3 critères (achats, âge, localisation). Aujourd'hui : 50 critères | Phase 1 = historique achats uniquement |
| **Privacy d'abord** | Demander la permission = transparence = confiance = données de qualité | 99% d'acceptation clients |
| **L'IA s'améliore avec le temps** | Plus de données = meilleure IA = meilleures prédictions (cercle vertueux) | Précision : 60% → 94% en 1 an |

---

## Éthique et protection des données

| Principe | Application chez Jumia |
|----------|------------------------|
| Consentement client | Demande systématique avant toute collecte |
| Transparence | Information claire sur l'utilisation des données |
| Droit à l'oubli | Possibilité de supprimer ses données à tout moment |
| Non-discrimination | Pas de décision automatique sans contrôle humain |
| Données sensibles | Aucune collecte sans consentement explicite (santé, politique, religion) |

---

## Indicateurs de réussite du projet

| Indicateur | Cible | Statut |
|------------|-------|--------|
| 50 millions de points de données collectés | ✅ | ATTEINT |
| 12 profils clients identifiés et utilisés | ✅ | ATTEINT |
| Taux de clics (CTR) > 15% | ✅ | 23% atteint |
| Panier moyen augmenté de +50% | ✅ | +73% atteint |
| CA mensuel doublé | ✅ | x3,16 atteint |
| Taux de satisfaction client > 80% | ⏳ | En cours |
| Conformité RGPD validée | ✅ | VALIDÉE |
