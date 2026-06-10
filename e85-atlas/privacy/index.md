---
layout: page
title: Politique de confidentialité
---

**Version 1.0 — en vigueur au : 10 juin 2026**

## 1. Responsable de traitement

Éditeur de l'application **E85 Atlas** :
- **Alpes Reprog**
- Adresse : 195 ZA du Bout du Lac, 74210 Lathuile
- SIRET : 979 023 579 RCS Annecy
- Contact : contact@alpesreprog.com
- Représentant légal : Nicolas Decoene

Délégué à la protection des données (DPO) : non désigné (la désignation n'est pas obligatoire au sens de l'article 37 RGPD compte tenu du volume et de la nature des traitements). Pour toute question relative à vos données personnelles, vous pouvez contacter directement l'adresse ci-dessus.

## 2. Données que nous collectons

### 2.1. Données que vous nous fournissez directement

| Donnée | Finalité | Base légale | Obligatoire ? |
|---|---|---|---|
| Position GPS approximative (au niveau de la ville) | Afficher les stations proches sur la carte | Consentement (iOS) | Non — fonctionnalité dégradée si refus |
| Position GPS précise | Calculer la distance exacte vers chaque station | Consentement (iOS) | Non |
| Favoris de stations | Mémoriser vos stations préférées | Exécution du service | Non |
| Signalements (rupture, prix erroné, fermeture) | Améliorer la qualité des données communautaires | Intérêt légitime + consentement implicite via soumission | Non |
| Email (si abonnement Premium) | Gestion de la facturation App Store, communication essentielle uniquement | Exécution du contrat | Oui si abonnement |

### 2.2. Données collectées automatiquement

| Donnée | Finalité | Base légale | Prestataire |
|---|---|---|---|
| Version iOS, modèle d'appareil, langue | Assurer la compatibilité et corriger les bugs par segment | Intérêt légitime | TelemetryDeck (analytique anonyme) |
| Événements d'usage anonymes (ouverture écran, action carte) | Comprendre l'usage général, prioriser les améliorations | Intérêt légitime | TelemetryDeck |
| Rapports de plantage | Diagnostiquer et corriger les plantages | Intérêt légitime | Sentry |
| Identifiant publicitaire Apple (IDFA) | Personnalisation limitée des publicités AdMob | **Consentement explicite** via ATT | Google AdMob |

**Position précise** : demandée uniquement au premier usage de la carte, peut être refusée ou révoquée à tout moment dans les Réglages iOS → Confidentialité → Services de localisation → E85 Atlas.

**Identifiant publicitaire (IDFA)** : demandé via la fenêtre système App Tracking Transparency (ATT) au premier lancement. Si vous refusez, les publicités sont maintenues mais non personnalisées, et aucun identifiant publicitaire n'est transmis.

### 2.3. Données que nous NE collectons PAS

- Pas de nom, prénom, numéro de téléphone, adresse postale.
- Pas de compte utilisateur en v1.0 — l'app fonctionne sans identification.
- Pas de liste de vos trajets, pas d'historique GPS enregistré côté serveur.
- Pas de cookies (application mobile native, sans stockage web).

## 3. Destinataires et transferts

| Destinataire | Données transmises | Localisation serveurs | Encadrement juridique |
|---|---|---|---|
| **Alpes Reprog** (éditeur) | Signalements anonymes, favoris | France | — |
| **Cloudflare Inc.** | Requêtes HTTP anonymisées vers l'API E85 Atlas | Edge mondial, point de présence préférentiel Paris | Clauses contractuelles types UE (SCC) + Data Processing Addendum Cloudflare |
| **TelemetryDeck GmbH** | Événements d'usage anonymes | Allemagne, Union Européenne | Basé en UE, conforme RGPD nativement |
| **Functional Software Inc.** (Sentry) | Rapports de plantage, version app | UE (région Francfort sélectionnée) | SCC + DPA Sentry |
| **Google LLC / Ireland Ltd.** (AdMob) | IDFA (si consentement), événements publicitaires | US + UE | SCC + conformité EU-US Data Privacy Framework |
| **Apple Inc.** | Gestion des abonnements et paiements | US + Irlande | SCC + conformité EU-US Data Privacy Framework |

