# 🛡️ SIEM avec Wazuh et ELK Stack

## 🔍 Description du Projet

Ce projet consiste à **déployer un système de surveillance de sécurité SIEM** basé sur l’intégration de **Wazuh** avec la **stack ELK** (Elasticsearch, Logstash, Kibana).

Il a été conçu dans le but de détecter, surveiller et analyser les événements de sécurité dans un environnement informatique, à travers une solution open-source puissante et flexible.

---

## 🎯 Objectifs

- Proposer une **solution pratique de détection des menaces**
- Centraliser les logs des machines du réseau
- Visualiser les événements via des dashboards Kibana
- Réagir efficacement en cas d’attaque (force brute, injection SQL, etc.)

---

## 🧱 Technologies Utilisées

- 🐧 **Wazuh** – moteur SIEM pour la collecte, la détection et les alertes  
- 📦 **ELK Stack** :
  - **Elasticsearch** – stockage et recherche
  - **Logstash** – traitement des logs
  - **Kibana** – visualisation des données
- 🐍 **Kali Linux** – simulateur d’attaques
- 💻 **VMware Workstation** – virtualisation de l’environnement

---

## 🧪 Tests réalisés

✔️ Détection attaque brute SSH  
✔️ Surveillance de fichiers critiques (FIM)  
✔️ Détection attaque SQLi  
✔️ Détection Shellshock  
✔️ Processus non autorisés (netcat)

---

## 📊 Dashboards

Des dashboards personnalisés ont été créés pour visualiser :

- Les vulnérabilités détectées
- Les événements critiques
- Les agents les plus bruyants
- Les statistiques sur la conformité

---

## 📎 Rapport complet en PDF

📄 **[Télécharger le rapport final](./SIEM2.pdf)**

---

## 👨‍💻 Réalisé par

**Ahmed Argoubi**  
Étudiant en cybersécurité  
🔗 [LinkedIn](https://www.linkedin.com/in/ahmed-argoubi-773808299/)

---

## 📌 Remarque

Ce projet est une **démonstration pratique** pour les étudiants ou professionnels souhaitant apprendre à mettre en place un SIEM open-source. Il peut être enrichi par :
- L’ajout d’un honeypot
- L’intégration de règles de threat intelligence
- Une extension vers un vrai SOC multi-agent

