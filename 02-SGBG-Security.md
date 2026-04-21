# Cas Étude 2 : SOCIÉTÉ GÉNÉRALE GUINÉE

## Résumé de l'énoncé

- **Incident déclencheur (Mai 2022)** : Un employé clique sur un email de phishing. Les hackeurs tentent de transférer 500 millions GNF vers l'étranger. Transaction bloquée de justesse par la BCRG.
- **Audit de juin 2022** : 47 vulnérabilités critiques détectées. Note globale : 2/10 🔴
- **Budget total investi** : 2,45 milliards GNF
- **Attaque du 15 mars 2024** : 247 tentatives de connexion en 3 minutes. 0 GNF volé grâce aux nouvelles mesures.

## Objectif

Sécuriser l'infrastructure IT de la banque après la tentative d'attaque de mai 2022, pour protéger les actifs des clients et la réputation de l'établissement.

---

## Audit initial (Juin 2022) - État des lieux catastrophique

| Critère | État | Note /10 | Action nécessaire |
|---------|------|----------|-------------------|
| Mots de passe | NON (mots de passe faibles, post-it) | 1/10 | Imposer un gestionnaire de mots de passe |
| 2FA | NON | 0/10 | Installer Login + Mot de passe + Code SMS |
| Formation | NON (0% employés formés) | 0/10 | Lancer 2 jours de formation obligatoire |
| IDS | NON (aucune détection d'intrusion) | 0/10 | Déployer IBM QRadar (surveillance 24/7) |
| Cloud | NON (sauvegardes dans même bâtiment) | 2/10 | Migrer vers Microsoft Azure en Europe |

**Score Total : 10/100** (❌ DANGER ! Vulnérabilité critique)

---

## Architecture technique déployée (Juin 2022 - Mars 2024)

### Action 1 : Authentification 2 Facteurs (2FA)
**Budget** : 50 millions GNF | **Délai** : 1 mois

| Avant | Après |
|-------|-------|
| Login + Mot de passe | Login + Mot de passe + Code SMS |

**Résultat** : Même si un hackeur vole le mot de passe, il ne peut PAS se connecter sans le téléphone de l'employé. **-99% de risque de piratage.**

### Action 2 : Formation OBLIGATOIRE pour tous les employés
**Budget** : 300 millions GNF | **Délai** : 3 mois

**Programme (2 jours/employé)** :
- **Jour 1** : Reconnaître le phishing (20 exemples d'emails frauduleux, quiz, vérification des liens)
- **Jour 2** : Bonnes pratiques (mots de passe forts, gestionnaire Bitwarden, verrouillage PC)

**Résultat** : 94% de réussite au test final. 0% employés non formés.

### Action 3 : Système de Détection d'Intrusion (IDS)
**Budget** : 800 millions GNF | **Délai** : 6 mois

**Technologie** : IBM QRadar

**L'IA surveille 24/7** :
- Connexions inhabituelles (Conakry puis Paris 5 min après = SUSPECT)
- Transferts anormaux (jamais fait puis 500M GNF = SUSPECT)
- Horaires bizarres (connexion à 3h du matin = SUSPECT)

**Cas réel (12 Septembre 2023, 02h47)** :
- 🚨 ALERTE : M. Diallo (Comptable) tente un transfert de 380 millions GNF vers le Nigéria
- Heure suspecte (02h47 - jamais connecté après 18h)
- Décision IA : BLOQUER + Alerter chef sécurité
- **Résultat** : M. Diallo confirme n'avoir rien fait. Compte piraté. 380 millions GNF sauvés.

### Action 4 : Sauvegardes Cloud Sécurisées
**Budget** : 500 millions GNF/an | **Délai** : 2 mois

| Avant | Après |
|-------|-------|
| Sauvegardes sur serveur local | Sauvegardes sur Microsoft Azure (Europe) |
| 1 fois/semaine | 3 fois par jour |
| Récupération en 2 jours | Récupération en 2 heures |
| Vulnérable à incendie/vol | Chiffrement militaire |

### Action 5 : Pentesting Mensuel
**Budget** : 50 millions GNF/an

**Principe** : Société Générale PAYE des hackers éthiques pour ATTAQUER la banque !

**Processus mensuel** :
1. Hackers éthiques attaquent pendant 1 semaine
2. Ils trouvent les failles
3. Rapport détaillé à l'équipe IT
4. Corrections immédiates
5. Re-test le mois suivant

**Évolution des vulnérabilités** :
- Mai 2022 : 47 vulnérabilités critiques
- Juin 2023 : 12 vulnérabilités
- Mars 2024 : 2 vulnérabilités (mineures)

---

## Retour au 15 Mars 2024 (L'attaque)

**14h30** : Alerte reçue - 247 tentatives de connexion en 3 minutes (Chine, Russie, Nigeria)

**14h32** : Actions immédiates
- Système IDS bloque automatiquement toutes les IP suspectes
- Emails envoyés aux clients concernés
- Équipe cybersécurité mobilisée
- Analyse des logs

**15h00** : Attaque repoussée

**Résultat** :
- 0 GNF volé ✅
- 0 compte piraté ✅
- Clients informés en temps réel ✅
- Attaquants identifiés et signalés à Interpol ✅

**Ce qui aurait pu arriver SANS les mesures de 2022** :
- 2 milliards GNF volés
- 500+ comptes compromis
- Panique bancaire
- Faillite possible

---

## Résultats clés (2022-2024)

| Indicateur | 2022 (Avant) | 2024 (Après) | Évolution |
|------------|--------------|--------------|------------|
| Attaques réussies | 1 (Mai 2022) | 0 | **-100%** ✅ |
| Tentatives attaques/mois | Non détectées | 50-100 (100% détectées) | **Détection totale** |
| Temps de détection | Jamais | 2 minutes | ✅ |
| Temps de réaction | Aucun | 5 minutes | ✅ |
| Employés formés | 0% | 100% | **+100%** ✅ |
| Argent sauvé (2 ans) | - | 5+ milliards GNF | 💰 |

---

## ROI de la cybersécurité

### Investissement total (2022-2024)

| Poste | Coût |
|-------|------|
| Audit | 200M GNF |
| 2FA | 50M GNF |
| Formation | 300M GNF |
| IDS (IBM QRadar) | 800M GNF |
| Cloud sauvegardes | 1 Md GNF |
| Pentesting | 100M GNF |
| **TOTAL** | **2,45 Mds GNF** |

### Bénéfices (2022-2024)

| Bénéfice | Montant |
|----------|---------|
| Attaques déjouées | 5+ Mds GNF sauvés |
| Réputation préservée | Inestimable |
| Conformité BCRG | Obligatoire |
| Confiance clients | +25% nouveaux comptes |

**ROI : +200%** 🚀

---

## Recommandation finale

✅ **LANCER le projet de cybersécurité (URGENCE ABSOLUE)**

### Justification (3 arguments clés)

1. **Une seule attaque réussie peut coûter plus de 2 milliards GNF** : L'attaque évitée de justesse en mai 2022 aurait pu être catastrophique. Le coût de l'inaction est bien supérieur à l'investissement.

2. **La conformité BCRG est obligatoire** : La Banque Centrale impose désormais des normes de cybersécurité. Ne pas s'y conformer expose à des sanctions et au retrait d'agrément.

3. **ROI prouvé et ultrarapide** : 2,45 milliards investis → plus de 5 milliards d'attaques déjouées en 2 ans. Rentabilité dépassée en moins d'un an.

---

## Leçons pour entreprises

| Leçon | Enseignement |
|-------|---------------|
| **La cybersécurité n'est PAS une dépense, c'est un investissement** | "2,5 milliards paraissent chers. Mais 5 milliards perdus + réputation détruite = BEAUCOUP plus cher !" - Ibrahima Sow |
| **L'humain est le maillon faible** | 89% des cyberattaques réussies commencent par un CLIC d'employé. Former = priorité #1. |
| **Détection rapide > Prévention parfaite** | On ne peut pas empêcher toutes les attaques. Mais on peut les détecter en 2 minutes et réagir en 5. |
| **Testez-vous avant qu'un vrai hackeur le fasse** | Pentesting = vaccin. Ça fait un peu mal au début, mais ça sauve la vie. |
| **Cloud ≠ Risque, Cloud = Solution** | Microsoft Azure est 1000× plus sécurisé qu'un serveur local. |

---

## Indicateurs de réussite du projet

☐ 2FA déployé sur 100% des comptes  
☐ 100% des employés formés et certifiés  
☐ IDS opérationnel 24/7  
☐ Sauvegardes cloud actives avec reprise < 2h  
☐ Pentesting mensuel effectué  
☐ 0 attaque réussie sur 12 mois consécutifs  
☐ Conformité BCRG validée
