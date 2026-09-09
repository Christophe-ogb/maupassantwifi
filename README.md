# 📡 MAUPASSANT WiFi Zone - Landing Page & Portail d'Accès

Interface web moderne, légère et responsive permettant aux utilisateurs de demander un accès Internet sur le réseau **MAUPASSANT WiFi Zone**.

---

## 🚀 Fonctionnalités

- 📱 **Sélection dynamique des forfaits :** Prise en charge des tarifs selon l'équipement (Téléphone seul vs Téléphone + PC).
- 💳 **Paiement Mobile Money local :** 
  - Intégration des syntaxe USSD pour **MTN Mobile Money** et **Moov Money**.
  - Fonctionnalité de copie rapide du code USSD en un clic.
- 🔢 **Saisie de la référence de transaction :** Champ de validation sécurisé (15 chiffres max).
- 📩 **Envoi des demandes via Formspree :** Réception instantanée des informations clients sans nécessiter de serveur backend complexe.
- 💬 **Modal de confirmation dynamique :** Affichage automatique des identifiants Wi-Fi et consignes d'attente dès la validation du formulaire.
- 📞 **Support client intégré :** Liens directs WhatsApp et appel téléphonique pour le service après-vente.

---

## 🛠️ Technologies utilisées

- **HTML5** (Sémantique et accessible)
- **CSS3** (CSS Variables, Flexbox, Design Responsive Mobile-First)
- **JavaScript (Vanilla JS)** (Gestion dynamique des forfaits, manipulation DOM, Fetch API)
- **Formspree API** (Traitement du formulaire)

---

## 📋 Prérequis & Configuration

Pour adapter ce projet à votre propre WiFi Zone :

1. Ouvrez le fichier `index.html`.
2. Modifiez l'action du formulaire Formspree :
   ```html
   <form id="wifiForm" action="[https://formspree.io/f/VOTRE_FORM_ID](https://formspree.io/f/VOTRE_FORM_ID)" method="POST">
