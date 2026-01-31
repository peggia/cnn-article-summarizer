# cnn-article-summarizer
Étude de différents modèles de génération automatique de résumé de texte
# Contexte
Ce projet s’inscrit dans le cadre du cours CNAM RCP217 Intelligence artificielle pour des données multimédia.
“Il s’agit de produire des résumés de textes à partir d’un corpus de dépèches
de CNN, qui propose, pour chaque document, une série de courts résumés. Chacun des documents étant assez clairement séparé en phrases (à raison d’une phrase par ligne), on pourra essayer d’utiliser cette structure pour limiter les problèmes dus à la taille du texte.”
# Source de données
Le jeu de données utilisé (CNN_STORIES_TOKENIZED) est disponible sur : https://github.com/ JafferWilson/Process-Data-of-CNN-DailyMail
Il contient un ensemble de 92850 dépêches CNN sous forme de fichiers “.story”. Chaque fichier “.story” contient une dépêche/article avec le texte complet de l’article, ainsi que des résumés de référence fournis par CNN (ou “highlights”).
# Objectif
L’objectif de ce projet est de générer automatiquement quelques phrases résumant l'essentiel de l’article en explorant différentes solutions afin de pouvoir les comparer entre elles, avec les standards actuels, en utilisant des métriques adaptées.
# Approche
On a choisi d’adopter une approche itérative, afin d’explorer les deux types principaux de génération de résumés. La vue d’ensemble des étapes est présentée dans la section méthodologie expérimentale.
# Contenu
- pdf du rapport
- ensemble de notebooks correspondant aux differentes itérations
