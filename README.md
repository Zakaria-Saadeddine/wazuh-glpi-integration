# Wazuh to GLPI ITSM Integration (Inetum Internship)

Ce projet a été réalisé dans le cadre de mon stage technique en cybersécurité et infrastructure chez **Inetum Casablanca** (Juillet - Septembre 2026).

## 🎯 Objectif du Projet
Automatiser la création de tickets d'incidents dans la plateforme ITSM **GLPI** à partir des alertes de sécurité générées par le SIEM **Wazuh**, afin d'accélérer la réponse aux incidents (SecOps).

## ⚙️ Architecture & Fonctionnalités
- **Wazuh SIEM :** Détection des alertes de sécurité (ex: Brute-Force SSH) et cartographie des menaces via le référentiel **MITRE ATT&CK**.
- **Middleware Python :** Script de connexion via l'API REST pour parser les alertes Wazuh et les injecter sous forme de tickets dans GLPI.
- **Environnement :** Administration d'environnements virtualisés (VMware, Ubuntu, MariaDB) et application des procédures de diagnostic et de résolution des incidents techniques.

## 🛠️ Stack Technique
* **Langage & API :** Python, API REST
* **Sécurité & SOC :** Wazuh SIEM, MITRE ATT&CK
* **ITSM :** GLPI
* **Infrastructure :** Linux (Ubuntu), MariaDB, VMware
