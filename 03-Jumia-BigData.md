# Cas Étude 3 : JUMIA GUINÉE

## Résumé de l'énoncé

**Problème initial (Décembre 2021)** : Marketing non personnalisé. Jumia envoyait les mêmes promotions à tous les clients, sans tenir compte de leurs préférences ou de leur historique d'achat. Résultat : seulement 2% de taux de clics (CTR) et 15% de taux d'ouverture des emails. L'échec du marketing de masse était flagrant. **Budget du projet** : 500 millions GNF. **Objectif** : Utiliser le Big Data et l'IA pour comprendre les comportements d'achat, personnaliser les offres et augmenter significativement les ventes.

## Le problème au départ : l'ancien marketing

Imaginez que vous tenez une boutique physique. Vous voyez un client entrer, mais vous ne savez pas qui il est, ce qu'il aime ou ce qu'il a acheté hier. Pour essayer de vendre, vous criez à tout le monde : "Venez acheter des téléphones !", même à ceux qui viennent d'en acheter un ou à ceux qui ne cherchent que des vêtements. Résultat : les gens se sentent harcelés par des publicités qui ne les intéressent pas. Chez Jumia, seulement **2 personnes sur 100** cliquaient sur leurs offres. Le chiffre **15%** servait de point de comparaison pour mesurer l'échec du marketing non personnalisé : c'était le taux d'ouverture des emails avant l'IA, contre 58% après.

## Architecture technique déployée (Février-Juin 2022)

**Phase 1 : Collecte des données (2 mois, 150M GNF)** : Jumia collecte tout sur chaque client : produits consultés (même sans acheter), temps passé sur chaque page, recherches effectuées, heure de connexion préférée, appareil utilisé (téléphone/ordinateur), localisation, historique achats sur 2 ans. Résultat : 50 millions de points de données sur 200 000 clients actifs.

**Phase 2 : Analyse avec IA – Détection de patterns (2 mois, 200M GNF)** : L'algorithme découvre des schémas surprenants. Pattern 1 "Les Jeudis Soir" : 40% des achats vêtements ont lieu le jeudi entre 20h et 23h car les gens achètent pour sortir le weekend. Action Jumia : promos vêtements uniquement les jeudis. Pattern 2 "L'Effet Salaire" : pic d'achats électroménager entre le 25 et le 30 du mois, quand les gens reçoivent leur salaire. Action : promos électro en fin de mois. Pattern 3 "Le Panier Maman" : les clients qui achètent des couches bébé achètent aussi du lait, des vêtements enfant et des jouets avec une probabilité de 85%. Action : recommandations de produits complémentaires (cross-selling).

**Phase 3 : Personnalisation totale (2 mois, 150M GNF)** : L'algorithme crée 12 profils types : Fashionista (femmes 18-30 ans, mode), Bricoleur (hommes 30-50 ans, outils), Gamer (jeunes, consoles), Maman Active (femmes, produits bébé), Tech Addict (smartphones, gadgets), Sportif (équipements sport), Religieuse (seniors, livres religieux, tapis de prière), et 5 autres profils. Chaque client reçoit désormais des promos PERSONNALISÉES.

## Exemple concret : même email, 3 versions différentes

Aminata (Fashionista) reçoit : "🎉 Aminata, POUR VOUS : 👗 Robe que vous avez vue hier : -40%, 👠 Chaussures assorties : -30%, 💄 Maquillage tendance : CADEAU dès 300K". Ibrahim (Bricoleur) reçoit : "🔨 Ibrahim, Promotions Bricolage : 🔧 Perceuse que vous cherchiez : -35%, 📦 Pack 100 vis : OFFERT, 🛠️ Nouveau marteau disponible". Mme Diallo (Religieuse) reçoit : "📿 Mme Diallo, Nouveautés : 📖 Coran français-arabe : -20%, 🧎 Tapis prière qualité : -15%, 🕌 Livres religieux : 2 achetés = 1 offert".

## Cas réel : prédiction parfaite

25 Mars 2023, 14h : L'algorithme détecte que Kadiatou (28 ans) a cherché "poussette bébé" 5 fois cette semaine, a consulté 12 produits bébé, mais n'a rien acheté encore (elle hésite sur le prix). Prédiction IA : "90% de probabilité d'achat dans 48h". Action automatique Jumia : email à 20h "Kadiatou, la poussette que vous aimez = -25% SEULEMENT AUJOURD'HUI" + "Payez en 3 fois sans frais". Le 27 Mars à 09h, Kadiatou achète la poussette à 480 000 GNF. Bonus : elle achète aussi des couches, des vêtements bébé et un biberon. Total : 780 000 GNF (au lieu de 480K prévu).

## Prédictions encore plus poussées

L'IA est capable d'anticiper des événements de vie. Cas 1 "Anticiper une grossesse" : la cliente achète des vitamines prénatales et consulte des vêtements grande taille. L'IA prédit une grossesse au 2ème trimestre et Jumia lui propose le catalogue "Maman & Bébé". La cliente est surprise mais ravie et achète beaucoup. Cas 2 "Détecter un déménagement" : le client achète des cartons, du scotch et du matériel d'emballage. L'IA prédit un déménagement imminent et Jumia lui propose des meubles, de la décoration et de l'électroménager. Résultat : panier moyen multiplié par 5. Cas 3 "Cadeau d'anniversaire" : 15 jours avant la date d'anniversaire (détectée via le compte client), un email automatique est envoyé : "🎂 Offre spéciale anniversaire : -30%". Résultat : 40% des clients achètent pour leur propre anniversaire.

