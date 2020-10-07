# Monte_Carlo_Tree_Search_UTTT_Game

Ce projet a pour but de créer trois intelligences artificielles capables de jouer au jeu Ultimate Tic-Tac-Toe. 
Pour l'implémentation je me suis appuiyée sur le [papier de Sylvain Gelly (Université Paris Sud, LRI, CNRS, INRIA), David Silver (University College London) “Monte-Carlo Tree Search and Rapid Action Value Estimation in Computer Go” March 2011. ](https://github.com/Nada-S/Monte_Carlo_Tree_Search_UTTT_Game/blob/master/mcrave.pdf)

A travers l’application de la recherche arborescente de Monte Carlo, je crée trois IA différentes utilisant trois stratégies pour jouer (cf. papier ci-dessus) 
La première utilisera UCT (Upper confidence Bounds for Trees) 
La seconde utilisera RAVE (Rapid Action Value Estimation)
Et la troisième sera composé d’un mixte des deux premières stratégies.

Je fais jouer ces trois IA face à une stratégie random et entre elles. 
Puis je simule 1000 parties du jeu et récapitule le taux de gain de chaque méthode. 
[Les résultats et l'explication du code sont ici](https://github.com/Nada-S/Monte_Carlo_Tree_Search_UTTT_Game/blob/master/MCTS%20for%20UTTT%20game.pdf)
