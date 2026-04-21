# Glossaire Technique

## Termes généraux

| Terme | Définition | Formule / Exemple |
|-------|-------------|-------------------|
| **ROI** (Return on Investment) | Indicateur financier mesurant la rentabilité d'un investissement. Exprime le gain généré par rapport au coût investi. | (Gain – Coût) / Coût × 100 |
| **KPI** (Key Performance Indicator) | Indicateur clé de performance. Mesure quantitative permettant d'évaluer l'efficacité d'une action ou d'un processus. | Ex: Taux de conversion, CTR, panier moyen |
| **CA** | Chiffre d'affaires. Montant total des ventes réalisées sur une période donnée (mois, trimestre, année). | CA = Prix × Quantité vendue |
| **GNF** | Franc guinéen. Monnaie officielle de la République de Guinée. | Code ISO : GNF |
| **BCRG** | Banque Centrale de la République de Guinée. Autorité de régulation financière et monétaire. | Organisme de contrôle des banques et institutions financières |

---

## Cas 1 : Orange Money (Fintech)

| Terme | Définition | Application dans le cas |
|-------|-------------|------------------------|
| **Mobile Money** | Service de paiement et de transfert d'argent via téléphone mobile, sans nécessiter de compte bancaire. | Orange Money permet d'envoyer de l'argent, payer des factures, acheter sans cash |
| **USSD** (Unstructured Supplementary Service Data) | Protocole de communication permettant d'utiliser des services mobiles sans connexion internet. | Code `*#144#` → Menu complet accessible même sans smartphone |
| **Agent Mobile Money** | Commerçant ou particulier habilité à effectuer des dépôts et retraits d'argent pour le compte d'un opérateur mobile. | 25 000 agents en Guinée (ex: Mamadou à Ratoma) |
| **Inclusion financière** | Accès des populations non bancarisées à des services financiers simples, sécurisés et abordables. | 70% des Guinéens sans compte bancaire → 8M utilisateurs OM |
| **Transaction mobile** | Opération financière (transfert, paiement, retrait) effectuée via téléphone. | 1 million+ transactions/jour en 2024 |
| **Commission agent** | Rémunération perçue par l'agent pour chaque transaction effectuée. | 50 000 GNF/jour pour Mamadou au 30ème jour |

---

## Cas 2 : Société Générale Guinée (Cybersécurité)

| Terme | Définition | Application dans le cas |
|-------|-------------|------------------------|
| **2FA** (Two-Factor Authentication) | Authentification à deux facteurs. Nécessite un mot de passe + un second élément (code SMS, empreinte, etc.). | Login + Mot de passe + Code SMS envoyé sur téléphone |
| **IDS** (Intrusion Detection System) | Système de détection d'intrusion. Surveille le réseau 24h/24 pour identifier des comportements suspects. | IBM QRadar déployé chez SG Guinée |
| **Phishing** | Technique d'arnaque où un faux email (ou SMS) incite la victime à cliquer sur un lien ou à fournir ses identifiants. | Email "RH" demandant informations bancaires (Mai 2022) |
| **Pentesting** (Penetration Testing) | Test d'intrusion. Des hackers éthiques sont payés pour attaquer le système et découvrir ses failles. | Tests mensuels chez SG Guinée (50M GNF/an) |
| **Logs** | Fichiers d'historique qui enregistrent toutes les actions et connexions sur un système informatique. | Avant : gardés 7 jours. Après : gardés indéfiniment |
| **Cloud** | Stockage et traitement des données sur des serveurs distants (ex: Microsoft Azure) plutôt que sur site. | Migration vers Azure Europe |
| **Sauvegarde Cloud** | Copie des données stockée hors site (souvent dans un autre pays) pour les protéger contre incendie, vol ou panne. | 3 sauvegardes/jour sur Azure |
| **Vulnérabilité critique** | Faille de sécurité majeure permettant un accès non autorisé au système. | 47 vulnérabilités détectées en juin 2022 |
| **Hacker éthique** | Expert en cybersécurité autorisé à attaquer un système pour en tester les faiblesses. | Équipe de pentesting mensuel |
| **IP suspecte** | Adresse internet identifiée comme source d'activité malveillante (attaques, tentatives de connexion). | Blocage automatique des IPs de Chine, Russie, Nigeria |

---

## Cas 3 : Jumia Guinée (Big Data)

