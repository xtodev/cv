# Xavier Touron
## Ingénieur DevOps & Dév. backend
<i>Nationalité française, actuellement à Montpellier  <img src="https://cdn-icons-png.flaticon.com/16/317/317182.png" style="vertical-align: middle;"></i>

> [PDF (Complet)](https://github.com/xtodev/cv/releases/latest/download/CV_Touron_Xavier_Full.pdf) [PDF (1 page)](https://github.com/xtodev/cv/releases/latest/download/CV_Touron_Xavier.pdf)<br>
> <img src="https://cdn-icons-png.flaticon.com/16/646/646094.png" style="vertical-align: middle;"> [<b>contact@xtodev.fr</b>](mailto:contact@xtodev.fr)   
> <img src="https://cdn-icons-png.flaticon.com/16/977/977411.png" style="vertical-align: middle;"> <b>(+33) 7 66 65 32 68</b>

------

### Profil {#profile}

Oscille entre les missions de développement backend et les missions Ops afin de mieux appréhender les problématiques DevOps.<br> Une envie insatiable de découvrir et d'apprendre de nouvelles technologies.

------

### Savoir<br> faire {#skills}

* Développement
  : Je développe des applications backend, avec une certaine affinité pour les APIs REST.

* Infra (Ops)
  : Je déploie des stacks EFK sur Kubernetes, j'administre des clusters Elasticsearch, Kafka, Nifi avec des alertes sous Prometheus.

* DevOps
  : Je conçois et déploie des pipelines CI/CD avec Jenkins, Concourse ou encore Github Actions.

-------

### Technos {#technical}

1. Java / Kotlin / C#
1. Kubernetes, Helm
1. Jenkins, Concourse
1. Springboot
1. Stack ELK / EFK
1. Python / Bash Shell
1. Gradle, Maven
1. Kafka, Nifi
1. Docker
1. Git
1. Prometheus, Grafana
1. RegEx

------

### Missions {#experience}

Pole-Emploi
: *OPS/DevOps : Centralisation des logs  (Conserto <img src="https://camo.githubusercontent.com/cf205bfa51e1f09c26909321e5796271fbffbbcd55190fd21d083da1598ee34f/68747470733a2f2f7777772e6d796672656e6368737461727475702e636f6d2f6c6f676f2f353837346634666434666662646c6f676f2d636f6e736572746f2d706963746f6772616d6d652e706e67" height="14">)*
  __Février 2022 - Aujourd'hui__
  Ma seconde plus grosse mission en terme de challenge, passer du côté Ops me donne du fil à retordre et beaucoup de formation en "cours du soir" pour atteindre un niveau confortable.<br><br>
  &nbsp;¤ Centralisation des logs : mettre en place les collectes de logs applicatifs (Nifi/Fluentbit), le parsing d'informations (Grok/RegEx), l'acheminement via Nifi/Kafka jusqu'à Elasticsearch, ainsi que la réalisation de dashboards Kibana.<br>
  &nbsp;¤ Bigdata : Mettre en place les collectes depuis des fichiers textes/csv, APIs ou autres, l'acheminement via Nifi/Kafka jusqu'au lac de données<br>
  &nbsp;¤ Infra : Administrer les stacks K8s<br>
  &nbsp;&nbsp;- Approche GitOps<br>
  &nbsp;&nbsp;- Mise à jour des stacks via Concourse (CI : tests intégration / CD : déploiement K8s)<br>
  &nbsp;&nbsp;- Kafka (Création/Modification/Suppression des Topic, nommage, taille messages, rétention messages…)<br>
	- Superviser les clusters et les agents Nifi (sur les VMs applicatives)<br>
	- Superviser ELK / EFK (PVC, cpu, etc)<br>
	&nbsp;&nbsp;- Alerting Prometheus / Grafana<br>
	&nbsp;&nbsp;- Dashboards Grafana avec les métriques tps réel<br>
	- Faire évoluer et maintenir le produit lors des upgrades de version des progiciels (Nifi, Kafka, ELK)<br>
	- Scripting pour automatiser les taches d'administration courantes<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Observabilité (Stacks K8s)<br>
  &nbsp;&nbsp;&nbsp;&nbsp;Centralisation des logs : Elasticsearch - Fluent/Logstash - Kibana - Kafka - Nifi<br>
  &nbsp;&nbsp;&nbsp;&nbsp;Monitoring : Prometheus - Grafana<br>
  BigData : Apache Nifi, Apache Hive, HDFS, HQL<br>
  DevOps : Concourse, Git, Ansible <br>
  Méthodologie : Mode produit, Kanban - Equipe de 4 à 6 personnes - Exigences Non Fonctionnelles (ENF)

SADA Assurances
: *Développeur Java, Kotlin  (Conserto <img src="https://camo.githubusercontent.com/cf205bfa51e1f09c26909321e5796271fbffbbcd55190fd21d083da1598ee34f/68747470733a2f2f7777772e6d796672656e6368737461727475702e636f6d2f6c6f676f2f353837346634666434666662646c6f676f2d636f6e736572746f2d706963746f6772616d6d652e706e67" height="14">)*
  __Août 2020 - Janvier 2022__
  &nbsp;¤ Développement d'une API back (projet sous Java17 et dockerisé), permettant la génération des éditiques de la SADA (attestations, contrats, devis, etc..) via des templates au format Word/Jrxml et les librairies Aspose/Jasper pour la génération des PDF. Gestion de l'authentification et des rôles via Auth0. Décommissionnement de l'ancien service d'éditiques (Bdoc).<br>
  &nbsp;¤ Développement d'une API pour le RGPD (sous Kotlin, non dockerisé, clean architecture) permettant d'exporter toutes les données (ainsi que leur durée de conservation) d'un individu.<br>
  &nbsp;¤ Correction de nombreuses failles de sécurité (audit externe) dans le code source (Java 8) des projets : failles XSS, gestions des droits, stockage des mots de passes, sessions...<br>
  &nbsp;¤ MCO : Montée de version du framework Springboot et MongoDB sur plusieurs projets, ajout de traçabilité des actions sur les différentes APIs dans le cadre du RGPD. Maintenance sur les CI (Gitlab) et CD (Ansible) de certains projets.<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Développement : Java/Kotlin, Springboot, Jasper/Aspose, Clean Architecture, MongoDB, RabbitMQ, OpenAPI, IntellIJ, Postman, Gradle/Maven, Git, DBeaver<br>
  DevOps : Docker, Gitlab CI, Ansible, Nexus (Registry)<br>
  Méthodologie : Agile (Scrum, Sprints de 3semaines) - Equipe de 4 à 6 personnes

CompuGroup Medical
: *DevOps Jenkins (Conserto <img src="https://camo.githubusercontent.com/cf205bfa51e1f09c26909321e5796271fbffbbcd55190fd21d083da1598ee34f/68747470733a2f2f7777772e6d796672656e6368737461727475702e636f6d2f6c6f676f2f353837346634666434666662646c6f676f2d636f6e736572746f2d706963746f6772616d6d652e706e67" height="14">)*
  __Février 2020 - Juillet 2020__
  Contexte : Améliorer la forge logicielle de CGM avec un mécanisme d'intégration / livraison en continu (CI / CD) pour tous les projets de développement<br><br>
  &nbsp;¤ Mise en place et configuration de l'outillage pour l'intégration continue et le déploiement dédié à une centaine de projets : Jenkins, Sonarqube<br>
  &nbsp;¤ Réalisation des modèles de pipelines pour les projets :<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- C# : Build du projet, exécution des tests unitaires NUnit3 et TestsCoverages avec OpenCover, analyse de la qualimétrie avec SonarQube, livraison en continu  <br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Nuget (package .NET) : Build de la solution Visual Studio, exécution des tests unitaires NUnit3 et TestsCoverages avec OpenCover, analyse de la qualimétrie avec SonarQube, déploiement vers Artifactory<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Packaging Innosetup (génération d'archives autoextractibles) : Création et livraison d'un setup.exe depuis des binaires déjà  existants.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Docker <br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Scripting : Groovy, Bash Shell, Powershell, Cake (C#)<br>
  DevOps : Jenkins, SonarQube, Gitlab, Docker, Artifactory, Teamcity<br>
  Outils : Visual Studio, NUnit, OpenCover, Nuget, Git, Gitversion, FinalBuilder, Innosetup, XMind (mindmaps des pipelines)<br>
  Equipe de 2/3 personnes

Enercal.nc
: *Développeur PHP (ISI.nc <img src="https://isi.nc/images/logo_isi_final.png" height="10">)*
  __Février 2019 - Août 2019__
  Contexte : Développement du backend de l'application mobile d'Enercal, gestionnaire du système électrique néocalédonien. Les 3 derniers mois en télétravail depuis la Nouvelle-Zélande<br><br>
  &nbsp;¤ Développement du backend de l'application mobile Enercal (API REST basée sur un CMS Drupal 7) <br>
  &nbsp;¤ Réalisation du contrat d'interface de l'API (documentation réutilisée par le client en interne) <br>
  &nbsp;¤ Tests de charge / tests unitaires avec Jmeter.<br>
  <br><u>Environnement technique et fonctionnel</u><br>
  Développement : PHP/MySQL (CMS Drupal 7), Postman, Jmeter, Docker, Gradle, Git.<br>
  Méthodologie : Agile (Scrum, Sprints de 2semaines) - Equipe de 2 à 4 personnes

Société Le Nickel (SLN)
: *Développeur JAVA  (ISI.nc <img src="https://isi.nc/images/logo_isi_final.png" height="10">)*
  __Janvier 2017 - Février 2019__
  Une mission très challengeante car j'ai beaucoup appris en très peu de temps sur Kafka, Elasticsearch et l'écosystème K8s dans cette petite startup néocalédonienne (ISI), précurseuse dans ses choix technologiques.<br>
  Développement en équipe (plateau) sur plusieurs applications de la SLN, basées sur le même socle : Architecture micro-services, intégration continue et déploiement automatisé d'images docker via Gitlab CI / Jenkins vers des infras K8s. Principalement :<br>
  &nbsp;¤ Projet d'interconnexion de Maximo (logiciel EAM commercialisé par IBM) avec Reflex (un logiciel WMS produit par le groupe Hardis). Les flux de Maximo (entrée) sont obtenus via la base Oracle et un autre projet interne permettant d'envoyer les données Oracle vers Kafka en temps réel. Les données sont ajustées selon les types de données puis écrites dans des topics Kafka (tampon/scaling) dédiés. Plusieurs jobs Java viendront ensuite dépiler les messages des topics Kafka et effectuer les appels SOAP vers le webservice de Reflex (sortie).<br>
  &nbsp;¤ Projet permettant le suivi de la flotte et des horamètres des véhicules de la SLN en temps réel via l'interconnexion des APIs REST d'Hexagon (logiciel australien de suivi de mines) et de la société fournissant les coordonnées GPS des véhicules (données en entrée)<br>
  &nbsp;¤ Application de suivi exact et détaillé du stock d'explosifs de la SLN via une interface dédiée et épurée basée sur les données de Maximo<br>
  &nbsp;¤ Application en ligne permettant la déclaration des conflits d'intérêts potentiels au sein de la SLN<br>
  &nbsp;¤ Projet permettant de simplifier grandement la saisie des bons de travaux dans Maximo.<br><br>
  Suivi de la qualité du code avec SonarQube, taux de couverture des tests unitaires > 70%<br>
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Développement : Java8, Kafka Streams, Elasticsearch, Guice/Springboot, Gradle, Git. <br>
  DevOps : Gitlab CI, Jenkins, Sonarqube, Docker, kubectl (Kubernetes)<br>
  Méthodologie : Agile (Scrum, Sprints de 2semaines) - Equipe de 2 à 5 personnes

Ministère de la défense - SMSIF
: *Développeur C# (SopraSteria<img src="https://e7.pngegg.com/pngimages/397/511/png-clipart-sopra-steria-orange-s-a-chief-executive-credit-agricole-canal-sop-orange-logo.png" height="13">)*
  __Juillet 2015 - Décembre 2016__
  Contexte : Le service ministériel des systèmes d'information de fonctionnement (SMSIF) est l'organisme chargé de la tierce-maintenance applicative de systèmes d'informations des ressources humaines du Ministère de la Défense. Ma mission porte sur le projet Louvois, permettant la gestion de la solde des militaires, du calcul des indemnités au virement pour chaque administré.
  Développement et MCO du calculateur (application console C#) 
  &nbsp;¤ Réalisation des évolutions et amélioration la qualité du code (SonarQube)
  &nbsp;¤ Maintenance corrective du calculateur (analyse et correction de bugs).
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Développement : C#, Visual Studio 2012, Oracle 11G, Microsoft TFS (Versionning), SonarQube<br>
  DevOps : GitlabCI, Jenkins, Sonarqube, Docker, Kubernetes<br>
  Méthodologie : Cycle en V sur délai court (3/4 semaines) - Equipe de 10 à 15 personnes

Ministère de la défense - SMSIF
: *Intégrateur Technique (SopraSteria<img src="https://e7.pngegg.com/pngimages/397/511/png-clipart-sopra-steria-orange-s-a-chief-executive-credit-agricole-canal-sop-orange-logo.png" height="13">)*
  __Février 2014 - Juillet 2015__
  Intégration technique des différents modules de l'application Louvois (chacun ayant son langage de programmation propre : Java, C#, Oracle... ou étant un logiciel tiers).  
  &nbsp;¤ Développement et MCO de l'intégration technique et de l'intégration continue de l'application Louvois
  &nbsp;¤ Conception et mise à jour des scripts shell (bash/Linux) ainsi que des builds de l'intégration continue (builds manuels)
  &nbsp;¤ Analyse et remontées des informations d'erreurs lors des cycles de tests
  &nbsp;¤ Maintien de la documentation technique et des procédures
  <br>
  <u>Environnement technique et fonctionnel</u><br>
  Développement : Bash shell, Linux (Debian/CentOS), Microsoft TFS (Versionning), Oracle 11G<br>
  Méthodologie : Cycle en V sur délai court (3/4 semaines) - Equipe de 2 à 3 personnes, mixte prestataire / personnel du Ministère de la Défense.

Hexacomb <img src="https://www.orconind.com/wp-content/uploads/2018/07/hexacomb-logo-1.jpg" height="22" style="vertical-align: middle;">
: *Apprenti ingénieur*
  __Sept 2010 - Sept 2013__
  Responsable informatique de l’entreprise  : Gestion des sauvegardes, Active Directory, Installations logicielles/matérielles, Mise en place fibre optique (suivi de prestation externe)<br>
  Réalisation d’un système de supervision en temps réel de l’état des machines de production (en fonctionnement, en réglage, ou machine inutilisée), avec un historique des jours, mois, années précédents. <br>
  &nbsp;¤ Analyse, tests de faisabilité et rédaction du cahier de spécification. 
  &nbsp;¤ Mise au point d'un système embarqué (logiciel et électronique) permettant de récupérer les informations des capteurs (installés sur une machine industrielle) afin de les transmettre au serveur web.
  &nbsp;¤ Réalisation du site intranet permettant un affichage interactif et temps réel des données obtenues.
  <br>
  <u>Environnement technique</u><br>
  Matériel : Raspberry Pi, capteurs de courant / distance<br>
  Développement : Java, JS/Ajax, CSS, PHP/MySQL<br>

Polytech Tours <img src="https://upload.wikimedia.org/wikipedia/commons/9/94/Logo_Polytech_Tours.svg" height="22" style="vertical-align: middle;">
: *Projet de fin d'études*
  __Janvier 2013 - Juillet 2013__
  Réalisation d’un système de supervision d’une centrale photovoltaïque (3panneaux, 525Wc), permettant l’affichage en continu des informations de production d’énergie, ainsi que les données issues d’une station météo (dans le but d’en mesurer l’impact sur notre production). <br>
  Un projet très enrichissant (et toujours d'actualité 10ans après) alliant informatique, électronique et mécanique.<br><br>
  &nbsp;¤ Analyse, test de faisabilité et rédaction du cahier de spécification.<br>
  &nbsp;¤ Fabrication des supports métalliques pour les panneaux photovoltaïques.<br>
  &nbsp;¤ Développement d'une application JAVA, dont le but est de collecter les donnéees des micro-onduleurs ainsi que de la station météo, afin de pouvoir les communiquer au serveur web.<br>
  &nbsp;¤ Réalisation d'un site intranet sur la base d'EmonCMS, un projet open-source lui aussi toujours d'actualité qui permet de traiter et afficher des données temps-réel liées à la production / consommation d'énergie (et autres infos temps réel).<br>
  <br>
  <u>Environnement technique</u><br>
  Matériel : Micro-onduleurs Enecsys, Station météo Davis, Traqueurs solaires <br>
  Développement : Java, JS/Ajax, CSS, PHP/MySQL<br>
  Protocoles : Analyse de trames Zigbee, Protocole série de la station Davis<br>
  
------

<br>
<br>

### Formation {#experience}

Ingénieur en Informatique Industrielle
: *Ecole Polytech' Tours*
  __2010-2013__

BTS I.R.I.S. (Informatique et Réseaux)
: *Lycée Grandmont - Tours*
  __2008-2010__

------

### Langues étrangères {#technical}

1. Anglais (courant)
1. Espagnol (scolaire)
1. Allemand (en cours d'apprentissage)

------

### Hobbies {#technical}

1. Course à pied
1. Cyclisme / VTT
1. Lecture
1. Photographie
1. Dev / Scripting
1. Trading

------

### Footer {#footer}

Xavier Touron -- [contact@xtodev.fr](mailto:contact@xtodev.fr) -- (+33) 7.66.65.32.68 -- <a href="https://github.com/xtodev/cv" target="_blank"><img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" height="16" width="16" style="vertical-align: middle;"></a>  <a href="https://www.linkedin.com/in/xavier-touron-084b4b73" target="_blank"><img src="https://cdn.icon-icons.com/icons2/2248/PNG/32/linkedin_icon_135436.png" height="16" width="16" style="vertical-align: middle;"></a> 

------