## Comment ça marche techniquement ?

Architecture Big Data de Jumia : Étape 1 "Collecte" : chaque clic est enregistré via cookies navigateur et tracking application mobile. Étape 2 "Stockage" : serveurs AWS en Afrique du Sud avec un Data Lake de 2 pétaoctets (2 millions de Go). Étape 3 "Analyse" : algorithmes TensorFlow + Python avec 50+ modèles prédictifs entraînés en continu. Étape 4 "Action" : marketing automation avec emails personnalisés automatiques, notifications push ciblées et promotions dynamiques.

## Résultats clés (6 mois après)

| Indicateur | Avant Big Data | Après Big Data | Évolution |
|------------|----------------|----------------|------------|
| Taux d'ouverture des emails | 15% | 58% | +287% 🚀 |
| Taux de clic (CTR) | 2% | 23% | +1050% 🚀 |
| Taux de conversion | 0,5% | 8% | +1500% 🚀 |
| Panier moyen | 450K GNF | 780K GNF | +73% 🚀 |
| Clients récurrents | 18% | 52% | +189% 🚀 |
| Chiffre d'affaires mensuel | 300M GNF | 950M GNF | +217% 🚀 |

## Évaluation du projet (critères techniques)

| Critère | Analyse Technique et Stratégique | Note /10 |
|---------|--------------------------------|----------|
| Volume de données | Exploitation de 50 millions de points de données collectés sur 200 000 clients actifs | 9/10 |
| Potentiel de conversion | Passage d'un CTR générique de 2% à un taux personnalisé de 23% | 10/10 |
| Précision de l'IA | Capacité des algorithmes à prédire un achat avec une probabilité de 90% dans les 48h | 9/10 |
| Valeur du panier | Augmentation du panier moyen de +73% via le cross-selling | 8/10 |
| Coût du projet | Investissement de 500 millions GNF pour la plateforme de données et l'expertise | 7/10 |
| ROI | Chiffre d'affaires mensuel bondissant de 300M à 950M GNF en 6 mois | 10/10 |

## Recommandation finale

✅ **LANCER** le projet Big Data

## Justification (3 arguments clés)

**1. Le passage du marketing de masse au marketing prédictif** : Avant ce projet, Jumia envoyait les mêmes promotions à tous les clients (par exemple des couches à des célibataires), ce qui entraînait un désintérêt total. Grâce au Big Data, l'entreprise segmente désormais ses clients en "Profils Types" (Fashionista, Tech-Lover, Parent, etc.). On ne vend plus un produit, on répond à un besoin spécifique au bon moment. La preuve : le taux de clic est passé de 2% à 23%.

**2. L'anticipation des événements de vie** : L'algorithme analyse les changements de comportement. Si un client commence à acheter des vêtements de maternité, le système anticipe les besoins futurs (poussettes, lait, couches) et les propose avant même que le client ne les cherche. Cette "proactivité" crée une dépendance positive à la plateforme, comme le montre le cas de Kadiatou qui a acheté pour 780K GNF au lieu des 480K prévus.

**3. L'optimisation des stocks et de la logistique** : En sachant ce que les clients vont probablement acheter dans les 30 prochains jours, Jumia peut pré-positionner ses stocks dans ses entrepôts de Conakry. Cela réduit les délais de livraison, évite les ruptures de stock sur les produits à forte demande, et améliore la satisfaction client. Le chiffre d'affaires mensuel a bondi de 300M à 950M GNF en seulement 6 mois, soit une augmentation de 217%.

## Leçons pour entreprises

**Leçon 1 : Données = Nouvel Or** : "Avant Big Data : on DEVINE ce que veut le client. Après Big Data : on SAIT ce qu'il veut avant même qu'il le sache !" - Moussa, Data Scientist.

**Leçon 2 : Personnalisation > Promotion massive** : 1 email personnalisé est 10 fois plus efficace que 100 emails génériques. La preuve : le taux d'ouverture est passé de 15% à 58%.

**Leçon 3 : Commencez simple** : Jumia a commencé avec seulement l'historique des achats, l'âge et la localisation. Aujourd'hui, ils utilisent 50 critères. Mais ils ont commencé SIMPLE.

**Leçon 4 : Privacy d'abord** : Jumia demande TOUJOURS la permission avant d'utiliser les données. Transparence = Confiance = Données de qualité. 99% des clients acceptent la personnalisation car elle apporte une vraie valeur ajoutée.

**Leçon 5 : L'IA s'améliore avec le temps** : Plus il y a de données, meilleure est l'IA, et meilleures sont les prédictions. C'est un cercle vertueux. La précision de l'IA est passée de 60% à 94% en un an.

## Éthique et protection des données

Points de vigilance : consentement client obligatoire avant toute collecte, transparence totale sur l'utilisation des données, droit à l'oubli (possibilité de supprimer ses données), et non-discrimination par l'IA. Aucune donnée sensible (santé, politique, religion) n'est collectée sans consentement explicite.

## Indicateurs de réussite du projet

☐ 50 millions de points de données collectés ☐ 12 profils clients identifiés et utilisés ☐ Taux de clics (CTR) > 15% (objectif atteint : 23%) ☐ Panier moyen augmenté de +50% (objectif atteint : +73%) ☐ CA mensuel doublé (objectif atteint : x3,16) ☐ Taux de satisfaction client > 80% ☐ Conformité RGPD validée
