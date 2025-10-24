# Documentation du serveur VPS Ubuntu 22.04

Ce document décrit la mise en œuvre de mon serveur VPS, incluant la sécurisation, l’isolation des applications et la configuration des services.

---

## 1. Informations générales

- **Système d’exploitation** : Ubuntu 22.04 LTS
- **Utilisateur principal** : admin (avec droits sudo)
- **Objectif** : serveur sécurisé pour exécuter des conteneurs Docker et gérer des services comme Omada et WireGuard.

---

## 2. Vérification du système

Vérification de la version d’Ubuntu et du noyau Linux pour garantir la compatibilité et la sécurité.

```bash
lsb_release -a
uname -r

<p align=("center")>
<img src="images/Screenshot-1.jpg" alt="Screenshot pour la vérification du système" width="300" />
</p>
