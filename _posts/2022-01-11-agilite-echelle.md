---
layout: post
title:  "Et si on passait à l’échelle ?"
author: gde
categories: [ Agilité ]
tags: [Agilité]
image: assets/images/agilite-echelle/agilite-echelle.jpg
description: "Et si on passait à l’échelle ?"
featured: true
hidden: false
comments: false
---

Depuis quelques années, nous entendons beaucoup parler d’agilité d’échelle, c’est devenu le sujet à la mode dans l’écosystème agile.
Je vais essayer de vous présenter dans cet article ce dont il est question derrière ce concept d’agilité d’échelle ainsi que les principaux frameworks proposés sur le marché.

Qu’est-ce qu’on appelle agilité à l’échelle ? 

L’agilité à l’échelle ou agile@scale est un concept qui est apparu au début des années 2010 mais qui s’est popularisé ces dernières années avec les transformations agiles mises en place dans les grands groupes.
Initialement réservé aux équipes informatiques, l’agilité s’est progressivement diffusée dans tous les services de l’entreprise. Cette mise à l’échelle a permis, de mon point de vue, de répondre à deux besoins :
- La complexité des produits grandit : technologies utilisées, typologie de clients, canaux de distribution. Ils sont à l’image de l’environnement dans lequel ils évoluent : Time To Market réduit, concurrence, nouveaux usages. Afin de répondre à tous ces enjeux, les entreprises mettent en place des organisations qui nécessitent la collaboration de plusieurs équipes IT.
- Diffuser l’agilité dans l’ensemble des services et départements afin d’en faire une nouvelle culture d’entreprise.
Afin d’accompagner ce changement, les entreprises ont lancé des chantiers importants de déploiement de l’agilité à travers ce qu’on appelle aujourd’hui les transformations agiles.

