# Projet VoIP Asterisk 23 📞

Ce dépôt contient les configurations et scripts pour le déploiement d'un serveur VoIP complet sous Debian 12 avec Asterisk 23 (compilé depuis les sources).

## 🚀 Fonctionnalités
* **Appels Audio** : Configuration PJSIP (Alice & Bob).
* **Serveur Vocal Interactif (SVI)** : Menu dynamique ("Tapez 1 pour la Compta...").
* **Synthèse Vocale (TTS)** : Intégration hybride Google TTS / PicoTTS.
* **Messagerie Vocale** : Boîte vocale avec protection PIN.
* **Automatisation** : Script de prospection téléphonique automatique (Call Files).
* **Gestion Horaire** : Mode "Ne pas déranger" (DnD) automatique 18h-9h.
* **Supervision** : Monitoring via CLI et sngrep.

## 📂 Structure
* `/conf` : Fichiers de configuration Asterisk (extensions.conf, pjsip.conf...).
* `/scripts/agi` : Scripts de liaison Asterisk <-> TTS.
* `/scripts/admin` : Scripts d'installation automatique et d'ajout d'utilisateurs.

## 🛠️ Installation
Lancer le script `install_asterisk.sh` sur une Debian vierge.
