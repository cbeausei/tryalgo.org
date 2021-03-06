---
layout: page
title: Résolution de problèmes algorithmiques
---

## Prochaines conférences

- [**AlphaGo explained**](/club/) par Étienne Simon & Jill-Jênn Vie  
jeudi 1<sup>er</sup> décembre 2016 à 19 h à l'ENS Paris-Saclay
- [**Arbres de Merkle : la structure de données à l'origine de git, BitTorrent, Bitcoin et autres blockchains**](/club/) par Jill-Jênn Vie  
vendredi 9 décembre 2016 à 19 h à l'ENS Paris-Saclay

## [pip install tryalgo](/code/)

<a href="{% post_url fr/2016-11-19-swerc-2016 %}"><img src="/fr/images/swerc2016/swerc2016-thumb.jpg" style="float: right" /></a>

Ce site regroupe les ressources suivantes :

- le livre [*Programmation efficace : Les 128 algorithmes qu'il faut avoir compris et codés dans sa vie*](/book/) ;
- [128 algorithmes classiques](/code/) en Python sur [GitHub](https://github.com/jilljenn/tryalgo/tree/master/tryalgo) ;
- différents [problèmes](/problems/) et leurs [solutions](/en/) ;
- le [blog](/fr/) du CAPS, le [club algo](/club/) de l'ENS Paris-Saclay.

Voici un pseudo-code à appliquer pour apprendre un max d'algorithmes :

    import tryalgo                 # import all you can eat

    try:
      problem = read(statement)    # needs organisation
      algo = solve(problem)        # needs skills
      solution = implement(algo)   # needs experience
      answer = submit(solution)
      assert answer == "Accept"
    except Submission_error:
      learn_more()
