# Custos Studio — Directives pour les Agents IA (Édition Google Play Store)

Ce dépôt (**custos-studio**) contient exclusivement la version commerciale grand public de **Custos** publiée sur le Google Play Store ainsi que son site vitrine officiel.

---

## 1. Identité du Produit
* **Nom de l'application** : Custos
* **Package Play Store (pplicationId)** : com.custos.studio.app
* **Langue par défaut** : Anglais (en-US)
* **Site officiel & Pages légales** : website/ (Next.js 15 déployé sur Vercel → https://custos.joshuanancey.com)
  * /privacy : Privacy Policy (GDPR & Google Play Data Safety)
  * /delete-account : Account & Data Deletion
  * /terms : Terms of Use & Legal Notice

---

## 2. Modèle de Monétisation (Freemium Hybride)
1. **Version Gratuite (Free)** :
   * Financement par **Google Mobile Ads (AdMob)** avec recueil du consentement RGPD européen via **Google UMP (User Messaging Platform)**.
   * **Règle Google Play Ads stricte** : Les publicités (bannières ou interstitiels) ne doivent s'afficher **qu'à l'intérieur des écrans de configuration/statistiques de Custos**, jamais par-dessus d'autres applications ni pendant un écran de blocage critique.
2. **Version Complète / Pro (Achat intégré unique — In-App Purchase non consommable)** :
   * Produit Google Play Billing : custos_full_unlock (paiement unique).
   * Supprime définitivement 100 % des publicités et débloque les fonctionnalités Pro (quotas/couvre-feux illimités, Mode Nucléaire avancé, Accès Partiel illimité).

---

## 3. Séparation Stricte avec Custos Supremus
* Ce dépôt ne contient **ni Guardian (:guardian)**, **ni Device Owner**, **ni scripts ADB personnels**.
* Toute évolution de la forteresse personnelle Device Owner se fait uniquement dans le dépôt frère **custos** (Custos Supremus).
