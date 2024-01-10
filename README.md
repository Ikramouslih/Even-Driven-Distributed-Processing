# JEE-Activite-Pratique-6
 
L'objectif de cette activité est de mettre en œuvre et de comprendre les principes fondamentaux de l'écosystème Apache Kafka, ainsi que son intégration avec Docker et Spring Cloud Streams. 

### Travail à faire ###

1. Setup : 
- Télécharger Kafka;
- Démarrer Zookeeper; 
- Démarrer Kafka-server; 
- Tester avec Kafka-console-producer et kafka-console-consumer.
- Vidéo à utiliser comme ressources : https://www.youtube.com/watch?v=dXJEzisrFZo&t=2s&ab_channel=ProfesseurMohamedYOUSSFI

2. Avec Docker (voir https://developer.confluent.io/quickstart/kafka-docker/) :
 - Créer le fichier docker-compose.yml;
 - Démarrer les conteneurs docker : zookeeper et kafka-broker;
 - Tester avec Kafka-console-producer et kafka-console-consumer.
 - Vidéo à utiliser comme ressources : https://www.youtube.com/watch?v=9O1Kuk2xXO8

3. En Utilisant KAFKA et Stpring Cloud Streams, Créer : 
- Un Service Producer KAFKA via un Rest Controler;
- Un Service Consumer KAFKA;
- Un Service Supplier KAFKA;
- Un Service de Data Analytics Real Time Stream Processing avec Kaflka Streams;
- Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel.
- Vidéo à utiliser comme ressources : https://www.youtube.com/watch?v=eo8pSWpj2os&authuser=0

## Kafka ##

![kafka-basic-components](https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/86755915-89e5-453c-8e53-9742503fb979)

Kafka est une plateforme de diffusion de données en temps réel et de gestion de flux de données, développée par la Apache Software Foundation. Conçu pour être distribué, durable et tolérant aux pannes, Kafka est utilisé pour la construction de systèmes événementiels et de pipelines de données en temps réel. Voici quelques concepts clés associés à Kafka :
- Topic : Une catégorie ou un flux de messages.
- Producteur : Publie des messages dans les topics.
- Consommateur : S'abonne aux topics et traite les messages.
- Courtier : Serveur Kafka gérant la distribution des messages.
- Zookeeper : Gère la coordination et les métadonnées.
- Partitions : Divise les topics pour un traitement parallèle.
- Streams Kafka : Permet le traitement de flux en temps réel.
- API Connect : Facilite l'intégration avec des systèmes externes.
- Log : Les messages sont stockés de manière séquentielle.

## Spring Cloud Stream ##

Spring Cloud Stream est un projet du framework Spring Cloud qui simplifie le développement d'applications basées sur l'architecture de microservices en fournissant un modèle de programmation pour la création de systèmes de traitement de flux de données. Voici quelques points clés associés à Spring Cloud Stream :
- Modèle Déclaratif : Offre un modèle déclaratif pour la création d'applications de traitement de flux basées sur des fonctions autonomes.
- Binder Abstrait : Utilise un "Binder" pour abstraire la connectivité avec différentes technologies de messagerie, comme Kafka ou RabbitMQ.
- Applications Basées sur des Fonctions : Les applications sont conçues comme des ensembles de fonctions orchestrées pour traiter des flux de données.
- Intégration Kafka : Intégration native avec Apache Kafka pour créer facilement des producteurs et des consommateurs.
- Gestion des Flux : Simplifie la gestion des flux de données avec des abstractions pour la publication, la consommation et le traitement des messages.
- Connectivité Facile : Intégration avec d'autres composants Spring Cloud pour créer des workflows complexes.
- Écosystème Spring Cloud : S'intègre naturellement avec l'écosystème Spring Cloud pour des fonctionnalités supplémentaires.
- Flexibilité : Permet l'extension et la personnalisation du comportement par défaut selon les besoins du projet.

## Manipulation ##
### Partie 1 ###
<img width="960" alt="Screenshot 2024-01-06 224338" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/6496174e-cadc-425a-be27-6325383f3be7">
<img width="960" alt="Screenshot 2024-01-06 224122" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/4f26cb8c-13a7-4571-8e20-59d8a2618444">
<img width="823" alt="Screenshot 2024-01-06 222300" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/0b694e62-2486-4af1-bcc8-b792529d2fd0">
<img width="960" alt="Screenshot 2024-01-06 221050" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/fa4f6967-cb61-471e-ad6a-5b40f73c0a09">
<img width="960" alt="Screenshot 2024-01-06 220431" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/8ed93f8a-b3fe-4a47-b044-8b1b22584644">

### Partie 2 ###
<img width="897" alt="Screenshot 2024-01-07 004507" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/6bc53812-947a-4506-abfa-c35a14ebfe35">
<img width="960" alt="Screenshot 2024-01-07 002514" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/9f035d69-501b-4aa3-a7e5-3e8ba0f13711">
<img width="958" alt="Screenshot 2024-01-06 232552" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/1b79607d-58ff-4c9f-9f5e-4528bf7b8030">
<img width="960" alt="Screenshot 2024-01-06 231241" src="https://github.com/Ikramouslih/Event-Driven-Distributed-Processing/assets/60039200/7f5094ad-25e6-4834-971d-9031056fb0c4">

