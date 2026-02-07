# mon-chat-ephemere
---

# 🔐 Chat Éphémère Crypté

Un chat **sécurisé, simple et éphémère** utilisant **PeerJS** pour la connexion directe entre utilisateurs et **AES (CryptoJS)** pour le chiffrement des messages.
Ce projet permet d’échanger des messages chiffrés **sans serveur central** : vos données ne transitent que de pair à pair.

---

## 🚀 Fonctionnalités

✅ Connexion directe entre deux utilisateurs via **Peer-to-Peer**
✅ Messages **chiffrés avec AES**
✅ Chat en **temps réel**
✅ Interface moderne et épurée
✅ Messages **éphémères** (ils disparaissent à la fermeture de la page)

---

## 📸 Aperçu

```text
┌─────────────────────────────────────────────┐
│        🔐 Chat Éphémère Crypté              │
│---------------------------------------------│
│ Votre ID : 8sd9f-azxkq                      │
│                                             │
│ [Votre pseudo: Alice] [ID de l'autre: Bob]  │
│ [Connecter]                                 │
│                                             │
│ ---------------- Messages ----------------- │
│ Alice: Salut 👋                             │
│ Bob: Hello !                                │
│---------------------------------------------│
│ [Tapez votre message...] [Envoyer]          │
└─────────────────────────────────────────────┘
```

---

## ⚙️ Installation

1. Clone le projet :

   ```bash
   git clone https://github.com/ton-utilisateur/chat-ephemere-crypte.git
   cd chat-ephemere-crypte
   ```

2. Ouvre simplement le fichier **`index.html`** dans ton navigateur.
   👉 Aucune installation supplémentaire n’est nécessaire !

---

## 📖 Utilisation

1. **Ouvre la page** : ton **ID unique** s’affiche.

   * Exemple : `8sd9f-azxkq`.

2. **Partage ton ID** avec ton correspondant.

3. **Entre son ID** dans le champ prévu et choisis ton **pseudo**.

4. Clique sur **"Connecter"**.

5. Échangez vos messages 🚀

   * Chaque message est **chiffré avant l’envoi**.
   * Le destinataire **décrypte automatiquement**.

⚠️ Si tu fermes la page, la connexion est perdue et les messages disparaissent.

---

## 🔒 Sécurité

* Chaque message est chiffré avec **AES** grâce à [CryptoJS](https://cryptojs.gitbook.io/docs/).
* La connexion est directe **P2P** via [PeerJS](https://peerjs.com/).
* Le secret est défini dans le code (`my-secret-key-123`) → il peut être remplacé par une clé unique pour plus de sécurité.

---

## 🎨 Personnalisation

Tu peux modifier :

* 🎨 **Les couleurs** dans le CSS pour adapter le thème.
* 🔑 **La clé de chiffrement** (`secretKey`) pour renforcer la confidentialité.
* 💬 **Le style des messages** (bulle, couleurs, etc.).

---

## 🤝 Contribution

Les contributions sont les bienvenues !

* Ajoute des fonctionnalités (messages temporisés, pièces jointes, etc.)
* Améliore le design
* Propose un meilleur système de gestion des clés 🔑

---

## 📜 Licence

Projet open-source sous licence **MIT**.
Tu es libre de l’utiliser, le modifier et le partager.

---

✨ Bon chat sécurisé à toi !

