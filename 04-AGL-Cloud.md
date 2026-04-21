# Cas Étude 4 : AGL CONAKRY TERMINAL

## Résumé de l'énoncé

- **Problème initial (2020)** : 45 minutes par conteneur traité manuellement (papier, Excel, tampon douane). Un bateau de 200 conteneurs = 6 jours de retard.
- **Coût du retard** : 50 000 USD/jour de pénalité = 300 000 USD par bateau bloqué.
- **Déclencheur COVID-19 (Mai 2020)** : Fermeture du port → accès serveur local impossible → perte de 5 millions USD en 2 semaines.
- **Budget du projet** : 1 milliard GNF
- **Partenaire technologique** : Microsoft Azure

## Objectif

Migration complète de l'infrastructure IT du port vers le cloud pour :
- Éliminer les processus papier
- Permettre le télétravail et l'accès distant
- Réduire les temps d'arrêt et les coûts
- Sécuriser les données contre les sinistres (incendie, inondation)

---

## Évaluation du projet (Avant/Après)

| Critère | Avant (2020) | Après (2021) | Note /10 |
|---------|--------------|--------------|----------|
| Temps de traitement par conteneur | 45 minutes | 12 minutes | 9/10 |
| Conteneurs traités par jour | 150 | 400 | 9/10 |
| Taux d'erreur de saisie | 15/jour | 1/semaine | 8/10 |
| Coût IT mensuel | 80M GNF | 50M GNF | 7/10 |
| Accessibilité des données | 8h-18h uniquement | 24/7 partout dans le monde | 10/10 |
| Temps d'arrêt (disponibilité) | 2h/semaine | 5 min/mois | 9/10 |

**Score total d'amélioration** : ⚡ **+73% de gain de productivité**

---

## Architecture technique déployée

### Phase 1 : Migration Infrastructure (3 mois)
- Suppression des 50 serveurs physiques
- Migration vers Microsoft Azure (datacenters en Europe)
- Sauvegarde en temps réel (vs 1 fois/semaine avant)
- Chiffrement militaire des données

### Phase 2 : Application Mobile "AGL Mobile" (2 mois)
- Scan QR code conteneur (2 secondes)
- Données automatiquement chargées depuis le cloud
- Photo du conteneur comme preuve
- Notification instantanée à la douane
- **Temps total : 2 minutes** (vs 45 min avant)

### Phase 3 : Tableau de Bord Power BI (1 mois)
- Dashboard temps réel accessible depuis n'importe où
- Indicateurs : conteneurs traités, bateaux en attente, délai moyen par équipe
- Exemple : Directeur à Dubaï peut superviser Conakry en direct

---

## Résultats clés

| Indicateur | Résultat | Gain |
|------------|----------|------|
| Gain de temps par conteneur | 45 min → 12 min | **-73%** ⚡ |
| Productivité journalière | 150 → 400 conteneurs | **+167%** 🚀 |
| Réduction des erreurs | 15/jour → 1/semaine | **-95%** ✅ |
| Économie sur coûts IT | 80M → 50M GNF/mois | **-37%** 💰 |
| Disponibilité | 8h/24 → 24/7 | **+200%** ♾️ |
| Reprise après sinistre | 6 mois → 10 minutes | **-99%** 🔥 |

**Gain financier annuel** : 500 millions GNF  
**ROI** : **6 mois**

---

## Avantages concrets du cloud démontrés

### Avantage 1 : Accessibilité mondiale
**Cas réel (Décembre 2021)** : Directeur AGL en vacances au Maroc. Douane bloque un conteneur suspect. Il ouvre l'app depuis Marrakech, consulte les documents, autorise le dédouanement. **Temps : 5 minutes** (avant = devoir rentrer à Conakry : vol 6h + trajet).

### Avantage 2 : Collaboration instantanée
**Avant** : AGL Conakry saisit → email à MSC Genève → MSC modifie → renvoie → conflits de version.  
**Après** : 1 seul fichier en ligne, modifications en temps réel, zéro conflit.

### Avantage 3 : Sécurité renforcée
**Incident Avril 2019 (avant cloud)** : Incendie dans bâtiment serveurs → perte de TOUTES les données de 2018 → 6 mois de reconstruction.  
**Avec cloud** : Incendie, inondation, tremblement de terre → données en sécurité en Europe. Reprise activité : **10 minutes**.

### Avantage 4 : Évolutivité automatique
**Black Friday 2022** : Trafic port × 3. Avant = serveurs plantent. Avec cloud = Azure ajoute automatiquement la capacité nécessaire. Coût supplémentaire uniquement pour le mois de décembre (30%).

---

## Recommandation finale

✅ **LANCER** le projet de migration cloud

### Justification (3 arguments clés)

1. **Rentabilité prouvée** : ROI en 6 mois avec 500M GNF d'économies annuelles, sans compter les pénalités évitées (300 000 USD par bateau).

2. **Résilience opérationnelle** : Reprise après sinistre en 10 minutes (vs 6 mois avant). Un incendie ou une inondation ne détruit plus l'activité.

3. **Avantage concurrentiel majeur** : 12 min/conteneur vs 45 min avant. Le port devient le plus efficace d'Afrique de l'Ouest, attirant plus de navires et de clients.

---

## Leçons pour entreprises

| Leçon | Enseignement |
|-------|---------------|
| **Cloud ≠ Compliqué** | Microsoft a formé l'équipe en 2 semaines |
| **Commencez petit** | AGL a migré 1 app test (planning) avant le reste |
| **Cloud = économies** | 50M/mois cloud vs 80M/mois sur site |
| **Disaster Recovery** | Sauvegarder ses données hors site n'est pas un luxe |
| **Green IT** | -80% d'impact écologique (datacenter solaire vs 50 serveurs) |

---

## Plan d'action pour une entreprise qui veut migrer vers le cloud

| Phase | Durée | Application | Coût estimé |
|-------|-------|-------------|--------------|
| 1 | 1 mois | Migration emails (Office 365) | 5M GNF |
| 2 | 2 mois | Application métier critique | 50M GNF |
| 3 | 1 mois | Tableau de bord temps réel (Power BI) | 20M GNF |

**Checklist Cloud Readiness** (évaluez votre entreprise) :
- [ ] Données critiques sur serveur local
- [ ] Besoin d'accès données hors bureau
- [ ] Collaboration avec partenaires externes
- [ ] Coûts IT > 30% du budget
- [ ] Peur de perdre des données (incendie, vol)
- [ ] Croissance rapide prévue

**Score** : 4-6 OUI = Cloud recommandé | 7+ OUI = Cloud URGENT

---

## Indicateurs de réussite du projet AGL

☐ Migration complète vers Azure effectuée  
☐ Application mobile déployée et utilisée par tous les agents  
☐ Temps de traitement conteneur < 15 minutes  
☐ Reprise après sinistre testée et validée (< 30 minutes)  
☐ ROI atteint en moins de 12 mois
