
################################################################

🚧 Évolution du projet
 Version actuelle

Cette version représente la première itération du projet — une base fonctionnelle développée avec Spring Boot et PostgreSQL, intégrant les fonctionnalités essentielles de gestion pédagogique (formateurs, filières, emplois du temps, états d’avancement, etc.).
Elle constitue une version stable et démonstrative, destinée à illustrer l’architecture et les concepts fondamentaux du système.

Note : Cette version est une première itération du projet et ne suit pas encore toutes les bonnes pratiques de production, comme l’injection par champ /  Injection par constructeur...

⚙️ Nouvelle version en cours de développement

Une version avancée du projet est actuellement en refonte.
Elle vise à appliquer les meilleures pratiques du développement professionnel, renforcer la sécurité et améliorer la scalabilité, tout en intégrant de nouveaux outils modernes.

Élément	Ce que ça démontre

DTO & ResponseDTO	Bonne séparation des couches et structure claire

MapStruct	Automatisation du mapping entre entités et DTO

Jakarta Validation (@Valid, @NotBlank, @Pattern)	Validation robuste des données

GlobalExceptionHandler	Gestion centralisée et cohérente des erreurs

Spring Security + JWT + CSRF	Sécurité moderne et authentification maîtrisée

Liquibase	Migration de base de données versionnée et traçable

JUnit & Mockito	Tests unitaires et d’intégration

Logging (SLF4J + Logback)	Suivi et diagnostic des applications

Swagger / Springdoc OpenAPI	Documentation claire et interactive de l’API

Structure modulaire (multi-modules)	Architecture propre, scalable et maintenable

Algorithme d’autogénération d’emploi du temps	Logique métier avancée et optimisation algorithmique

frontend React 	Vision full-stack moderne

Docker / Docker Compose	Déploiement simplifié et environnement reproductible


💡 Cette version est conçue pour offrir une architecture plus propre, testée et extensible, conforme aux standards professionnels et prête pour la conteneurisation.



##########################################################################
################################################################

<br><br><br>





**************Description*****************
<br><br>
Ce projet est une application web de gestion pédagogique développée avec Spring Boot et PostgreSQL.
Elle vise à digitaliser et automatiser le suivi de l’avancement des formateurs, ainsi que la gestion des emplois du temps, filières, matières, employés et utilisateurs au sein d’un établissement de formation.
<br>
L’application propose une interface moderne, intuitive et sécurisée, adaptée à trois profils d’utilisateurs :
<br><br><br>
👨‍💼 Direction : supervision globale, gestion des filières, modules, emplois du temps et utilisateurs.

🧾 Secrétariat : gestion opérationnelle et suivi des états d’avancement.

👨‍🏫 Formateurs : consultation de l’emploi du temps et saisie des états d’avancement.

⚙️ Cette premiere version du projet est semi-complet, modulaire et évolutif, conçu pour s’intégrer facilement dans tout environnement de formation ou d’enseignement.




**************Technologies principales*****************

Backend : Spring Boot (Java), Spring Security, Spring Data JPA

Base de données : PostgreSQL

Frontend : Thymeleaf, HTML, CSS, JavaScript

Architecture : MVC (Model–View–Controller)




***************Caractéristiques*************************

Authentification et autorisation basées sur les rôles (Direction, Secrétariat, Formateur)

Gestion complète des entités principales (CRUD)

Génération de fichiers Excel pour export des données

Architecture claire et découplée (Model, Repository, Service, Controller, Security)

Interface fluide sans rechargement complet grâce aux fragments Thymeleaf

Automatisation de certaines opérations via triggers et contraintes en base de données







*****************Objectif*******************

Fournir une solution moderne, fiable et extensible de gestion pédagogique, répondant aux besoins concrets des établissements de formation — tout en restant suffisamment flexible pour être personnalisée selon les exigences spécifiques.








⚠️ Note
Pour Plus de details sur l'aplication >>> 


Le code source complet et la documentation technique détaillée ne sont pas publiés sur ce dépôt public pour des raisons de confidentialité.
Ce projet est prêt pour une mise en production ou une commercialisation.
Pour toute demande de démonstration ou de partenariat, veuillez me contacter directement.




<br><br><br><br>





### 📸 Aperçu de l’application

<br><br>
Page d'authentification:


<img width="1152" height="773" alt="image" src="https://github.com/user-attachments/assets/0feb9640-b3da-41eb-b5a2-ec28d6878609" />



<br><br><br>
Page d'accueil:


<img width="1850" height="982" alt="image" src="https://github.com/user-attachments/assets/f4e42b49-d56d-48c1-bd1e-e98f3f91bb08" />




<img width="1861" height="981" alt="image" src="https://github.com/user-attachments/assets/59d859f6-5293-41d6-8fec-ef5b851d95f5" />



<br><br><br>

Page Etat d'avancement:





<img width="1852" height="982" alt="image" src="https://github.com/user-attachments/assets/60dbf189-044d-497a-bd7d-e339964f7aa8" />





<br><br><br>

Page d'emplois du temps:




<img width="1856" height="967" alt="image" src="https://github.com/user-attachments/assets/b799770f-d3cd-4722-a0a4-32f18d55394e" />



<br><br><br>
Module de Ajout/Modification:


<img width="1860" height="938" alt="image" src="https://github.com/user-attachments/assets/5addb612-811c-4959-91b0-6ce2a4d185c1" />









