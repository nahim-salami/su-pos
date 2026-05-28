<div align="center">

# Su POS

**Logiciel de caisse béninois — homologué DGI, fonctionne hors ligne.**

[![Version](https://img.shields.io/github/v/release/nahim-salami/su-pos?label=version)](https://github.com/nahim-salami/su-pos/releases/latest)
[![License](https://img.shields.io/badge/license-Proprietary-blue.svg)](LICENSE)
[![Site](https://img.shields.io/badge/site-su.ahime.net-1B2A4E.svg)](https://su.ahime.net)
[![Édité par](https://img.shields.io/badge/édité_par-Ahime-C9A24A.svg)](https://ahime.net)

[**🌐 Site officiel**](https://su.ahime.net) · [**📥 Télécharger**](https://github.com/nahim-salami/su-pos/releases/latest) · [**🚀 Démarrer en ligne**](https://app.su.ahime.net) · [**✉️ Support**](mailto:support@su.ahime.net)

</div>

---

## 📦 Téléchargement

Tous les binaires officiels sont publiés ici comme **releases GitHub**. Cliquez sur la version qui correspond à votre appareil :

| Plateforme | Téléchargement direct | Configuration requise |
|---|---|---|
| 🪟 **Windows 10 / 11** | [Télécharger `su-pos-setup-windows.exe`](https://github.com/nahim-salami/su-pos/releases/latest/download/su-pos-setup-windows.exe) | 64 bits · 4 Go RAM min. · ~50 Mo disque |
| 🤖 **Android 7+** | [Télécharger `su-pos-android.apk`](https://github.com/nahim-salami/su-pos/releases/latest/download/su-pos-android.apk) | APK universel · 200 Mo · Autoriser sources inconnues |
| 🌐 **Web (navigateur)** | [Ouvrir `app.su.ahime.net`](https://app.su.ahime.net) | Chrome, Edge, Safari récents · sans installation |
| 🍎 macOS · 🐧 Linux · 📱 iOS | *Bientôt disponibles* | — |

> 💡 La version **Web** est idéale pour démarrer instantanément (consulter ventes, catalogue, clients).
> Pour **encaisser** en boutique avec ticket thermique et mode hors-ligne, utilisez l'app **Windows** ou **Android**.

---

## 🌐 Liens utiles

| Service | URL |
|---|---|
| **Site marketing** | https://su.ahime.net |
| **App Web (login + dashboard)** | https://app.su.ahime.net |
| **Page tarifs** | https://su.ahime.net/tarifs |
| **Page fonctionnalités** | https://su.ahime.net/fonctionnalites |
| **Page métiers supportés** | https://su.ahime.net/verticaux |
| **Inscription (14 jours gratuits)** | https://app.su.ahime.net/?action=signup |
| **Connexion** | https://app.su.ahime.net/?action=login |
| **Documentation API (à venir)** | https://docs.su.ahime.net |
| **Support email** | support@su.ahime.net |
| **WhatsApp** | [Démarrer une discussion](https://wa.me/22900000000) |

---

## 🎯 À qui s'adresse Su POS ?

Su POS est conçu pour les **commerçants du Bénin et de l'UEMOA** :

- 🛍️ **Boutiques** (alimentation, prêt-à-porter, électronique, librairie…)
- 🍽️ **Restaurants & bars** (table service, KDS cuisine, livraison)
- 💊 **Pharmacies** (ordonnances, stupéfiants, lots+DLC, assurances)
- 💇 **Salons de beauté / coiffure** (rendez-vous, prestations, fidélité)
- 🚗 **Garages auto** (ordres de réparation, devis, pièces+main d'œuvre)
- 🏨 **Hôtels** (réservations, room service, folio, housekeeping)
- 🧑‍💼 **Professions libérales** (cabinets juridiques, comptables, audit)
- 🚚 **Services & livraison** (zones, drivers, marketplaces : Glovo, Yango, Jumia)

Au total **25 profils métiers** pré-configurés avec écrans dédiés. La liste complète est sur [su.ahime.net/verticaux](https://su.ahime.net/verticaux).

---

## ✨ Ce qui rend Su POS différent

### 🇧🇯 Conformité fiscale DGI Bénin native
- Facturation normalisée e-MECeF (code sécurité 24 chars + QR code)
- Soumission temps réel à l'API DGI
- **Mode dégradé** intelligent : si pas de connexion DGI, le ticket reste imprimable avec mention « FACTURE NON-NORMALISÉE », et la soumission est faite automatiquement dès reconnexion (sous 72h max)
- Audit log immuable et traçable

### 📡 Marche vraiment hors ligne
- Toute la caisse fonctionne sans Internet (ventes, encaissement, impression, calcul fiscal AIB)
- Base SQLCipher chiffrée AES-256 stockée localement
- Synchronisation automatique dès que la 4G revient
- Idéal pour les coupures fréquentes au Bénin

### 🏪 Multi-métiers et multi-boutiques
- Une seule app pour 25 métiers (le profil est choisi à l'inscription)
- Boutiques multiples avec switch instantané
- Reporting consolidé inter-boutiques
- Transferts de stock entre boutiques en 2 clics

### 👥 Gestion d'équipe avancée
- 15 rôles RBAC standards (caissier, vendeur, gérant, comptable…)
- Connexion par PIN 4 chiffres pour les caissiers
- Permissions fines (peut-il faire une remise > 20% ? rembourser ?)
- Audit log : qui a fait quoi, quand

### 💰 Modules métier complets
- Caisse + paiements (cash, mobile money, carte, USSD, virement, crédit, fidélité)
- Catalogue produits + services
- Clients B2C / B2B (avec IFU, conditions de paiement, plafonds crédit)
- Stocks multi-entrepôts (FIFO, alertes seuils, inventaires)
- Comptabilité OHADA complète
- Trésorerie (banques, rapprochement)
- Achats (fournisseurs, BC, BR, factures)
- RH (employés, contrats, fiches de paie CNSS+IPTS, présences)
- Marketing (promotions, programme fidélité)
- Rapports avancés + prévisions de ventes

---

## 🚀 Comment démarrer ?

### 1. Créez votre compte (gratuit, sans carte bancaire)

Allez sur [**app.su.ahime.net**](https://app.su.ahime.net/?action=signup) et remplissez le formulaire en 2 minutes. Vous obtenez :

- ✅ **14 jours gratuits** avec toutes les fonctionnalités débloquées
- ✅ Code boutique + PIN caissier livrés par email
- ✅ Plan comptable OHADA + 6 groupes de taxe DGI déjà configurés
- ✅ 1 boutique + 1 dépôt + 1 caissier déjà créés pour vous

### 2. Téléchargez l'app

| Cas d'usage | Téléchargement recommandé |
|---|---|
| Vous voulez **encaisser en boutique** | [📥 Windows .exe](https://github.com/nahim-salami/su-pos/releases/latest/download/su-pos-setup-windows.exe) |
| Vous avez une **tablette/téléphone Android** | [📥 Android .apk](https://github.com/nahim-salami/su-pos/releases/latest/download/su-pos-android.apk) |
| Vous voulez juste **consulter / superviser** | [🌐 Ouvrir app.su.ahime.net](https://app.su.ahime.net) — sans installation |

### 3. Connectez-vous et démarrez

Au premier lancement, choisissez « Compte propriétaire » et entrez l'email/mot de passe créés à l'étape 1. Pour les caissiers, le PIN 4 chiffres suffit.

---

## 💰 Tarifs

| Plan | Mensuel | Inclus |
|---|---|---|
| **Démarrage** | 9 000 XOF | 1 boutique, 300 produits, 2 utilisateurs |
| **Pro** | 19 000 XOF | Boutiques illimitées, 5 000 produits, 10 utilisateurs, fidélité, KDS, RDV |
| **Multi-boutiques** | 39 000 XOF/boutique | Reporting consolidé, transferts, API publique, support prioritaire |
| **Enterprise** | Sur devis | SLA 99%, account manager dédié, intégrations sur-mesure |

➡️ Détails complets sur [**su.ahime.net/tarifs**](https://su.ahime.net/tarifs)

---

## 🔧 Pour les administrateurs IT

### Installation Windows (déploiement multi-postes)

L'installeur `.exe` supporte l'installation silencieuse :

```cmd
su-pos-setup-windows.exe /SILENT /SUPPRESSMSGBOXES /NORESTART
```

Options utiles :

| Flag | Effet |
|---|---|
| `/SILENT` | Pas de wizard interactif, juste une barre de progression |
| `/VERYSILENT` | Aucun affichage, idéal pour SCCM / Intune / GPO |
| `/NORESTART` | Pas de redémarrage automatique |
| `/DIR="C:\Apps\Su POS"` | Override du dossier d'install |
| `/TASKS="desktopicon,startmenuicon"` | Choix des raccourcis |

L'installeur fonctionne **sans droits administrateur** (installation par utilisateur). Pour une installation système, lancer en tant qu'admin.

### Configuration centralisée

Les paramètres serveur (URL backend, tenant ID) sont récupérés au login. Aucune configuration locale n'est nécessaire pour les caissiers.

Pour pointer vers un serveur Su Local sur LAN (déploiement sur réseau interne), utiliser le menu **Paramètres → Connexions → Su Local**.

### Désinstallation propre

Panneau de configuration → Programmes → Su POS → Désinstaller.

L'assistant demande s'il faut aussi effacer les **données locales** (base SQLCipher, identifiants, configuration). Choisir « Non » lors d'une réinstallation/mise à jour pour préserver le setup.

---

## 📋 Compatibilité

| Plateforme | Versions supportées | Statut |
|---|---|---|
| Windows | 10, 11 (x64) | ✅ Production |
| Android | 7.0 (API 24) et plus | ✅ Production |
| Web | Chrome 100+, Edge 100+, Safari 16+, Firefox 100+ | ✅ Production (lecture/back-office) |
| macOS | 12 Monterey+ | 🚧 Q3 2026 |
| Linux | Ubuntu 22.04+, Debian 12+ | 🚧 Q3 2026 |
| iOS / iPadOS | 16+ | 🚧 Fin 2026 (App Store en validation) |

---

## 📜 Notes de version

Voir [**la liste des releases**](https://github.com/nahim-salami/su-pos/releases) pour le détail des changements de chaque version, ou consultez le [CHANGELOG.md](CHANGELOG.md).

La version stable la plus récente est toujours disponible via les liens « latest » :
- https://github.com/nahim-salami/su-pos/releases/latest/download/su-pos-setup-windows.exe
- https://github.com/nahim-salami/su-pos/releases/latest/download/su-pos-android.apk

---

## 📜 Licence

Su POS est un logiciel **propriétaire** édité par **Ahime SARL** (Cotonou, Bénin).

L'usage du logiciel est régi par l'abonnement Su POS souscrit auprès d'Ahime. Voir [LICENSE](LICENSE) pour les conditions complètes.

Le **code source** n'est pas publié dans ce dépôt — ce dépôt sert uniquement à la distribution des **binaires officiels** et à la documentation utilisateur.

---

## 🏢 À propos d'Ahime

[**Ahime**](https://ahime.net) est un éditeur de logiciels d'entreprise basé à **Cotonou, Bénin**. Notre mission : équiper les commerçants africains avec des outils numériques à la hauteur des meilleurs standards mondiaux, adaptés aux réalités locales (réseau intermittent, fiscalité DGI, mobile money, multi-devises).

Su POS est notre produit phare pour le **point de vente** et la **gestion d'activité**.

**Contact** :
- 📧 [contact@ahime.net](mailto:contact@ahime.net)
- 🌐 [ahime.net](https://ahime.net)
- 💼 [LinkedIn](https://www.linkedin.com/company/ahime)

---

## 🆘 Besoin d'aide ?

| Type d'aide | Comment nous contacter |
|---|---|
| **Question avant achat** | [WhatsApp](https://wa.me/22900000000) ou [contact@su.ahime.net](mailto:contact@su.ahime.net) |
| **Support technique** | [support@su.ahime.net](mailto:support@su.ahime.net) (réponse sous 2 h ouvrées) |
| **Bug à reporter** | [Ouvrir une issue](https://github.com/nahim-salami/su-pos/issues/new) sur ce dépôt |
| **Demande de fonctionnalité** | [Ouvrir une issue](https://github.com/nahim-salami/su-pos/issues/new) avec le label `enhancement` |
| **Partenariat / Enterprise** | [partnerships@ahime.net](mailto:partnerships@ahime.net) |

---

<div align="center">

**Su POS** · Édité par [**Ahime**](https://ahime.net) · Cotonou, Bénin · 2026

Made with ❤️ in Benin for African businesses.

</div>
