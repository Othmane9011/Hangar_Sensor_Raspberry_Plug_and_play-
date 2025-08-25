# Monitoring System

## 📌 Description
Ce projet utilise un **Raspberry Pi** comme centre de monitoring pour un **hangar à poules**.  
Le Raspberry Pi agit comme **point d’accès Wi-Fi** afin de centraliser toutes les données envoyées par les capteurs répartis dans le hangar.  

Les capteurs mesurent en temps réel plusieurs paramètres environnementaux essentiels au bien-être des poules :
- 🌡️ Température  
- 💧 Humidité  
- 🌿 CO₂ et qualité de l’air  
- (et d’autres capteurs à venir)  

Toutes les données sont ensuite **collectées, stockées et visualisées** via **Grafana**, permettant un suivi clair et précis de l’état du hangar.

---

## ⚙️ Fonctionnement
1. Les capteurs se connectent en **Wi-Fi** directement au Raspberry Pi.  
2. Le Raspberry Pi centralise les données.  
3. Les informations sont stockées dans une base de données (InfluxDB, Prometheus, ou autre backend compatible).  
4. **Grafana** est utilisé pour créer des tableaux de bord et visualiser les mesures en temps réel.  

---

## 🛠️ Matériel utilisé
- Raspberry Pi (Point d’accès + serveur)  
- Capteurs Wi-Fi (Température, Humidité, CO₂, etc.)  
- Réseau local sans dépendance Internet  

---

## 📊 Visualisation
Les données sont affichées sur un tableau de bord **Grafana**, permettant :
- Un suivi en temps réel  
- L’analyse historique  
- L’alerte en cas de dépassement de seuils  

---

## 🚀 Objectifs
- Améliorer le **confort et la santé** des poules  
- Avoir une **surveillance continue** du hangar  
- Mettre en place un système **autonome et local**, sans dépendance extérieure  

---

## 📅 Roadmap
- [ ] Ajouter de nouveaux types de capteurs (luminosité, son, mouvement)  
- [ ] Intégrer un système d’alertes (mail / Telegram)  
- [ ] Automatiser certaines actions (ventilation, ouverture de trappes, etc.)  

---

## 📷 Aperçu
*(à compléter avec des captures Grafana ou photos du montage une fois disponible)*  

---

## 🤝 Contributions
Les contributions, idées et améliorations sont les bienvenues !  

---

## 📄 Licence
Ce projet est sous licence libre. Vous pouvez le réutiliser et l’adapter.
