# tutorialXtextSirius
https://github.com/Sofiane-13/tutorialXtextSirius/wiki
# Définir une grammaire DSL avec xtext (pas à pas)  
Pourquoi un DSL ?
    Un DSL (Domain Specific Language) est un langage dédié à une problématique métier spécifique. C’est une notion qui s’oppose aux langages de programmation dits généralistes, de type Java ou C, ou bien aux langages de modélisation généralistes de type UML.
    L’avantage des DSLs réside dans leur puissance d’expression, puisque conçus pour une problématique précise, et dans leur facilité de traitement lorsqu’il s’agit d’effectuer de la validation ou de la transformation (génération de code par exemple).
   En contrepartie, un DSL nécessite de définir un méta-modèle et une notation, ce qui représente un temps de développement et d’apprentissage du langage supplémentaire.
DSL textuel ou graphique ?
  Il y a plusieurs manières de concevoir un DSL.
  Tout d’abord, la définition du DSL peut être envisagée de différentes manières. 
# La création d'éditeurs graphiques (éditeurs UML, représentation de processus, éditeurs de concepts métier, etc.)
Pourquoi Sirius ?

La création d'éditeurs graphiques (éditeurs UML, représentation de processus, éditeurs de concepts métier, etc.) est difficile à intégrer dans un cycle itératif court avec le client, car coûteuse en temps et nécessitant souvent l'apprentissage de technologies ou frameworks complexes. Le projet Eclipse Sirius se propose de faciliter la création d'éditeurs en se basant sur la représentation d'un DSL au sein d'un modèle EMF (Eclipse Modeling Framework). Sirius est un projet Open Source de la Fondation Eclipse. Cette technologie permet de concevoir un atelier de modélisation graphique sur-mesure en s'appuyant sur les technologies Eclipse Modeling, en particulier EMF et GMF. L'atelier de modélisation créé est composé d'un ensemble d'éditeurs Eclipse (diagrammes, tables et arbres) qui permettent aux utilisateurs de créer, éditer et visualiser des modèles EMF.