Pour les transferts hors Union Européenne (notamment États-Unis), nous nous appuyons sur les mécanismes suivants :
- **Clauses contractuelles types** (décision UE 2021/914) acceptées par chaque prestataire.
- **Data Privacy Framework** (DPF) UE-US pour les prestataires certifiés (Google, Apple).

## 4. Durées de conservation

| Catégorie | Durée |
|---|---|
| Signalements (anonymes) | 12 mois glissants |
| Logs serveur Cloudflare | 30 jours |
| Événements TelemetryDeck | 12 mois |
| Rapports de plantage Sentry | 90 jours |
| Abonnement Apple / facture | Durée légale comptable : 10 ans |
| Données locales iOS (favoris, signalements en attente) | Jusqu'à désinstallation de l'app ou effacement manuel |

## 5. Vos droits

Conformément au RGPD et à la loi Informatique et Libertés, vous disposez des droits suivants :

- **Droit d'accès** : obtenir confirmation du traitement et copie de vos données.
- **Droit de rectification** : corriger des données inexactes.
- **Droit à l'effacement** : demander la suppression de vos données (sauf obligation légale).
- **Droit à la limitation** : demander la suspension temporaire d'un traitement contesté.
- **Droit d'opposition** : vous opposer à un traitement fondé sur l'intérêt légitime.
- **Droit à la portabilité** : recevoir vos données dans un format structuré.
- **Droit de retirer votre consentement** à tout moment (ATT, localisation) via les Réglages iOS.

**Pour exercer ces droits**, écrivez à contact@alpesreprog.com en précisant votre demande. Nous répondrons dans un délai maximum d'un mois.

En cas de réponse insatisfaisante, vous pouvez saisir la **CNIL** (Commission Nationale de l'Informatique et des Libertés) — www.cnil.fr — 3 place de Fontenoy, 75007 Paris.

## 6. Sécurité

- Toutes les communications entre l'app et nos serveurs sont chiffrées en **TLS 1.3**.
- Les signalements utilisateurs sont stockés sans corrélation avec une identité.
- L'accès aux données serveur est restreint par des clés API, renouvelées à intervalle régulier.
- Aucune donnée personnelle n'est stockée en clair côté serveur.

## 7. Publicités et Apple App Tracking Transparency

L'application E85 Atlas, dans sa version gratuite, contient des emplacements publicitaires servis par **Google AdMob** avec des filtres catégoriels stricts (exclusion des secteurs sensibles : jeux d'argent, alcool, rencontres, politique, santé).

**Personnalisation publicitaire** : par défaut, Apple exige votre **consentement explicite** via une fenêtre ATT (App Tracking Transparency) pour accéder à votre identifiant publicitaire. En cas de refus :
- Les publicités continuent de s'afficher.
- Elles ne sont **pas personnalisées** en fonction de vos comportements.
- Aucun identifiant n'est transmis à Google AdMob.

**Retrait total de la publicité** : **E85 Atlas Premium** (abonnement annuel 4,99 €/an ou accès à vie 19,99 €/29,99 €) supprime **toute publicité** de l'application.

## 8. Modifications de la politique

Nous nous réservons le droit de modifier cette politique de confidentialité pour l'adapter aux évolutions réglementaires ou fonctionnelles. Toute modification substantielle fera l'objet d'une notification dans l'application au prochain lancement. La date de mise à jour figure en tête de document.

## 9. Contact

Pour toute question relative à vos données personnelles :
- Email : contact@alpesreprog.com
- Objet recommandé : « Données personnelles E85 Atlas »
