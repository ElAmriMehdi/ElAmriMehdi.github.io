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
* Applet COntainer. 
* Application Client Container.


