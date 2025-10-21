# Introduction au calcul stochastique et détection de sauts dans les cours d’actifs financiers

Ce dépôt contient le rapport de mon projet de recherche réalisé en deuxième année à l’École des Mines de Nancy, au sein du département d’ingénierie mathématique.  
Ce travail a été effectué à l’Institut Élie Cartan de Lorraine (IECL) sous la direction de **Madalina Deaconu** et **Antoine Lejay**.

## Objectif du projet
L’objectif de ce projet est d’étudier les fondements du calcul stochastique et d’explorer leurs applications à la modélisation financière, notamment à la détection de sauts dans les séries temporelles de prix d’actifs.  
Le travail s’appuie sur l’article de **I. Raffaelli, S. Scotti et G. Toscano**, qui propose un modèle à volatilité stochastique intégrant des processus de Poisson et de Hawkes.

## Contenu du rapport
Le rapport présente successivement :
1. Les notions fondamentales de processus stochastiques, martingales et mouvement brownien.  
2. Les outils du calcul stochastique et l’application au modèle de Black & Scholes.  
3. Les processus à sauts (Poisson, Hawkes, et modèles hybrides).  
4. Le test de détection de sauts proposé par **S. Lee et P. Mykland**, ainsi que sa mise en œuvre sur des simulations.

## Méthodologie
- Étude théorique des processus continus et discontinus.  
- Simulation numérique d’actifs suivant différents modèles à sauts (Merton, Kou, Hawkes).  
- Comparaison de la variation bipuissance et de la variation quadratique pour identifier les discontinuités.  
- Implémentation et validation du test de Lee & Mykland sur données simulées.

## Résultats principaux
Le projet montre que les modèles hybrides auto-excités permettent de reproduire à la fois les sauts exogènes et les réactions en chaîne observées sur les marchés financiers.  
Le test de Lee & Mykland s’avère efficace pour distinguer les variations de volatilité des véritables discontinuités de prix.

## Compétences mobilisées
- Calcul stochastique et théorie des martingales  
- Modélisation probabiliste et simulation numérique  
- Méthodes statistiques appliquées à la finance  
- Rédaction scientifique sous LaTeX



