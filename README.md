# SK Beauty Pro - Système de Gestion Professionnelle

Application complète de gestion pour boutique de cosmétiques.

## 🚀 Fonctionnalités

- ✅ **Authentification** : 2 administrateurs + 8 caisses
- ✅ **Multi-devises** : CDF (Franc Congolais) et USD (Dollar Américain)
- ✅ **Multi-langues** : Français et Anglais
- ✅ **Logo personnalisable** : Upload par l'administrateur
- ✅ **Catégories de produits** : Laits & Crèmes, Parfums, Rouges à Lèvres, Maquillage
- ✅ **Gestion des stocks** : Seuils d'alerte personnalisables
- ✅ **Caisse** : Scanner code-barres, panier dynamique
- ✅ **Facturation professionnelle** : PDF avec logo, remise, numéro de téléphone
- ✅ **Impression réelle** : USB, Bluetooth, WiFi (avec fallback navigateur)
- ✅ **Gestion des clients** : Points fidélité, anniversaires, historique
- ✅ **Sauvegarde automatique** : Toutes les heures, 24 sauvegardes conservées
- ✅ **Mode hors-ligne** : File d'attente, synchronisation automatique
- ✅ **Rapports** : Export Excel/CSV
- ✅ **Tableau de bord** : Graphiques, top produits, comparaison avec la veille
- ✅ **Design responsive** : S'adapte à tous les écrans (mobile, tablette, desktop)
- ✅ **Animations** : Objets flottants, transitions fluides

## 🔧 Technologies utilisées

- HTML5 / CSS3 / JavaScript
- Chart.js pour les graphiques
- jsPDF pour les factures PDF
- Font Awesome 6 pour les icônes
- Google Fonts (Inter, Playfair Display)
- WebUSB / Web Bluetooth pour l'impression réelle
- LocalStorage pour la persistance des données

## 📱 Compatibilité

- ✅ Chrome (recommandé pour l'impression USB)
- ✅ Edge
- ✅ Firefox (sans impression USB)
- ✅ Safari (sans impression USB)
- ✅ Android (navigateur Chrome)
- ✅ iOS (Safari)

## 🔑 Identifiants de connexion

| Rôle | Email | Mot de passe |
|------|-------|--------------|
| Admin Principal | admin1@skbeauty.cd | admin123 |
| Admin Secondaire | admin2@skbeauty.cd | admin123 |
| Caisse 1 | caisse1@skbeauty.cd | caisse123 |
| Caisse 2 | caisse2@skbeauty.cd | caisse123 |
| ... | ... | ... |
| Caisse 8 | caisse8@skbeauty.cd | caisse123 |

## 🖨️ Impression réelle

L'application supporte l'impression réelle via :
- **USB** : WebUSB (Chrome/Edge)
- **Bluetooth** : Web Bluetooth
- **WiFi** : Impression navigateur (fallback)

Formats supportés : 58mm et 80mm

## 💾 Sauvegarde automatique

- Sauvegarde toutes les heures (intervalle configurable)
- 24 dernières sauvegardes conservées
- Restauration possible depuis l'interface
- Export manuel possible

## 📊 Rapports

Export Excel/CSV disponible pour :
- Ventes
- Produits
- Clients
- Factures

## 📞 Contact

- **Téléphone** : +243 992 381 922 (modifiable dans les paramètres)
- **Développé par** : Prosper MING'A Muya et Annah KIS

## 📦 Installation

1. Clonez le dépôt :
```bash
git clone https://github.com/Pro057/SK-Beauty.git
