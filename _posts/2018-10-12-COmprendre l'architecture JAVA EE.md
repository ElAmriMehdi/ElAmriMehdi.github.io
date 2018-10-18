---
layout: post
title: Comprendre l'architecture JAVA EE
date: 2018-10-12 00:00:00 -0000
tags: [IA, tech, data]
image: JAVAEE.png
---
Ce poste est le premier d'une serie d'arctiles où je vais traiter le JAVA EE. Une connaissace minimale de JAVA SE est nécessaire pour une bonne compréhension. Sans trop tarder, on attaque directement le fond du sujet. 

## Le JAVA EE, c'est quoi ? 
J2EE est un standard qui permet de produire une application entreprise sécurisée, évolutive, disponible et fiable. 
Le standard définie des services qui tournent dans des serveurs qui supportent J2EE. Ces serveurs supportent des containers où 
des composants J2EE peuvent s'executer. 

## Composants et Containers
Les spécifications J2EE définisent un ensemble de containers pour faire tourner les composants J2EE. Un container fournie un environnement d'execution (runtime environment)
pour les composants. Par exemple, le Java standard (J2SE) est valable dans chaque container. 

On peut distinguer un container pour chaque type de composant J2EE: 
* Web Container. 
* EJB Container.
* Applet Container. 
* Application Client Container.

Il existe deux types de composants qui peuvent s'executer dans un serveur J2EE: 
* Composants Web: C'est un composant qui intéragit avec un client web. Les servlets et les JSP font partie de cette famille de composant.
* Composants EJB: Il existe trois types de JavaBean qu'on verra en plus de detail dans les prochains articles: 
  * Session beans.
  * Entity beans.
  * Message-driven Beans.

La figure ci-dessous montre la relation entre les différents containers et composants dans un environnement J2EE. 
![fig1]

## Les Services du Standard J2EE
Les containers doivent fournir un ensemble de services pour chaque composant. On cite quelques services: 
* La connexion: Les containers doivent supporter la connextion vers d'autres composants et application cliente. 
* L'accés et persistance de donnée: l'API JDBC permet la connexion et la manipulation des BDs. 
* La sécurité
* Les transactions...

La figure ci-dessous illustre les services valable dans J2EE
![fig2]



[fig1]: /assets/img/ContainerAndComp.png "Container and Comp"
[fig2]: /assets/img/JavaEEservices.png "JavaEE services"
 
