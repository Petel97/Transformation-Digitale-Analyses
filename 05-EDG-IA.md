# Cas Étude 5 : EDG (ÉLECTRICITÉ DE GUINÉE)

## Résumé de l'énoncé

- **Pertes financières (2022)** : 40% de la production électrique perdue
  - 30% = pertes techniques (câbles vétustes)
  - **10% = FRAUDES** = 15 milliards GNF/mois = 180 milliards GNF/an !
- **Types de fraudes** :
  - Branchement sauvage (câble avant compteur)
  - Compteur trafiqué (aimant puissant)
  - Faux abonnement (restaurant sous nom de mosquée → tarif réduit)
- **Budget du projet** : 800 millions GNF
- **Partenaire technologique** : Schneider Electric + EDG

## Objectif

Détecter et éliminer automatiquement les fraudes énergétiques grâce à l'Intelligence Artificielle et aux compteurs intelligents.

---

## Évaluation du projet (Avant/Après IA)

| Critère | Avant IA (2022) | Après IA (2024) | Note /10 |
|---------|----------------|-----------------|----------|
| Fraudes détectées par mois | 50 | 2 000 | 10/10 |
| Temps de détection d'une fraude | 6 mois | 24 heures | 10/10 |
| Taux de détection des fraudes | 5% | 87% | 9/10 |
| Pertes liées à la fraude | 15 Mds GNF/mois | 3 Mds GNF/mois | 9/10 |
| Recouvrement financier | 500M GNF/mois | 8 Mds GNF/mois | 10/10 |

**Score total d'amélioration** : 🚀 **+3900% de fraudes détectées**

---

## Architecture technique déployée

### Phase 1 : Smart Meters (Compteurs Intelligents)
**Remplacement de 50 000 compteurs**

| Ancien compteur | Smart Meter |
|----------------|-------------|
| Roue qui tourne | Envoie données toutes les 15 min |
| Agent lit à la main 1x/mois | Détecte anomalies automatiquement |
| Aucune donnée temps réel | Alerte automatique |
| | Communication GSM/4G |

**Coût** : 10 000 GNF/compteur × 50 000 = 500 millions GNF

### Phase 2 : Plateforme IA de Détection
**L'IA analyse en temps réel les profils de consommation**

**Signal normal** (Maison Mme Barry, 4 personnes) :
- 06h : 2 kWh (douches, café)
- 12h : 3 kWh (cuisine)
- 20h : 5 kWh (pic - TV, lumières)
- 23h : 0,5 kWh (veille)

**Signal suspect** (Maison M. Diallo, 2 personnes déclarées) :
- 06h : 15 kWh ⚠️
- 12h : 20 kWh ⚠️
- 20h : 35 kWh 🚨
- 23h : 25 kWh 🚨
- **IA** : "Consommation × 5 par rapport aux voisins = SUSPECT"

### Phase 3 : Algorithmes de Détection (10 algorithmes)

| Algorithme | Principe | Exemple |
|------------|----------|---------|
| **Consommation Zéro Suspect** | Compteur affiche 0 kWh mais maison occupée | Branchement sauvage |
| **Profil Anormal** | Maison 2 chambres consomme 500 kWh/mois (normale = 150) | Atelier clandestin |
| **Baisse Subite** | 200 kWh/mois pendant 2 ans → soudain 50 kWh/mois | Compteur trafiqué |
| **Pic Nocturne** | Consommation 20 kWh entre 23h-6h (restaurant fermé) | Activité non déclarée |
| **Tarif Frauduleux** | Mosquée consomme 800 kWh/mois (normale = 50-100) | Faux abonnement |
| **Pattern Trop Parfait** | Pic exact TOUJOURS à 12h15, jamais de variation | Compteur reprogrammé (Arduino) |

---

## Cas réel : Détection automatique

**15 Août 2024, 03h47** 🚨

**ALERTE IA**
- Abonné : Restaurant Le Bon Goût (Matam, Conakry)
- Anomalie : Consommation 02h-04h = 45 kWh
- Restaurant fermé selon déclaration
- Profil suspect : +500% vs normale
- **Probabilité fraude : 94%**

**Actions automatiques** :
✅ Photo satellite analysée : Bâtiment agrandi (non déclaré)
✅ Historique : Consommation × 3 en 6 mois
✅ Comparaison 10 restaurants similaires : ANORMAL
✅ Recommandation : VISITE TERRAIN URGENTE

**06h00** : Équipe EDG arrive
**Découverte** : Restaurant + Cyber café + Atelier soudure cachés !
**Fraude estimée** : 25 millions GNF/an

---

## Résultats clés (6 mois, Janv-Juin 2024)

