# Xavier Touron
## DevOps & JAVA Development Engineer {#subheading}
<span id="langselect"><a href="https://xtodev.fr">🇫🇷</a>&nbsp;&nbsp;<a href="https://xtodev.fr/en.html">🇬🇧</a></span>
> ![Pic](./assets/photo.jpg) {#photo}
[](https://github.com/xtodev/cv/releases/latest/download/CV_Touron_Xavier_EN.pdf)

------

<span id="aboutme">
Graduate engineer with over 10 years' experience in a wide range of skills :<br><br>
  • <b>DevOps</b> : DevOps: CI/CD pipeline design using Jenkins, Concourse or Gitlab CI. Infra-as-code deployments on Kubernetes, task automation via Ansible.<br>
  • <b>Development</b> : Development of backend applications in Java, with an affinity for APIs and microservices.<br>
  • <b>Infra/Ops</b> : Deployment and administration of Elasticsearch, Kafka and Fluentbit stacks on Kubernetes (via Helm)<br><br>
Curious by nature, I have an insatiable appetite for learning new technologies.
</span>

<span id="identity">
+33 7 66 65 32 68<br>
contact@xtodev.fr<br>
Lives in Montpellier, FR<br>
<br>
Married - 2 children<br>
Age 34<br>
French nationality
</span>

<span id="lang">
<u>Languages :</u><br>
French - Mother tongue<br>
English - Advanced (<a target="_blank" href="https://cert.efset.org/MzoJqB">C1</a>)<br>
German - Beginner (A1/A2)
</span>

## PROFESSIONAL EXPERIENCE {.h2long}

### Since 02/2022 {.date}
DEVOPS ENGINEER <span class="ssii"> (Company: Conserto)</span>
: 
*France-Travail (Pôle-Emploi) - Montpellier, France*
  Working as part of the Ops team responsible for centralized logging and big data collection<br>
  • Reworking (with Helm and using Infra-as-Code) of the automated deployments for each element of the whole centralized logging chain<br>
	• Administration of Kafka and Elasticsearch clusters<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Parameter refinement (sizing, retention times, upgrades)<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Supervision, incident resolution, anomaly analysis (e.g. wrong format) using Kibana<br>
  • Administration of Fluent (Kubernetes) and Nifi (on 3000+ Virtual Machines) collection agents<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Development of Ansible roles / AWX to automate the management of Nifi agents<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- GitOps management of Fluent collection agents (deployment to ~30 Kubernetes clusters)<br>
  • Setting up monitoring and alerting to guarantee service availability<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Also watching vulnerabilities for docker images in use<br>
  • Bigdata : Set up data collection from CSV files or APIs to the data lake<br>
  <br>
  <u>Technical and functional environment</u><br>
  IaC deployment and administration of the centralized logging chain : <br>
  &nbsp;&nbsp;&nbsp;&nbsp;Fluentbit & Apache Nifi => Apache Kafka => Logstash (Grok/RegEx) => Elasticsearch/Kibana<br>
  Containers : Docker - Kubernetes - Helm<br>
  Monitoring : Prometheus (AlertManager) - Grafana - OpenTelemetry<br>
  BigData : Apache Nifi, Apache Hive/Iceberg, HDFS, HiveQL<br>
  DevOps : Concourse, Rancher Fleet (gitOps), Ansible, Artifactory, Trivy/Snyk<br>
  Linux environment (Aix, SLES, Debian)<br>
  Work methodology : Product Operating Model / Agile (Scrum) - Team of 4 to 5 people - Non-functional requirements<br>

---

### 08/2020 - 01/2022 {.date}
JAVA DEVELOPMENT ENGINEER <span class="ssii"> (Company: Conserto)</span>
: 
*SADA Assurances - Nîmes, France*
  • Development of a microservice REST API (Java17, Docker) enabling the generation of SADA documents (certificates, contracts, quotes, etc.) using templates in Word/Jrxml format and Aspose/Jasper libraries for PDF generation. Authentication and role management via Auth0<br>
  • Development of a microservice REST API for the GDPR (Kotlin project, clean architecture) enabling all an individual's data to be exported (along with its retention period)<br>
  • Fixing numerous security flaws (external audit) on old Java8 projects: XSS flaws, rights management, password storage, sessions, etc.<br>
  • Maintenance : Upgrading the Springboot and MongoDB framework on several projects, adding traceability<br>
  <br>
  <u>Technical and functional environment</u><br>
  Development : Java/Kotlin, Springboot, Jasper/Aspose, Clean Architecture, MongoDB, RabbitMQ, OpenAPI, IntellIJ, DBeaver(SQL requests), Postman, Gradle/Maven, Git, Linux Gentoo<br>
  DevOps : Docker, Gitlab CI, Ansible, Nexus (Registry)<br>
  Work methodology : Agile (Scrum, 3-week sprints) - Team of 4 to 6 people<br>

<hr class="hiddenhrinpdf">

### 02/2020 - 07/2020 {.date}
DEVOPS ENGINEER <span class="ssii"> (Company: Conserto)</span>
:  
*CompuGroup Medical - Montpellier, France*
  • Setup and configuration of a CI/CD with Jenkins and Sonarqube, dedicated to around a hundred projects :<br>
  • Creation of pipeline models for :<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- C#: project build, execution of NUnit3 unit tests and TestCoverages with OpenCover, quality analysis with SonarQube, continuous delivery <br>
  &nbsp;&nbsp;&nbsp;&nbsp;- NuGet (.NET package): Building the Visual Studio solution, running NUnit3 unit tests and TestsCoverages with OpenCover, analysing quality metrics, deploying to Artifactory<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Innosetup packaging (generation of self-extracting archives) : Build and deliver a setup.exe from existing binaries.<br>
  &nbsp;&nbsp;&nbsp;&nbsp;- Docker (generation of images via Dockerfile and push to the Artifactory registry)<br>
  <br>
  <u>Technical and functional environment</u><br>
  Scripting : Groovy, Bash Shell, Powershell, Cake (C#)<br>
  DevOps : Jenkins, SonarQube, Gitlab, Docker, Artifactory, Teamcity<br>
  Tools : Visual Studio, NUnit, OpenCover, NuGet, Git, Gitversion, FinalBuilder, Innosetup, XMind (pipeline mindmaps)<br>
  Team of 2-3 people

---

### 02/2019 - 08/2019 {.date}
PHP DEVELOPMENT ENGINEER <span class="ssii"> (Company: ISI.nc)</span>
: 
*Enercal (main energy supplier in NC) - Nouméa, New Caledonia*
  Context: Development of the mobile application backend for Enercal, New Caledonia's electricity system manager. I've been working remotely from New Zealand for the last 3 months, on a part-time basis.<br>
  • Development of the REST API in PHP, based on a Drupal 7 CMS<br>
  • Writing the API interface contract (documentation reused internally by the client)<br>
  • Load testing and unit testing with JMeter. <br>
  <br><u>Technical and functional environment</u><br>
  Development : PHP/MySQL, Postman, Jmeter, Docker, Gradle, Git.<br>
  Work methodology : Agile (Scrum, 2-week sprints) - Team of 2 to 4 people<br>

---

### 01/2017 - 02/2019 {.date}
JAVA DEVELOPMENT ENGINEER <span class="ssii"> (Company: ISI.nc)</span>
: 
  *Société Le Nickel (main industrial company in NC) - Nouméa, New Caledonia*
  Team development on several Java applications for SLN, based on the same Micro-services architecture, continuous integration and automated deployment of docker images via Gitlab CI / Jenkins to Kubernetes infrastructure.<br>
  • Project to track SLN's fleet and vehicle timetables in real time via interconnection of the REST APIs of Hexagon (Australian mine-tracking software) and the New Caledonian local company providing the GPS coordinates of the vehicles<br>
  • Project to interconnect Maximo (asset management software by IBM) with Reflex (a logistics management software by Hardis). <br>
  &nbsp;&nbsp;&nbsp;&nbsp;To sum up: Maximo (Oracle2Kafka) => Kafka (buffering/scaling) => Reflex (SOAP calls)<br>
  • Application for accurate, detailed monitoring of SLN's explosives stock via a dedicated, streamlined interface based on Maximo data<br>
  • Online application for declaring potential conflicts of interest within SLN<br>
  • Project to simplify the entry of work orders in Maximo by directly modifying its database<br>
  <br>
  <u>Technical and functional environment</u><br>
  Development : Java8, Kafka Streams, Elasticsearch, Guice/Springboot, Gradle, Git. <br>
  DevOps : Gitlab CI, Jenkins, Sonarqube (test coverage rate > 70%), Docker, Kubernetes<br>
  Work methodology : Agile (Scrum, 2-week sprints) - Team of 2 to 5 people

---

### 07/2015 - 12/2016 {.date}
C# DEVELOPMENT ENGINEER <span class="ssii"> (Company: SopraSteria)</span>
: 
  *Ministry of Defence (Service ministériel des SI de fonctionnement) - Tours, France*
  Context: The SMSIF-RH is the organisation responsible for the third-party application maintenance of the French Ministry of Defence's human resources information systems. My assignment was on the Louvois project, which manages the wages of military personnel, from the calculation of allowances to the payment for each member of the armed forces.<br>
  • Development (or upgrade) of allowances in the calculator (C# console application)<br>
  • Maintenance, upgrades and improvements to code quality (SonarQube)<br>
  <br>
  <u>Technical and functional environment</u><br>
  Development : C#, Visual Studio 2012, Oracle 11G, Microsoft TFS (Versionning), SonarQube<br>
  Work methodology : V cycle on a short timescale (3/4 weeks) - Team of 10 to 15 people

---

### 02/2014 - 07/2015 {.date}
TECHNICAL INTEGRATION ENGINEER <span class="ssii"> (Company: SopraSteria)</span>
: 
  *Ministry of Defence (Service ministériel des SI de fonctionnement) - Tours, France*
  Technical integration of the various modules of the Louvois application (each with its own programming language: Java, C#, Oracle... or being third-party software)<br>
  • Development and maintenance of the technical integration and continuous integration of the Louvois application<br>
  • Bash shell scripting for continuous integration builds (manual builds)<br>
  • Analysis and feedback of error information during test cycles<br>
  <br>
  <u>Technical and functional environment</u><br>
  Development : Bash shell, Linux (Debian/CentOS), Microsoft TFS (Versionning), Oracle 11G<br>
  Work methodology : V cycle on a short timescale (3/4 weeks) - Team of 2 to 3 people

---

### 01/2013 - 07/2013 {.date}
Apprenticeship: Final year project - at school
: 
  *Polytechnic School of the University of Tours, France*
  Development of a supervision system for a photovoltaic power plant (3 panels, i.e. 525Wp), enabling continuous display of energy production data, as well as data from a weather station (with the aim of measuring the impact on our production). <br>
  <br>
  Equipment : Enecsys microinverters, Davis weather station, solar trackers<br>
  Development : Java, JS/Ajax, CSS, PHP/MySQL (intranet site based on EmonCMS)

---

### 09/2010 - 09/2013 {.date}
Apprenticeship: Final year project - in company
: 
  *Hexacomb SA (Cardboard industry) - Amboise, France*
  • Development of a real-time supervision system for the status of production machines (to monitor production rates on each line), with a history of previous days, months and years <br>
  &nbsp;&nbsp;&nbsp;&nbsp; - Development of an on-board system (software and electronics with sensors) to retrieve information from the machines and send it via WiFi to the web server.<br>
  &nbsp;&nbsp;&nbsp;&nbsp; - Creation of an intranet site enabling real-time interactive display of the data obtained.<br>
  <br>
  Hardware: Raspberry Pi, current/distance sensors<br>
  Development : Java, JS/Ajax, CSS, PHP/MySQL

<hr class="hiddenhr">

## Education and courses {.h2short}

### Since 2020 {.date}
Specialized training
: Ansible (2d) via <a href="https://spherius.fr/formation/devops-ansible/" target="_blank">Spherius.fr</a> • <a href="https://www.scrum.org/user/735488" target="_blank">Professional Scrum Master I (PSM I)</a> • Basics of AWS (3d) via Conserto
  Cloud Azure (5d) : [AZ-900](https://www.youtube.com/watch?v=5abffC-K40c) (Basics) |  [AZ-204](https://www.youtube.com/watch?v=jZx8PMQjobk) (Developer) | [AZ-400](https://www.youtube.com/watch?v=11KT1hPNkY4) (DevOps) via FreeCodeCamp

### 2010-2013 {.date}
Industrial Computing Engineer, by apprenticeship
: *Polytechnic School of the University of Tours, France*
  Work experience at Hexacomb SA (now Smurfit Kappa), cardboard industry

### 2008-2010 {.date}
BTS (BAC+2) in Computer Science and Networks for Industry and Technical Services
: *Grandmont High School - Tours, France*

<hr class="hiddenhr">

## References {.h2short}
1. Annabel Alberto <br>(France-Travail IT manager)
1. Maryan Brussot <br>(France-Travail Team Leader )
1. Cyril Vacher / Sylvain Kozma <br>(France-Travail colleagues)

<hr class="hiddenhr">

### Footer {#footer}
Xavier Touron -- [contact@xtodev.fr](mailto:contact@xtodev.fr) -- (+33) 7.66.65.32.68 -- <a href="https://github.com/xtodev/cv" target="_blank"><img src="./assets/github.png" height="16" width="16" style="vertical-align: middle;"></a>  <a href="https://www.linkedin.com/in/xavier-touron-084b4b73" target="_blank"><img src="./assets/linkedin.png" height="16" width="16" style="vertical-align: middle;"></a> - July 2024