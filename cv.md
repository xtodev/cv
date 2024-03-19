# Xavier Touron
## Ingénieur DevOps & Développement JAVA {#subheading}
<span id="langselect"><a href="https://xtodev.fr">🇫🇷</a>&nbsp;&nbsp;<a href="https://xtodev.fr/en.html">🇬🇧</a></span>
> ![Pic](./assets/photo.jpg) {#photo}
[](https://github.com/xtodev/cv/releases/latest/download/CV_Touron_Xavier.pdf)

------

<span id="aboutme">
Ingénieur diplômé avec plus de 10 ans d'expérience sur des compétences polyvalentes :<br><br>
  • <b>DevOps</b> : Conception de pipelines CI/CD avec Jenkins, Concourse ou Gitlab CI. Déploiements infra-as-code sur Kubernetes, Automatisation de tâches via Ansible.<br>
  • <b>Développement</b> : Développement d'applications backend en Java, avec une affinité pour les APIs et les micro-services.<br>
  • <b>Infra/Ops</b> : Déploiement et administration de stacks Elasticsearch, Kafka, ou encore Fluentbit, sur Kubernetes (via Helm).<br><br>
Curieux de nature, j'ai une envie insatiable d'apprendre de nouvelles technologies.
</span>

<span id="identity">
+33 7 66 65 32 68<br>
contact@xtodev.fr<br>
Vit à Montpellier, France<br>
<br>
Concubinage - 2 enfants<br>
34 ans<br>
Nationalité française
</span>

<span id="lang">
<u>Langues :</u><br>
Français - Langue maternelle<br>
Anglais - Avancé (<a target="_blank" href="https://cert.efset.org/MzoJqB">C1</a>)<br>
Allemand - Débutant (A1/A2)
</span>

## EXPERIENCE PROFESSIONNELLE {.h2long}

### Depuis 02/2022 {.date}
INGENIEUR DEVOPS
: 
*France-Travail (Pôle-Emploi) - Montpellier, France*
  Mission au sein de l'équipe Ops chargée de la centralisation des logs et des collectes bigdata<br>
  • Refonte (avec Helm et en utilisant l'Infra-as-Code) des déploiements automatisés pour chacune des briques de la chaîne de centralisation des logs<br>
	• Administration des clusters Kafka et Elasticsearch<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Affinage des paramètres (dimensionnement, durées de rétention, évolutions)<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Supervision, résolution des incidents, analyse des anomalies (ex: format incorrect) sous Kibana<br>
  • Administration des agents de collecte Fluentbit (Kubernetes) et Nifi (3000+ VMs applicatives)<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Développement de rôles Ansible / AWX pour automatiser la gestion des agents de collecte Nifi<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Gestion gitOps des agents de collecte Fluent (déploiement vers ~30 clusters Kubernetes)<br>
  • Mise en place de supervision et alerting pour garantir la disponibilité du service<br>
  • Veille sur les vulnérabilités des images docker utilisées<br>
  • Bigdata : Mise en place de collectes depuis des fichiers CSV ou des APIs jusqu'au lac de données<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Déploiement IaC et administration de la chaîne de centralisation des logs : <br>
  &nbsp;&nbsp;&nbsp;&nbsp;Fluentbit & Apache Nifi => Apache Kafka => Logstash (Grok/RegEx) => Elasticsearch/Kibana<br>
  Conteneurisation : Docker - Kubernetes - Helm<br>
  Monitoring : Prometheus (AlertManager) - Grafana<br>
  BigData : Apache Nifi, Apache Hive, HDFS, HiveQL<br>
  DevOps : Concourse, Rancher Fleet (gitOps), Ansible, Artifactory, Trivy/Snyk<br>
  Environnement Linux (Aix, SLES, Debian)<br>
  Méthodologie : Mode produit + Agile (Scrum) - Equipe de 4 à 5 personnes - Exigences Non Fonctionnelles<br>

---

### 08/2020 - 01/2022 {.date}
INGENIEUR DEVELOPPEMENT JAVA
: 
*SADA Assurances - Nîmes, France*
  • Développement d'une API REST micro-service (Java17, Docker) permettant la génération des éditiques de la SADA (attestations, contrats, devis, etc..) via des templates au format Word/Jrxml et les librairies Aspose/Jasper pour la génération des PDF. Gestion de l'authentification et des rôles via Auth0.<br>
  • Développement d'une API REST pour le RGPD (projet Kotlin, clean architecture) permettant d'exporter toutes les données (ainsi que leur durée de conservation) d'un individu.<br>
  • Correction de nombreuses failles de sécurité (audit externe) sur des anciens projets Java8 : failles XSS, gestion des droits, stockage des mots de passes, sessions...<br>
  • MCO : Montée de version du framework Springboot et MongoDB sur plusieurs projets, ajout de traçabilité sur les différentes APIs pour le RGPD. Maintenance sur les CI (Gitlab) et CD (Ansible).<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Développement : Java/Kotlin, Springboot, Jasper/Aspose, Clean Architecture, MongoDB, RabbitMQ, OpenAPI, IntellIJ, DBeaver(requêtes SQL), Postman, Gradle/Maven, Git, Linux Gentoo<br>
  DevOps : Docker, Gitlab CI, Ansible, Nexus (Registry)<br>
  Méthodologie : Agile (Scrum, Sprints de 3 semaines) - Equipe de 4 à 6 personnes<br>

<br><hr class="hiddenhrinpdf"><br><br>

### 02/2020 - 07/2020 {.date}
INGENIEUR DEVOPS
:  
*CompuGroup Medical - Montpellier, France*
  • Mise en place et configuration d'une CI/CD avec Jenkins et Sonarqube, dédiée à une centaine de projets : <br>
  • Réalisation des modèles de pipelines pour les projets :<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- C# : Build du projet, exécution des tests unitaires NUnit3 et TestsCoverages avec OpenCover, analyse de la qualimétrie avec SonarQube, livraison en continu  <br>
  &nbsp;&nbsp;&nbsp;&nbsp;- NuGet (package .NET) : Build de la solution Visual Studio, exécution des tests unitaires NUnit3 et TestsCoverages avec OpenCover, analyse de la qualimétrie, déploiement vers Artifactory<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Packaging Innosetup (génération d'archives autoextractibles) : Création et livraison d'un setup.exe depuis des binaires déjà existants.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Docker (génération des images via Dockerfile et stockage dans la registry Artifactory<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Scripting : Groovy, Bash Shell, Powershell, Cake (C#)<br>
  DevOps : Jenkins, SonarQube, Gitlab, Docker, Artifactory, Teamcity<br>
  Outils : Visual Studio, NUnit, OpenCover, NuGet, Git, Gitversion, FinalBuilder, Innosetup, XMind (mindmaps des pipelines)<br>
  Equipe de 2/3 personnes

---

### 02/2019 - 08/2019 {.date}
INGENIEUR DEVELOPPEMENT PHP
: 
*Enercal (principal fournisseur d'énergie en NC) - Nouméa, Nouvelle-Calédonie*
  Contexte : Développement du backend de l'application mobile d'Enercal, gestionnaire du système électrique néocalédonien. Les 3 derniers mois en télétravail depuis la Nouvelle-Zélande, en temps partiel<br>
  • Développement de l'API REST en PHP, basée sur un CMS Drupal 7<br>
  • Réalisation du contrat d'interface de l'API (documentation réutilisée par le client en interne) <br>
  • Tests de charge / tests unitaires avec JMeter.<br>
  <br><u>Environnement technique et fonctionnel</u><br>
  Développement : PHP/MySQL, Postman, JMeter, Docker, Gradle, Git.<br>
  Méthodologie : Agile (Scrum, Sprints de 2 semaines) - Equipe de 2 à 4 personnes<br>

---

### 01/2017 - 02/2019 {.date}
INGENIEUR DEVELOPPEMENT JAVA
: 
  *Société Le Nickel (principal industriel en NC) - Nouméa, Nouvelle-Calédonie*
  Développement en équipe (plateau) sur plusieurs applications Java de la SLN, basées sur le même socle : Architecture micro-services, intégration continue et déploiement automatisé d'images docker via Gitlab CI / Jenkins vers des infras Kubernetes. Principalement :<br>
  • Projet permettant le suivi de la flotte et des horamètres des véhicules de la SLN en temps réel via l'interconnexion des APIs REST d'Hexagon (logiciel australien de suivi de mines) et de la société néocalédonienne fournissant les coordonnées GPS des véhicules<br>
  • Projet d'interconnexion de Maximo (logiciel de gestion d'actifs par IBM) avec Reflex (un logiciel de gestion logistique par Hardis). <br>
  &nbsp;&nbsp;&nbsp;&nbsp;Pour résumer : Maximo (Oracle2Kafka) => Kafka (tampon/scaling) => Reflex (appels SOAP)<br>
  • Application de suivi exact et détaillé du stock d'explosifs de la SLN via une interface dédiée et épurée basée sur les données de Maximo<br>
  • Application en ligne permettant la déclaration des conflits d'intérêts potentiels au sein de la SLN<br>
  • Projet permettant de simplifier la saisie des bons de travaux dans Maximo en modifiant directement sa base de données.<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Développement : Java8, Kafka Streams, Elasticsearch, Guice/Springboot, Gradle, Git. <br>
  DevOps : Gitlab CI, Jenkins, Sonarqube (taux de couverture des tests > 70%), Docker, Kubernetes<br>
  Méthodologie : Agile (Scrum, Sprints de 2 semaines) - Equipe de 2 à 5 personnes

---

### 07/2015 - 12/2016 {.date}
INGENIEUR DEVELOPPEMENT C#
: 
  *Ministère de la défense (Service ministériel des SI de fonctionnement) - Tours, France*
  Contexte : Le SMSIF-RH est l'organisme chargé de la tierce-maintenance applicative de systèmes d'informations des ressources humaines du Ministère de la Défense français. Ma mission portait sur le projet Louvois, permettant la gestion de la solde des militaires, du calcul des indemnités au virement.<br>
  • Développement (ou évolution) des indemnités dans le calculateur (application console C#)<br>
  • Maintenance, évolutions et amélioration de la qualité du code (SonarQube)<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Développement : C#, Visual Studio 2012, Oracle 11G, Microsoft TFS (Versionning), SonarQube<br>
  Méthodologie : Cycle en V sur délai court (3/4 semaines) - Equipe de 10 à 15 personnes

<hr class="hiddenhrinpdf">

### 02/2014 - 07/2015 {.date}
INGENIEUR INTEGRATION TECHNIQUE
: 
  *Ministère de la défense (Service ministériel des SI de fonctionnement) - Tours, France*
  Intégration technique des différents modules de l'application Louvois (chacun ayant son langage de programmation propre : Java, C#, Oracle... ou étant un logiciel tiers).<br>
  • Développement et MCO de l'intégration technique et de l'intégration continue de l'application Louvois<br>
  • Scripting (shell bash) pour la réalisation des builds de l'intégration continue (builds manuels)<br>
  • Analyse et remontée des informations d'erreurs lors des cycles de tests<br>
  • Maintien de la documentation technique et des procédures<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Développement : Bash shell, Linux (Debian/CentOS), Microsoft TFS (Versionning), Oracle 11G<br>
  Méthodologie : Cycle en V sur délai court (3/4 semaines) - Equipe de 2 à 3 personnes

---

### 01/2013 - 07/2013 {.date}
Apprentissage : Projet de fin d'études - à l'école
: 
  *Ecole Polytechnique de l'Université de Tours, France*
  Réalisation d’un système de supervision d’une centrale photovoltaïque (3 panneaux soit 525Wc), permettant l’affichage en continu des informations de production d’énergie, ainsi que les données issues d’une station météo (dans le but d’en mesurer l’impact sur notre production). <br>
  <br>
  Matériel : Micro-onduleurs Enecsys, Station météo Davis, Traqueurs solaires <br>
  Développement : Java, JS/Ajax, CSS, PHP/MySQL (base EmonCMS pour le site intranet)<br>
  Protocoles : Analyse de trames Zigbee, Protocole série de la station Davis<br>

---

### 09/2010 - 09/2013 {.date}
Apprentissage : Projet de fin d'études - en entreprise
: 
  *Hexacomb SA (Industrie du cartonnage) - Amboise, France*
  • Réalisation d’un système de supervision en temps réel de l’état des machines de production (pour suivre les cadences de fabrication sur chaque chaîne), avec un historique des jours, mois, années précédents. <br>
  &nbsp;&nbsp;&nbsp;&nbsp; - Mise au point d'un système embarqué (logiciel et électronique avec capteurs) permettant de récupérer les informations des machines pour les envoyer par WiFi au serveur web<br>
  &nbsp;&nbsp;&nbsp;&nbsp; - Réalisation du site intranet permettant un affichage interactif et temps réel des données obtenues<br>
  <br>
  Matériel : Raspberry Pi, capteurs de courant / distance<br>
  Développement : Java, JS/Ajax, CSS, PHP/MySQL (base EmonCMS pour le site intranet)<br>

<hr class="hiddenhr">

## Formations {.h2short}

### depuis 2020 {.date}
Formations spécialisées
: Ansible (2j) via <a href="https://spherius.fr/formation/devops-ansible/" target="_blank">Spherius.fr</a> • <a href="https://www.scrum.org/user/735488" target="_blank">Professional Scrum Master I (PSM I)</a> • Bases d'AWS (3j) via Conserto

### 2010-2013 {.date}
Ingénieur en Informatique Industrielle, par alternance
: *Ecole Polytechnique de l'Université de Tours, France*
  Alternance dans l'entreprise Hexacomb SA (aujourd'hui Smurfit Kappa), Industrie du cartonnage

### 2008-2010 {.date}
BTS Informatique et Réseaux pour l'Industrie et les Services techniques (IRIS)
: *Lycée Grandmont - Tours, France*

<hr class="hiddenhr">

## Références {.h2short}
1. Annabel Alberto <br>(Responsable DSI France-Travail)
1. Maryan Brussot <br>(Responsable Equipe France-Travail)
1. Cyril Vacher / Sylvain Kozma <br>(Collègues France-Travail)

<hr class="hiddenhr">

### Footer {#footer}
Xavier Touron -- [contact@xtodev.fr](mailto:contact@xtodev.fr) -- (+33) 7.66.65.32.68 -- <a href="https://github.com/xtodev/cv" target="_blank"><img src="./assets/github.png" height="16" width="16" style="vertical-align: middle;"></a>  <a href="https://www.linkedin.com/in/xavier-touron-084b4b73" target="_blank"><img src="./assets/linkedin.png" height="16" width="16" style="vertical-align: middle;"></a> - Mars 2024