| Indicateur | Avant IA | Après IA | Évolution |
|------------|----------|----------|------------|
| Fraudes détectées/mois | 50 | 2 000 | **+3900%** 🚀 |
| Temps de détection | 6 mois | 24 heures | **-99%** ⚡ |
| Taux de détection | 5% | 87% | **+1640%** ✅ |
| Pertes liées à la fraude | 15 Mds/mois | 3 Mds/mois | **-80%** 💰 |
| Recouvrement | 500M/mois | 8 Mds/mois | **+1500%** 💰 |

**Économies sur 6 mois** : 72 milliards GNF  
**ROI** : **Moins de 2 mois !** 🎯

---

## Impact social inattendu

**Avant** :
- Clients honnêtes payaient pour les fraudeurs
- Factures trop élevées
- Colère de la population

**Après (fraudes réduites de 80%)** :
- EDG baisse les tarifs de **15%** !
- Tout le monde gagne :
  - Clients honnêtes : Paient moins ✅
  - EDG : Gagne plus ✅
  - Guinée : Électricité pour tous ✅

---

## L'IA apprend en continu

### Mars 2024 : Nouvelle fraude détectée

**Fraudeurs intelligents** : Ils copient un profil normal
- Consommation le jour (normal)
- Zéro la nuit (normal)

**MAIS l'IA détecte** :
- Pic exact TOUJOURS à 12h15 (trop précis = robot !)
- Jamais de variation (suspect)

**Enquête** : Compteur reprogrammé avec Arduino !

**IA mise à jour** : Détecte maintenant les "patterns trop parfaits"

---

## Recommandation finale

✅ **LANCER** le projet IA anti-fraude (TRÈS URGENT)

### Justification (3 arguments clés)

1. **Pertes colossales** : 180 milliards GNF/an partent en fumée à cause des fraudes. C'est insoutenable pour une entreprise publique.

2. **ROI exceptionnel** : 800 millions GNF investis → 12 milliards GNF économisés par mois. Rentabilisé en **moins de 20 jours** !

3. **Bénéfice social** : Réduction des fraudes = baisse des tarifs pour tous. Les clients honnêtes ne paient plus pour les fraudeurs.

---

## Leçons pour entreprises

| Leçon | Enseignement |
|-------|---------------|
| **IA > Humain pour tâches répétitives** | 1 agent détecte 2 fraudes/jour. IA détecte 2000 fraudes/mois = travail de 30 agents 24/7 |
| **Données = Carburant IA** | Plus de compteurs intelligents = plus de données = IA plus précise (60% → 94%) |
| **ROI ultrarapide** | 800M GNF investis → 12 Mds GNF/mois économisés → rentabilisé en 20 jours |
| **IA éthique** | Transparence : 99% des clients acceptent le compteur intelligent |
| **Humain + IA = Parfait** | IA détecte → Humain vérifie → Décision (pas de sanction automatique, 13% faux positifs) |

---

## Plan d'action pour une IA anti-fraude dans votre secteur

### Étape 1 : Identifier les types de fraudes

| Type de fraude | Fréquence | Perte/an | Détectable par IA ? |
|----------------|-----------|----------|---------------------|
| Ex: Fausses factures | Fréquent | 50M GNF | OUI (patterns) |
| 1. Branchement sauvage | Très fréquent | 100Mds+ | OUI (conso zéro) |
| 2. Compteur trafiqué | Fréquent | 50Mds+ | OUI (baisse subite) |
| 3. Faux abonnement | Occasionnel | 10Mds+ | OUI (profil anormal) |

### Étape 2 : Concevoir un algorithme de détection

**Fraude ciblée** : Branchement sauvage

**Signaux suspects (5 minimum)** :
1. Compteur affiche 0 kWh pendant 3+ jours
2. Maison visiblement occupée (lumières le soir)
3. Aucune variation de consommation (trop constant)
4. Voisins avec consommation normale (20-30 kWh)
5. Pas de déclaration de départ/absence

**Seuil d'alerte** : 4/5 signaux suspects  
**Action automatique** : Envoyer équipe vérification terrain

### Étape 3 : Budget et ROI estimé

| Poste | Coût |
|-------|------|
| Collecte données (capteurs, logiciel) | 500M GNF |
| Plateforme IA (licence/développement) | 200M GNF |
| Formation équipe | 100M GNF |
| **TOTAL INVESTISSEMENT** | **800M GNF** |

**Gains attendus** :
- Fraudes détectées/mois : 2 000
- Montant récupéré/mois : 12 Mds GNF
- **ROI en moins de 2 mois**

---

## Indicateurs de réussite du projet EDG

☐ 50 000 compteurs intelligents installés  
☐ Plateforme IA opérationnelle 24/7  
☐ Taux de détection des fraudes > 80%  
☐ Réduction des pertes > 70%  
☐ ROI atteint en moins de 3 mois  
☐ Baisse des tarifs pour les clients honnêtes
