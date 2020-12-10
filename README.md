# Api_Flask_notesApp
# Vous décompressez le zip et vous suivez le readme à l'intérieur.
# 

API REST d'une appplication de Carnet de notes personnel
==

Ps: utiliser la version finale.
==

CarnetNotes utilise Flask comme framework Web, Flask RESTplus pour créer l'API et SQLAlchemy pour gérer le modèle de base de données.
J'utilise une base de données SQLlite pour le développement local.

Pour créez un environnement virtuel et installez les requirements :

    $ python3 -m venv ./venv
    $ source ./venv/bin/activate
    $ pip install -r requirements.txt


Pour initialiser la base de données :  $ python init_db.py

Démarrez le serveur de développement :

    $ FLASK_APP=run.py flask run
      ...
    * Cliquer http://127.0.0.1:5000/ (et CTRL+C pour quitter)

sur votre navigateur, vous avez accès directement en local sur : http://127.0.0.1:5000/


Tests
------

Je travaille sur les tests encore :  $ pytest
J'ai 8 à 9 qui sont Ok pour le moment.