| Terme | Définition | Application dans le cas |
|-------|-------------|------------------------|
| **Big Data** | Analyse de très grands volumes de données (structurées et non structurées) pour en extraire des tendances et prédictions. | 50 millions de points de données sur 200 000 clients |
| **CTR** (Click-Through Rate) | Taux de clics. Pourcentage de personnes qui cliquent sur un email ou une publicité. | (Clics / Emails envoyés) × 100 = 2% → 23% |
| **Taux de conversion** | Pourcentage de visiteurs qui réalisent une action d'achat sur le site. | (Achats / Visiteurs) × 100 = 0,5% → 8% |
| **Personnalisation** | Adaptation des offres et recommandations en fonction du profil, de l'historique et du comportement de chaque client. | 12 profils types (Fashionista, Bricoleur, etc.) |
| **Cross-selling** | Vente croisée. Proposer des produits complémentaires à ce que le client achète. | Couches bébé → recommandation lait, vêtements, jouets |
| **Machine Learning** | Branche de l'IA où l'algorithme apprend à partir des données et s'améliore automatiquement avec le temps. | Modèles TensorFlow entraînés sur 50M+ données |
| **TensorFlow** | Bibliothèque de programmation (Python) développée par Google pour créer des modèles d'intelligence artificielle. | Framework principal de l'IA Jumia |
| **Data Lake** | Zone de stockage massif contenant toutes les données brutes d'une entreprise (structurées et non structurées). | 2 pétaoctets sur AWS Afrique du Sud |
| **Pattern** | Schéma ou tendance récurrente détectée par l'IA dans les données. | "Jeudis Soir", "Effet Salaire", "Panier Maman" |
| **Profil client** | Segmentation d'un client selon ses caractéristiques (âge, sexe, localisation) et comportements (achats, consultations). | 12 profils types créés par l'algorithme |
| **Prédiction IA** | Estimation par l'algorithme de la probabilité qu'un événement se produise (achat, déménagement, grossesse). | "90% probabilité d'achat dans les 48h" |
| **Marketing automation** | Envoi automatique d'emails, notifications push et promotions déclenché par des comportements clients. | Email à Kadiatou 20h → achat le lendemain |

---

## Cas 4 : AGL Conakry Terminal (Cloud Computing)

| Terme | Définition | Application dans le cas |
|-------|-------------|------------------------|
| **Cloud Computing** | Accès à des ressources informatiques (serveurs, stockage, logiciels) via internet, sans posséder le matériel. | Migration AGL vers Microsoft Azure |
| **Microsoft Azure** | Plateforme cloud de Microsoft (concurrent d'AWS et Google Cloud). Datacenters en Europe et dans le monde. | Datacenters en Europe pour sauvegarde des données |
| **Power BI** | Outil de visualisation de données (dashboard) qui affiche des indicateurs en temps réel. | Dashboard portuaire accessible depuis Dubaï |
| **Disaster Recovery** | Plan de reprise après sinistre. Capacité à restaurer l'activité après un incident (incendie, panne, cyberattaque). | Reprise en 10 minutes (vs 6 mois avant) |
| **Scalabilité / Évolutivité** | Capacité du système à augmenter automatiquement ses performances (serveurs, bande passante) en cas de forte demande. | Azure ajoute capacité automatique (Black Friday) |
| **QR Code** | Code-barres en 2D (carré) qui stocke une information lisible par scan. Utilisé pour identifier chaque conteneur. | Scan QR code → données conteneur en 2 secondes |
| **Sur site (On-premise)** | Infrastructure informatique installée physiquement dans les locaux de l'entreprise (serveurs, climatisation, maintenance). | 50 serveurs physiques avant migration |
| **Green IT** | Démarche visant à réduire l'impact environnemental des technologies (ex: datacenter alimenté à l'énergie solaire). | -80% d'impact écologique après migration |
| **Temps réel** | Données mises à jour instantanément, sans délai. | Dashboard Power BI : données actualisées en continu |
| **Sauvegarde incrémentale** | Sauvegarde uniquement des données modifiées depuis la dernière sauvegarde (vs sauvegarde complète). | 3 sauvegardes par jour sur Azure |
| **Chiffrement militaire** | Niveau de sécurité maximal pour les données (AES-256, normes gouvernementales). | Données bancaires protégées sur Azure |

---

## Cas 5 : EDG (Intelligence Artificielle)

