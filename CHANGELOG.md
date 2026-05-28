# Notes de version — Su POS

Toutes les versions publiées de Su POS, par ordre antichronologique.

Le format suit [Keep a Changelog](https://keepachangelog.com/fr/1.1.0/), et le numéro de version respecte le [versioning sémantique](https://semver.org/lang/fr/).

---

## [0.1.0] — 2026-05-28

**Première release publique de Su POS** 🎉

### ✨ Nouveautés

- **Encaissement multi-paiement** : espèces, mobile money, carte bancaire, USSD, virement, crédit, fidélité
- **Conformité DGI Bénin (e-MECeF)** :
  - Code de sécurité 24 caractères + QR code sur chaque ticket
  - Soumission temps réel à l'API DGI
  - Mode dégradé intelligent (ticket non normalisé si pas de connexion DGI, re-soumis automatiquement sous 72 h)
  - Audit log immuable avec correlation_id
- **Hors ligne complet** : caisse, encaissement, impression, calcul AIB sans Internet
- **Multi-boutiques** : switch instantané, reporting consolidé, transferts inter-boutiques
- **25 profils métier** pré-configurés (boutique, restaurant, pharmacie, salon, garage, hôtel, etc.)
- **Tableau de bord** : KPI jour/mois/année, top produits, mix paiements, ventes récentes
- **Catalogue** : produits + services avec import CSV/Excel
- **Clients** B2C / B2B avec statut fiscal (IFU), conditions paiement, plafond crédit
- **Stocks** multi-entrepôts, FIFO, alertes seuils, inventaires, transferts
- **Comptabilité OHADA** : plan comptable, journaux, écritures
- **Trésorerie** : banques, mouvements, rapprochement
- **Achats** : fournisseurs, BC, BR, factures
- **RH** : employés, contrats, fiches de paie CNSS+IPTS, présences
- **Marketing** : promotions, programme fidélité
- **Rapports** : ventes, AIB, TVA, P&L, balance, prévisions
- **Multi-utilisateurs** : 15 rôles RBAC, permissions fines, login PIN
- **Tunnel d'inscription** : 14 jours gratuits sans carte bancaire
- **App Web** : login OTP + dashboard read-only sur [app.su.ahime.net](https://app.su.ahime.net)

### 🐛 Fix critiques de cette release

- Crash "Détail vente" sur 32+ écrans (parsing JSON tolérant pour types Laravel)
- Boucle infinie sur erreur 401 — bouton « Se reconnecter » qui purge la session
- Validation /users/invite et /users/roles (alignement champs Flutter ↔ backend)
- Sync engine /orders 422 (items.id, applied_tax_rate_bp, payments[])
- Path mismatch /transfers (Flutter aligné sur Laravel)
- Customer payload : phone, is_business, billing_address alignés sur backend

### 📥 Téléchargement

| Plateforme | Lien direct |
|---|---|
| Windows 10/11 | [su-pos-setup-windows.exe](https://github.com/nahim-salami/su-pos/releases/download/v0.1.0/su-pos-setup-windows.exe) |
| Android 7+ | [su-pos-android.apk](https://github.com/nahim-salami/su-pos/releases/download/v0.1.0/su-pos-android.apk) |
| Web | [app.su.ahime.net](https://app.su.ahime.net) |

### 🚧 Modules en bêta

- App Web complète (dashboard + lecture catalogue/ventes/clients) — encaissement web prévu Q3 2026
- macOS + Linux : prévus Q3 2026
- iOS : prévu fin 2026 (App Store en validation)

---

[0.1.0]: https://github.com/nahim-salami/su-pos/releases/tag/v0.1.0
