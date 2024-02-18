---
title: Cours 3
id: 20240218174707
tags:
  - développement
  - sécuritéNumérique
  - défenseEtSécurité
  - recherche
  - apprentissageAutomatique
  - intelligenceartificielle
  - linguistique
  - annotation
---
Invité : [Bénédicte Goujon](https://www.linkedin.com/in/b%C3%A9n%C3%A9dicte-goujon-1a7590256/?originalSubdomain=fr)
Entreprise : [Thalès](https://www.thalesgroup.com/fr)
Date : 30/01
Laboratoire : [[20240218194805|LRASC]]

La conférence 3 met en lumière l'innovation et l'évolution des méthodes d'extraction d'informations chez Thales, un groupe français de renom opérant dans cinq secteurs d'activité clés : l'identité et la sécurité numérique, le transport terrestre, la défense et la sécurité, ainsi que l'aéronautique et l'espace. Avec un investissement massif de 1 milliard d'euros en R&D, Thales s'est engagé à repousser les frontières de la technologie pour répondre aux défis contemporains. Cette note explore les approches en traitement automatique du langage naturel utilisées chez Thales, du passé au présent, et examine les défis et les opportunités qui façonnent la recherche et le développement dans cette entreprise de pointe.

**Approches NLP chez Thales : Passé et Présent**

Chez Thales, l'extraction d'informations a connu une évolution significative au fil du temps, passant par deux phases distinctes.

**Phase 1 (2000 - 2011)**

- Approche symbolique : Règles, patrons linguistiques écrits manuellement. Utilisation d’Unitex (annotation d’entités), trop limité (coût élevé de la construction des connaissances – besoin d’expertise linguistique – et difficulté de couvrir tous les cas) ;
- Approche statistique : corpus annotés volumineux ;
- TV5 : plateforme de commandes vocales (2000 - 2004) : écriture de grammaires génériques et de lexiques spécifiques pour la reconnaissance vocale pour générer une grammaire spécifique couvrant le maximum de cas ;
- Projet [[20240218205948|Outilex]] : ANR RNTL (2004 - 2006). Gestion du XML, dictionnaires multilingues sur un truc style Unitex. Filtrage thématique de documents audio ;
- 2007 - 2010 : Annotation automatique de l’incertain dans les textes. Contexte : extraction automatique d’événements + aspects (Temps, Incertitude, Polarité et Source) ;

Outil :  [[20240218210305|SemPlus]] pour extraction de relations entre des entités.  

**Phase 2 (2018 - Actuellement)**

- Extraction d’info à partir de tickets décrivant des problèmes de connexion à internet ;
- STRASS (2020) : extraction de relations entre entités (ça ressemble à ce qu’ils avaient fait en java) ;

Voir [[20240218194236|Brevets]]

links : [[20240218215719|_développement]] [[20240218215816|_recherche]] [[20240218215821|_sécuritéNumérique]] [[20240218215713|_défenseEtSécurité]] [[20240218215700|_apprentissageAutomatique]] [[20240218215738|_intelligenceartificielle]] [[20240218215748|_linguistique]] [[20240218215653|_annotation]]