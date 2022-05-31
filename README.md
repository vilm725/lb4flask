# my Flask App with Jenkins 🐍

Cursus DeVops 2022 : Une simple application avec Flask pour tester les pipelines avec Jenkins, avec des testes unitaires, une analyse avec SonarQube, envoie des artefacts vers un repo privé Nexus et un CD vers AWS ✅
Un loadbalancer NGINX est placé en front

# Installer les dépendances

pip3 install -r requirements.txt

# Lancer un test avec pytest

```
python3 -m pytest test2.py -v
python3 -m pytest test2.py --cov -v
```

💡 Note : pour la version 3 de python, ajouter 3 devant pip et python 🐍