| Terme | Définition | Application dans le cas |
|-------|-------------|------------------------|
| **IA** (Intelligence Artificielle) | Ensemble d'algorithmes capables d'analyser des données, de détecter des anomalies et de prendre des décisions automatisées. | IA anti-fraude EDG (10 algorithmes) |
| **Smart Meter** | Compteur intelligent. Envoie automatiquement les données de consommation toutes les 15 minutes via réseau mobile. | 50 000 compteurs intelligents installés |
| **Algorithme** | Série d'instructions logiques qu'un programme informatique exécute pour résoudre un problème spécifique. | 10 algorithmes de détection (conso zéro, profil anormal, etc.) |
| **Faux positif** | Situation où l'IA détecte une fraude qui n'existe pas (ex: famille nombreuse = consommation élevée mais légitime). | Taux de 13% chez EDG |
| **Branchement sauvage** | Raccordement électrique illégal effectué avant le compteur pour ne pas payer. | Détecté par l'algorithme "Consommation Zéro Suspect" |
| **Profil de consommation** | Modèle type de consommation électrique en fonction de la taille du foyer, des appareils, des heures d'activité. | Maison 2 chambres : 150 kWh/mois (normal) |
| **Pattern** | Schéma ou tendance récurrente détectée par l'IA dans les données. | Pic exact à 12h15 tous les jours (compteur reprogrammé) |
| **Anomalie** | Comportement anormal détecté par rapport au profil attendu. | Consommation × 5 par rapport aux voisins |
| **Taux de détection** | Pourcentage de fraudes identifiées par l'IA par rapport au total des fraudes existantes. | 5% → 87% après IA |
| **Recouvrement** | Montant financier récupéré suite à la détection et à la régularisation des fraudes. | 500M GNF/mois → 8 Mds GNF/mois |
| **Réseau GSM/4G** | Réseau de téléphonie mobile utilisé par les Smart Meters pour transmettre les données. | Communication compteurs intelligents |
| **Apprentissage continu** | Capacité de l'IA à s'améliorer automatiquement avec l'ajout de nouvelles données et la détection de nouveaux types de fraude. | Précision : 60% (2023) → 94% (2024) |

---

## Abréviations courantes

| Abréviation | Signification | Utilisation |
|-------------|---------------|-------------|
| **GNF** | Franc guinéen | Tous les cas |
| **Mds** | Milliards | Orange Money, SG, EDG |
| **M** | Millions | Jumia, AGL |
| **K** | Kilo (mille) | Ex: 500K GNF = 500 000 GNF |
| **h** | Heure | Temps de traitement, délais |
| **min** | Minute | Temps par conteneur (AGL) |
| **s** | Seconde | Scan QR code |
| **vs** | Versus (contre, par opposition à) | Comparaisons avant/après |
| **ex:** | Exemple | Illustrations |
| **IA** | Intelligence Artificielle | EDG, Jumia |
| **IT** | Information Technology (Informatique) | SG, AGL |
| **SMS** | Short Message Service (texte) | 2FA, Orange Money |
| **4G** | Réseau mobile haut débit | Smart Meters EDG |
| **QR** | Quick Response (réponse rapide) | AGL Conakry Terminal |
| **API** | Application Programming Interface | Communication entre systèmes |
| **SaaS** | Software as a Service | Cloud (AGL) |
| **AWS** | Amazon Web Services | Cloud (Jumia) |
| **RGPD** | Règlement Général sur la Protection des Données | Éthique Jumia |

---

## Tableau récapitulatif des formules

| Indicateur | Formule | Exemple issu des cas |
|------------|---------|----------------------|
| **Évolution (%)** | (Nouvelle valeur – Ancienne valeur) / Ancienne valeur × 100 | (23% – 2%) / 2% × 100 = +1050% (Jumia) |
| **ROI** | (Gain net – Coût) / Coût × 100 | (5 Mds – 2,45 Mds) / 2,45 Mds × 100 = +200% (SG) |
| **Rentabilité (mois)** | Investissement / Gain net mensuel | 800M / 12M = moins de 2 mois (EDG) |
| **Taux de conversion** | (Actions / Expositions) × 100 | (8 / 100) × 100 = 8% (Jumia) |
| **Taux de clics (CTR)** | (Clics / Emails envoyés) × 100 | (23 / 100) × 100 = 23% (Jumia) |
| **Part de marché** | (Volume entreprise / Marché total) × 100 | (8M / 13M) × 100 = 60% (Orange Money) |
| **Taux de détection** | (Fraudes détectées / Fraudes totales) × 100 | (2000 / 2300) × 100 = 87% (EDG) |
| **Panier moyen** | CA total / Nombre de commandes | 950M / 1,22M = 780K GNF (Jumia) |
| **Temps de traitement** | (Temps avant – Temps après) / Temps avant × 100 | (45 – 12) / 45 × 100 = -73% (AGL) |
