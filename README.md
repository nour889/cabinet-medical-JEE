#  Système de Gestion d’un Cabinet Médical – Version Java JEE

##  Description du projet

Ce projet consiste en la conception et le développement d’une application web de gestion pour un cabinet médical, réalisée en **Java JEE**.

L’application permet de gérer l’ensemble du cycle de consultation médicale :  
- gestion des créneaux,  
- prise de rendez-vous,  
- enregistrement des visites,  
- rédaction des bilans médicaux,  
- gestion des utilisateurs selon leurs rôles.

Le système repose sur une architecture professionnelle respectant le modèle MVC et les bonnes pratiques du développement web.


## Technologies utilisées

- Java EE
- Servlets
- JSP
- Maven
- MySQL
- Architecture MVC


## 🏗 Architecture technique

L’application adopte une architecture **MVC** :

- **Servlet** → Contrôleur  
- **JSP** → Vue  
- **DAO (JDBC)** → Accès aux données  
- **Service** → Logique métier  

La sécurité est assurée par :
- Gestion des sessions JEE
- Authentification des utilisateurs
- Filtres de contrôle d’accès selon les rôles

---

## 🗄 Base de données

Le système repose sur une base de données relationnelle **MySQL**.

Principales tables :

- utilisateurs  
- patients  
- créneaux  
- rendez_vous  
- visites  
- bilans  