Les trois frameworks présentés ci-dessous sont les plus connus mais il en existe bien d’autres comme [Scrum at Scale](https://www.scrumatscale.com/), [Nexus](https://www.scrum.org/resources/scaling-scrum), [DAD](https://www.pmi.org/disciplined-agile/process/introduction-to-dad) (Disciplined Agile Delivery) et [Fast Agile](https://www.fastagile.io/) (Fluid Scaling Technology) pour ne citer qu’eux.

##### 1. SAFe (Scaled Agile Framework)

![image](/assets/images/agilite-echelle/safe.png){:class="img-responsive"}

Le framework SAFe a été créé en 2011 par Dean Leffingwell. La version 5 a été publiée en février 2021. D’après [Wikipédia](https://fr.wikipedia.org/wiki/Scaled_agile_framework#Adoption_et_limites), il est le framework agile le plus déployé dans le monde. L’auteur s’est inspiré des pratiques lean, agile et devops pour créer son framework et le diffuser dans les entreprises.

Les principes de SAFe :

![image](/assets/images/agilite-echelle/principes-safe.png){:class="img-responsive"}

SAFe est recommandé pour les équipes de 100 à plusieurs milliers de personnes.
Il propose une organisation multi-équipes appelée ART (pour Agile Release Train afin de développer l'incrément planifié pendant le PI Planning (pour Program Increment Planning).
Le framework met en avant tout un panel de rôles et de rituels afin de déployer l’agilité. Il propose quatre niveaux d’implémentation de son modèle en fonction de la taille et de la maturité de l’organisation :
- Essential : représente le niveau minimum. Permet de synchroniser les équipes d’un même ART.
- Large solution : inclut le niveau essential. Permet de synchroniser plusieurs ART.
- Portfolio : permet d’aligner la stratégie de l’entreprise sur les cycles de développements des équipes.
- Full : intègre les trois niveaux précédents essential, large solution et portfolio.

SAFe est largement décrié dans la communauté agile pour sa complexité de mise en œuvre, son processus rigide et ses nombreuses certifications.

##### 2. Spotify

![image](/assets/images/agilite-echelle/spotify.png){:class="img-responsive"}

Henrik Kniberg et Anders Ivarsson ont publié un document en octobre 2012 décrivant ce qui était mis en place dans les équipes Spotify.

Le modèle Spotify, qui n’en est pas un pour les auteurs, propose une organisation en squads, elles-mêmes regroupées en tribus. Les squads d’une même tribu travaillent sur un domaine fonctionnel ou technique commun.
Afin de créer du lien entre les squads de tribu différente ou d’une même tribu, les équipes ont créé les concepts de chapitre et de guilde. Les chapitres regroupent les personnes ayant la même expertise d’une même tribu afin de partager leurs connaissances. Les guildes sont relativement similaires aux squads mais sont transverses à toute l’organisation.

D’après l’auteur de cet [article](https://www.jeremiahlee.com/posts/failed-squad-goals/), le modèle semble n’avoir jamais été mis en œuvre chez Spotify. Le framework serait donc une ambition de ce que devrait être l’agilité chez Spotify. Il nous est difficile de vérifier les propos de Jeremiah Lee mais il apporte un point de vue intéressant sur ce modèle tant copié par les entreprises.

##### 3. LeSS (Large-Scale Scrum)

![image](/assets/images/agilite-echelle/less.png){:class="img-responsive"}

LeSS a été créé par Bas Vodde et Craig Larman en 2013. Il est en grande partie basé sur Scrum et propose donc une organisation multi-équipes Scrum mais avec quelques changements :
- Le sprint planning : il est organisé en deux parties. La première partie inclut l’ensemble des équipes et permet de synchroniser le travail à venir notamment sur les éventuelles dépendances. Quant à la seconde partie, elle se fait par équipe.
- Le daily Scrum : il se fait par équipe. Si deux équipes travaillent sur la même fonctionnalité, un membre de l’équipe A peut participer au daily de l’équipe B en tant qu’observateur afin de partager les informations.
- Le overvall product backlog refinement : il est optionnel et plus court que le PBR. Il inclut le Product Owner et les membres de toutes les équipes. L’objectif est de décider la répartition des stories sur le prochain sprint.
- Le product backlog refinement (PBR) : il est identique à Scrum. Les équipes peuvent se regrouper si elles travaillent sur des fonctionnalités communes.
- La sprint review : elle se fait avec l’ensemble des équipes.
- La retrospective : elle est identique à Scrum.
- La overall rétrospective : elle inclut le Product Owner, les Scrum Masters et des représentants tournant de chaque équipe. Elle est centrée sur comment améliorer le système dans sa globalité plutôt que sur une seule équipe. Elle dure 1h30 pour un sprint de 2 semaines.

Comme Scrum, une organisation d’équipes LeSS a un seul Product Owner, un seul product backlog, un seul Definition of Done et un même sprint.

Aujourd’hui, les transformations agiles des entreprises sont malheureusement associées à la mise en place de l’un de ces frameworks. SAFe étant l’exemple le plus représentatif de ces changements organisationnels imposés.
Dans notre monde [VUCA](https://en.wikipedia.org/wiki/Volatility,_uncertainty,_complexity_and_ambiguity), devons-nous encore parler de transformation ? Afin de s’adapter à notre environnement complexe, les entreprises doivent évoluer sans cesse afin de ne pas être dépassées par leurs concurrents.
Répondre à la complexité par une organisation complexe comme SAFe, est-ce réellement pertinent ? Personnellement, je ne crois pas. Un système plus "simple" me semble plus adaptable aux difficultés et aux aléas.
SAFe avec son large éventail d’outils et pratiques, se veut très complet et de ce fait, rassure les managers et les directions, par contre, il laisse peu de place à l’adaptation. Un PI Planning a lieu, en règle générale, tous les trois mois. Comment les équipes peuvent-elles s’organiser en cas d’aléas, d’imprévus ou de difficultés ? Lors de ces mêmes PI Planning, les équipes affichent fièrement leurs dépendances entre elles. Ne devraient-elles pas plutôt montrer comment elles vont les résoudre ?

Le modèle [Cynefin](https://en.wikipedia.org/wiki/Cynefin_framework) donne quelques éléments de réponse afin d’évoluer dans un environnement complexe.

![image](/assets/images/agilite-echelle/cynefin.png){:class="img-responsive"}

Dans ce type d’environnement, le framework nous propose un processus de décision basé sur "sonder - sentir - répondre". On est donc dans l’expérimentation. Pour savoir si on est dans la bonne direction, on sonde et on répond. Dans le complexe, il n’y a pas de bonne ou de mauvaise réponse, juste des informations qui nous permettent d’adapter nos pratiques au fur et à mesure. On parle ici de pratiques émergentes.

En conclusion, le passage à l’agilité à l’échelle doit être mûrement réfléchi et non une simple envie de "suivre la mode". L’utilisation d’un framework peut être pertinent, par contre, il ne doit pas contraindre les équipes mais créer un espace de travail propice à l’expérimentation. Sans cela, vous risquez de ne pas voir les bénéfices attendus de cette nouvelle culture d’entreprise.
